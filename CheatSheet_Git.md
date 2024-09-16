# Git Cheetsheat

## Getting Started

`git init`

or 

`git clone url`

### Configuration

```
git config --global user.name "John Doe"
git config --global user.email foo@citrix.com
```

## Working with Local Branch
```bash
# Switch to existing local branch
git checkout branchname

# Checkout current branch into a new branch
git checkout -b new-branch-name

# Merge branch-name into the current branch
git merge branchname

# Soft branch delete
git branch -d branchname

# Hard branch delete
git branch -D branchname

```


### Standard Flow
```bash
# See all commits
git log

# Pretty commit view
git log --pretty=oneline

# See status of your current git branch. 
git status

# Add modified file to be commited(aka stage the file)
git add filename

# Add all modified files to be commited(aka stage all files)
git add .

# A short hand for commiting files and writing a commit message via one command
git commit -m "Some commit message"

```

### Working with Remote Branch
```bash
# See list of remote repos available. 
git remote

# Add a new remote. I.e. origin if it is not set
git remote add origin <https://some-git-remote-url>

# Push current branch to remote branch
git push

# Otherwise you can manually specify remote and branch to use every time
git push origin branchname

# Just like pushing, you can get the latest updates from remote. 
git pull

# Or you can tell git to pull a specific branch
git pull origin branchname
```


### Essential Git Commands
```bash
git init
git config --global user.name "John Doe"
git config --global user.email foo@citrix.com

git clone url

git status
git add .
git add file_name
git commit -m "Some commit message"
git push
```


