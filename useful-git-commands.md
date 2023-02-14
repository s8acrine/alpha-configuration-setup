# Useful Git Commands

## Learning Git and GitHub with Alpha

### Useful Commands
- git clone file-name
- - Pulls file-name from GitHub
- git status
- git add file-name
- git commit -m "message"
- git push origin main
<br><br>
### Vocabulary

- repository (repo) 
  - A named folder on GitHub
- git
  - version control software
- GitHub
  - Online platform for git, GUI for sharing code and collaboration
- local 
  - your personal computer
- commit
  - adding a tracking number and message to your version
- diff
  - the difference between states of your local and GitHub repository

### Common Errors
- Make sure to git add all files you want to add to tracking so you can push all at once


This is testing different commit messages on different files in a single push

## Notes about branching
- use git checkout -b name-of-branch to create a new branch
- use git checkout name-of-branch to change what branch you are on
- use git branch to list out what branches exist 
- use git pull origin name-of-branch to pull that branch onto your local

### Branching Vocabulary

- branch 0 an alternative timeline where a developer can code safely
- main - the branch that is the source of truth, only working code should be here
- checkout - command to navigate between branches
- checkout -b creates a new branch that doesn't exist
- deleting a branch - has to be deleted on local AND GitHub

### Branching Commands
- $ `git checkout -b branch-name` - creates and navigates to a new branch
- $ `git branch` - lists all the current branches on your local
- $ `git branch -d branch-name` - deletes branch-name from your local
- $ `git checkout branch-name` navigates to branch-name
