# Git Commands Reference

## Initialization
- **Initialize a new Git repository**:
  `git init`

## Configuration
- **Set global user name**:
  `git config --global user.name "Your Name"`

- **Set global user email**:
  `git config --global user.email "your.email@example.com"`

- **Check your Git configuration settings**:
  `git config --list`

## Staging
- **Add specific files to staging**:
  `git add <file-name>`

- **Add all files to staging**:
  `git add .`

- **Remove a file from staging**:
  `git reset <file-name>`

- **Unstage all files**:
  `git reset`

## Committing
- **Commit changes to the repository**:
  `git commit -m "commit message"`

- **Commit changes without staging**:
  `git commit -a -m "commit message"`

- **Amend the last commit**:
  `git commit --amend`

## Logs
- **Show the commit history**:
  `git log`

- **Show the commit history with a one-line summary per commit**:
  `git log --oneline`

- **Show a specific commit log by commit hash**:
  `git log <commit-hash>`

## Creating a Branch
- **Create a new branch**:
  `git branch <branch-name>`

- **Create and switch to a new branch**:
  `git checkout -b <branch-name>`

- **Switch to an existing branch**:
  `git checkout <branch-name>`

- **List all branches**:
  `git branch`

## Deleting a Branch
- **Delete a local branch**:
  `git branch -d <branch-name>`

- **Force delete a local branch**:
  `git branch -D <branch-name>`

- **Delete a remote branch**:
  `git push <remote-name> --delete <branch-name>`
