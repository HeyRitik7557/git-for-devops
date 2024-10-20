# Git Commands

## Setup
- **Configure User Name**  
  `git config --global user.name "Your Name"`
  
- **Configure User Email**  
  `git config --global user.email "your_email@example.com"`

## Repository Management
- **Initialize a New Repository**  
  `git init`
  
- **Check Repository Status**  
  `git status`
  
- **View Commit History**  
  `git log`

## Branching
- **Create a New Branch**  
  `git checkout -b branch-name`
  
- **List All Branches**  
  `git branch`
  
- **Switch to Another Branch**  
  `git checkout branch-name`

## Staging Changes
- **Add a File to Staging**  
  `git add file-name`
  
- **Add All Changes to Staging**  
  `git add .`

## Committing Changes
- **Commit Staged Changes**  
  `git commit -m "commit message"`

## Viewing Changes
- **Show Differences**  
  `git diff`

## Remote Repositories
- **Add a Remote Repository**  
  `git remote add origin repository-url`
  
- **Push Changes to Remote**  
  `git push origin branch-name`
  
- **Pull Changes from Remote**  
  `git pull origin branch-name`

## Undoing Changes
- **Remove a File from Staging**  
  `git reset file-name`
  
- **Restore a Deleted File**  
  `git restore file-name`
  
- **Undo Last Commit (keep changes)**  
  `git reset HEAD~1`

## Miscellaneous
- **Show Current Branch**  
  `git branch --show-current`
  
- **View All Files in the Repository**  
  `ls -a`
  
- **Create an Empty File**  
  `touch file-name`

## Notes
- Replace `branch-name`, `file-name`, and `repository-url` with your specific details.
