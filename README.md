# GIT COMMANDS

This repository contains a handy reference for commonly used Git commands.

## Table of Contents

- [Basic Commands]
- [Branching & Merging]
- [Remote Repositories]
- [Stashing & Cleaning]
- [Logs & History]

## Basic Commands

| Command | Description |
| --- | --- |
| `git init` | Initialize a new Git repository |
| `git clone <repo_url>` | Clone an existing repository |
| `git status` | Check the status of the working directory and staging area |
| `git add <file>` | Stage changes for commit |
| `git commit -m "message"` | Commit staged changes with a message |
| `git push` | Push local commits to a remote repository |
| `git pull` | Fetch and merge changes from a remote repository |
| `git diff` | Show differences between working directory and staging area |

## Branching & Merging

| Command | Description |
| --- | --- |
| `git branch` | List all branches |
| `git branch <branch_name>` | Create a new branch |
| `git checkout <branch_name>` | Switch to a specific branch |
| `git checkout -b <branch_name>` | Create and switch to the branch |
| `git merge <branch_name>` | Merge a branch into the current branch |
| `git rebase <branch_name>` | Reapply commits on top of another base branch |
| `git rebase -i HEAD~<n>` | Interactive rebase to edit,split,squash,delete commits |
| `git branch -d <branch_name>` | Delete a branch |

## Remote Repositories

| Command | Description |
| --- | --- |
| `git remote -v` | Show remote repositories |
| `git remote add <name> <url>` | Add a new remote repository |
| `git push -u origin <branch>` | Push a branch to a remote repository and track it |
| `git fetch` | Fetch changes from a remote repository |
| `git remote remove <name>` | Remove a remote repository |

## Stashing & Cleaning

| Command | Description |
| --- | --- |
| `git stash` | Stash changes without committing |
| `git stash pop` | Apply the latest stashed changes |
| `git stash apply stash@{n}` | Apply a specific stash  |
| `git stash list` | List all stashes |
| `git stash drop stash@{n}` | Remove a specific stash |
| `git clean -f` | Remove untracked files |

## Logs & History

| Command | Description |
| --- | --- |
| `git log` | Show commit history |
| `git log --oneline` | Show condensed commit history |
| `git blame <file>` | Show who modified each line in a file |
| `git show <commit_hash>` | Show details of a specific commit |
| `git reflog` |  recover lost commits even after a destructive reset or rebase |
