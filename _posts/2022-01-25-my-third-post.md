---
layout: post
title: GitHub codes
subtitle: Summarize most of github commands
categories: GitHub
tags: [guide, commands, github]
---
#Source
https://app.datacamp.com/learn/courses/introduction-to-git
-------
git status : Check changes in the file
git diff : Shows the changes occurs in the repository
git diff directory : Shows the changes occurs in the directory
git diff -r HEAD path/to/the file : Compare changes occur (-r), to the latest commit (HEAD)
git add + filename : Add to the staging area
Nano + filename: To edit file 
Use:
 Ctrl +o to save, then press enter
 Ctrl + X to exit
 Ctrl + K to delete
 Ctrl + U to un-delete

git commit -m “write message you want”  : To write notes /messages.
Note : if you want to write long messages (more than a line), do not use -m

git commit –amend -m “new message “ : To undo/edit  commit message, and write new one.
git show  #commit’s hash : To show specific commit, use git show with first few characters of commit’s hash, i,e git show 02dcf9
git log : View the project’s history
Note : if use git log -number+filename, will show only output restrict to this number, i.e git log -5 filename, shows only last 5 output

git reset HEAD : Unstage recent staged file
git checkout - - path/to/thefile : Undo unstaged changes
git checkout #commit’s hash+file name : Replace current version with version you want
git branch :Shows all repository’s branch
Note : The branch that you are currently in, will have * next to it

git checkout -b branch-name : Create a branch and switch to it
git merge source destination : Merge two branches together
git init project-name : Create new repository for new project
git clone/ existing project/ new project name : Clone repository
git annotate file : Shows the last changes details,i.e who and when
git clean -v : Files that git is not tracking recently
git config – list : Change default settings
git pull : Pull changes from branch
git push : Push changes into remote repository
git remote : List remotes names
Note use git remote -v, to show the remote’s URLs




