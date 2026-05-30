# Git Daily Commands

## Initial Git Setup

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list
```

## Clone Repository

```bash
git clone https://github.com/user/repo.git
cd repo
```

## Check Status

```bash
git status
```

## Check Current Branch

```bash
git branch
```

## Fetch Latest Changes

```bash
git fetch
```

## Pull Latest Changes

```bash
git pull origin main
```

## Create New Branch

```bash
git checkout -b feature-login
```

or

```bash
git switch -c feature-login
```

## Switch Branch

```bash
git switch main
```

## Add Changes

```bash
git add .
```

## Add Specific File

```bash
git add file_name
```

## Commit Changes

```bash
git commit -m "Add new feature"
```

## Push Changes

```bash
git push origin main
```

## Push New Branch

```bash
git push -u origin feature-login
```

## Merge Branch

```bash
git checkout main
git merge feature-login
```

## View Commit History

```bash
git log --oneline
```

## View Detailed History

```bash
git log
```

## View Changes

```bash
git diff
```

## View Staged Changes

```bash
git diff --staged
```

## Stash Changes

```bash
git stash
```

## View Stash List

```bash
git stash list
```

## Restore Stash

```bash
git stash pop
```

## Undo Unstaged Changes

```bash
git restore .
```

## Unstage Files

```bash
git restore --staged .
```

## Delete Local Branch

```bash
git branch -d feature-login
```

## Force Delete Branch

```bash
git branch -D feature-login
```

## Delete Remote Branch

```bash
git push origin --delete feature-login
```

## View Remote Repositories

```bash
git remote -v
```

## Add Remote Repository

```bash
git remote add origin https://github.com/user/repo.git
```

## Create Tag

```bash
git tag v1.0
```

## Push Tag

```bash
git push origin v1.0
```

## Push All Tags

```bash
git push --tags
```

## Daily Workflow

```bash
git pull origin main

git checkout -b feature-name

# Make changes

git add .
git commit -m "Implement feature"

git push -u origin feature-name

# Create Pull Request on GitHub

git checkout main
git pull origin main
git branch -d feature-name
```
