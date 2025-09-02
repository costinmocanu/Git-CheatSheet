# Git-CheatSheet

## Configure Git

Install Git: Download from git-scm.com.

## Configure Git

* git config --global user.name "Your Name"
* git config --global user.email "your.email@example.com"
* git config --list – View settings.

## Repository Basics
### Repository Basics
#### Repository Basics
##### Repository Basics

git init – Initialize a new Git repository.
git clone <url> – Clone a repository from GitHub.
git status – Check the status of your working directory.
git add <file> – Stage a specific file.
git add . – Stage all changed files.
git commit -m "message" – Commit staged changes.
git push origin <branch> – Push changes to GitHub.
git pull origin <branch> – Pull changes from GitHub.

Branching

git branch – List all branches.
git branch <name> – Create a new branch.
git checkout <name> – Switch to a branch.
git checkout -b <name> – Create and switch to a branch.
git merge <name> – Merge a branch into the current branch.
git branch -d <name> – Delete a local branch.
git push origin --delete <name> – Delete a remote branch.

Collaboration

git remote add origin <url> – Link local repo to GitHub.
git remote -v – View remote connections.
git fetch origin – Fetch changes without merging.
Sync a fork:
git remote add upstream <original-repo-url>
git fetch upstream
git merge upstream/main


Pull Requests: Create via GitHub’s web interface.

Troubleshooting

git reset --soft HEAD~1 – Undo last commit (keep changes).
git clean -f – Remove untracked files.
Resolve merge conflicts:
Edit conflicting files.
git add <file> to mark resolved.
git commit to complete.


git log --oneline – View commit history.

Tips

Commit often: Small, frequent commits are easier to manage.
Use meaningful messages: Clear commit messages improve collaboration.
Backup before merging: Use branches to test merges.
Explore GitHub: Use the web interface for PRs, issues, and reviews.
