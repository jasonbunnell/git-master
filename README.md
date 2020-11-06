# Git Master
These are my notes from the GitHub Ultimate: Master Git and GitHub course on Udemy

## 4.23 Backing Out Changes
1. Unstage an added file by resetting HEAD
1. THe file file-name should now be unstaged
1. Discard changes in unstaged file by checking out file
Example:
```
git reset HEAD <file-name.file>
git checkout -- <file-name.file>
```

## 4.24 History and Making New Commands with Alias
1. Create an alias for a git command with git config alias.name
1. See a list of git config changes
Example:
```
git config --global alias.hist "log --oneline --graph --decorate --all"
git config --global --list
```

## 4.25 Rename and Delete files
1. Instead of renaming with mv you can use git mv
1. To remove git rm <file-name.file>

## 4.27 Git Ignore


# Important git commands
### Rename or Remove file and update git
```
git add -A
```
### Modified Log command
This command is a modified version of git log that has --oneline --graph --decorate -all flags
```
git hist
```
