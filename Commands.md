# Git Commands Cheat Sheet

## Configuration
- **Set user name and email**
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your_email@example.com"
  ```

## Initializing a Repository
- **Initialize a new repository**
  ```bash
  git init
  ```

## Cloning a Repository
- **Clone an existing repository**
  ```bash
  git clone <repository_url>
  ```

## Staging and Committing Changes
- **Stage specific files**
  ```bash
  git add <file_name>
  ```
- **Stage all changes**
  ```bash
  git add .
  ```
- **Commit changes**
  ```bash
  git commit -m "Commit message"
  ```

## Checking Repository Status
- **Check the status of the repository**
  ```bash
  git status
  ```
- **View commit history**
  ```bash
  git log
  ```

## Viewing Changes
- **View unstaged changes**
  ```bash
  git diff
  ```

## Branching and Merging
- **List branches**
  ```bash
  git branch
  ```
- **Create a new branch**
  ```bash
  git branch <branch_name>
  ```
- **Switch to a branch**
  ```bash
  git switch <branch_name>
  ```
- **Merge a branch**
  ```bash
  git merge <branch_name>
  ```
- **Delete a branch**
  ```bash
  git branch -d <branch_name>
  ```

## Working with Remote Repositories
- **Add a remote repository**
  ```bash
  git remote add origin <repository_url>
  ```
- **Push changes to a remote repository**
  ```bash
  git push origin <branch_name>
  ```
- **Pull changes from a remote repository**
  ```bash
  git pull origin <branch_name>
  ```
- **Fetch changes without merging**
  ```bash
  git fetch origin
  ```

## Undoing Changes
- **Unstage a file**
  ```bash
  git reset <file_name>
  ```
- **Reset to a specific commit**
  ```bash
  git reset --hard <commit_hash>
  ```
- **Revert a commit**
  ```bash
  git revert <commit_hash>
  ```

## Temporary Changes
- **Stash uncommitted changes**
  ```bash
  git stash save "Stash message"
  ```
- **Apply stashed changes**
  ```bash
  git stash apply
  ```

## Tagging
- **Create a tag**
  ```bash
  git tag <tag_name>
  ```
- **Delete a tag**
  ```bash
  git tag -d <tag_name>
  ```
- **Push a tag to a remote repository**
  ```bash
  git push origin <tag_name>
  

