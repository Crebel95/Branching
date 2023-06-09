# Git Cheat Sheet

List of common git commands, and practice with branching and merging

## Basic Commands
* 'git init' - initalize local repository
* 'git add' - add current working folder contents to local repo index
* 'git commit -m "message"' - commit staged work to local repo, with commit message

## Info Commands
* 'git status' - show commit status of local working folder
* 'git log' - list commit history of local repo
* 'git log --oneline' - list commit history (compact format)
* 'git config -l' - list local Git configuration settings

## Branch Commands
* 'git branch' - list local branches
* 'git branch -m newName' - rename current local branch
* 'git branch branchName' - create local branch 'branchName'
* 'git checkout branchName' - move to local branch 'branchName'
* 'git checkout -b branchName' - create and move to local branch 'branchName'

## Remote Commands
* 'git remote add reName remoteUrl' - connect local repo to remote repository 'remoteUrl' with shortcut 'reName' for remote URL
* 'git push reName branchName' - push local commits to remote branch


