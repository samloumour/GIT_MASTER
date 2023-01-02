# GIT_MASTER

## The Git commands you absolutely need to know!
## Basic commands 

### Git init
To create localy a new repository 
````git
git init 
````
### Clone git 
to create localy a copy of a remote repository 
````
git clone path/of/your/remote/repository
````
### Git add
to add the file from the local repository to remote repository 
````
git add README.md
````
We can add all the file once and for all throught the following command:
````
git add .
````
### Git commit 
The git commit command is used to commit the changes made to the HEAD. Note that not all commits will go to the remote repository.
````
git commit –m “Description of your commit”
````
### Git push 
git push is a command to push local changes to the associated branch, for example : to push the changes to master branch:
````
git push origin master
````
## Git status
to displays the list of modified files as well as files that still need to be added or validated, we use:
````
git status
````
## Branch commands 

### Git checkout 
To create a new branch: 
````
git checkout -b <branch-name-to-be-created>
````
To list all the branches present in the repository, we use:
````
git branch
````
To simply switch from one branch to another, we use:
````
git checkout <branch-name-desired>
````
To delete a branch 
````
git branch –d <branch-name-to-be-deleted>
````
## Git diff
The command git diff allows the user to know the list of the conflicts

To visualise the confict between two brnaches, we use:
````
git diff <source-branch> <target-branch>
````
## Git merge 
The git merge command is used to merge a branch into the active branch. We use:

````
git merge <branch-name-not-active>
````

## Git rm 
Git rm can be used to remove files from the index and the working directory. We use:

````
git rm <file-name>