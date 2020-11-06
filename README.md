# Git Master
These are my notes from the GitHub Ultimate: Master Git and GitHub course on Udemy

## 4.23 Backing Out Changes
1. Unstage an added file with ```git reset HEAD <file-name.file>
1. THe file file-name should now be unstaged
1. Discard changes in unstaged file with ```git checkout -- <file-name.file>

## 4.24 History and Making New Commands with Alias
1. Create an alias for a git command with ```git config --global alias.hist "log --oneline --graph --decorate --all"```
1. See a list of git config changes with ```git config --global --list```
