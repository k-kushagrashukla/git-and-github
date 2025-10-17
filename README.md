# git-and-github

## Git (VCS-Version Control System)
- Git is nothing but it tracks changes in the files , which we or you made
- It is free and Open-source , so it can be used by me or you or by your family , basically everyone
- Also Git is a software nothing mpre than that and nothing less than that

## VCS (Version Control System)
- basically VCS are used to store and manage the history of code
- VCS allow us that you can track changes to your code and collaborate with others
- previous version called as SCCS-Source Code Control System
- so it is nothing but a Git

## Github ( it is a home where everyone stores their code)
- Github is an web-hoisting service for Git repos.
- it is an online way by which you can store your code and share your code with others.
- it is one of the most famous open -sorce platform for sharing and storing code
- thats why you and i never heard of any other platform , bcz they are not good as github :)

### For installing Git 
```
https://git-scm.com/downloads. ## link for git download
```
## Repository 
- It is nothing but a file which stores all of your code and manage them .
- for chaecking the status of your repo u can run
```
git status
```
## Creating a repo
- basicallly you are just asking git to tarack your repo
- to creat a repo you have to do :
```
git status
git init
```
- "git status": this command will show the cureent state of your repo
- "git  init": this will create a new folder on your system and initalize as git repo

**commit** - it is nothing but a way to save your changes to your repo 
- by this you can go back and see which change is done at what time and when...
<img width="636" height="140" alt="Screenshot 2025-10-17 124925" src="https://github.com/user-attachments/assets/1be8ba39-0b03-43dd-bd0c-ae73f7585d59" />

### Basic Flow
- when you want to first track a new folder , we use **init** command
- then we use **add** command to add that folder to the repo
- then only we use **commit** command to save the changes
- finally **push** command to push that thing to github.

### Git Log
- this command show the history of your reoo
- basicllay show all commits to your repo
```
git log
```
### gitignore
- basically it is a file or folder which contain those things which git should ignore
- it is a way for us by which we can prevent some files tracking from git
- you can create a gitignore file and add list of files and folders to ignore
- like your crush ignore you , it works same
```
.gitignore
- node _modules
-.env
```
### Branches
- Branches are a way to work on diff versions of proj at the same time.
- this is useful when you want to make changes to a project without affecting the main branch
- someone can work on header , some on foooter, some on content , that's the beauty of branches
<img width="818" height="244" alt="kygr9tcv4grxb91yngsa" src="https://github.com/user-attachments/assets/bc72b6f3-92c7-47ce-b75f-767145c31faa" />

### Git Diff
- it is an command which shows the difference btw two commits
- bascially it show the changes made in on ecommit and and in other commit
- #### Comparing two branches
- this command compare the difference btwo two branches.
```
git diff <branch-name-one> <branch-name-two>
```
### Git stash
- it is like a stack
- this command saves your changes in a temporary location
- it is useful when you switch from one brach to another without loosing your code
```
git stash
```
- you can view the list of stashes by using this command
```
git stash list
```
- we can apply and drop stash
```
git stash pop
```
- this command applies the stash & drop it from the stash list
- drop the stash by this command
```
git stash drop
```
### git clone [url]
- retrieve an entire repository from a hosted location via URL
- most imp part for us :)
---
- most of the things are done for git and github , if u want to know more about commands then looks at this cheatcode
- https://education.github.com/git-cheat-sheet-education.pdf

