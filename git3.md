# Git & github markdown



## Corrretion of the format


### git init  starts a repository

git init homework.md

- ### git clone  is used to copy a repository. If the repository is on a remote server, use:

git clone https://github.com/JorgeMauricioChan1/Git-data

git clone / path / to / repository

- ### git add  is used to add files to the staging area.

git add hw.md

- ### git commit  will create a snapshot of the changes and save it to the git directory.
git commit –m "Firts save, Hello Prof Juan"


- ### git config  can be used to set user-specific configuration, such as email, username and format type, etc. For example, the following command is used to set an email:

git config --global Mauricio.2009035@upy.edu.mx.

- ### git status  shows the list of files that have been changed along with files that are about to be prepared or committed.

git status
### git branch master
Changes not staged for commit:
#####  (use "git add <file> ..." to update what will be committed)
####  (use "git restore <file> ..." to discard changes in working directory)
        modified: git.md

Untracked files:
  (use "git add <file> ..." to include in what will be committed)
        _comands.md
        BASIC
        git

no changes added to commit (use "git add" and / or "git commit -a")

### git push ** is used to push local commits to the master branch of the remote repository. Here is the basic structure of the code:

git push origin <master>

- Replace <master> with the branch you want to send changes to when you don't want to send them to the master branch.
- Example: <Mau>
    
- ** git checkout ** creates branches and helps you navigate between them.
command git checkout -b <mau>

- To switch from one branch to another, just use:

git checkout <Master>

### git remote ** allows you to see all remote repositories.

git remote add origin

- On the other hand, the following command will delete a connection to a specified remote repository:

git remote <repository-name>
Example: git remote <Git-data>

### git branch  is used to list, create or delete branches. For example, if you want to list all the branches present in the repository, the command should look like this:

git branch

- If you want to delete a branch, use:

 git branch -d <branch-name>
 Example: Git <branch-Git.data>
 

- ###  git pull merges all changes that have been made in the local repository with the local working directory.

git pull

- ** git merge ** is used to merge a branch with another active branch:

git merge <mau>

- ** git diff ** is used to make a list of conflicts. In order to see conflicts regarding the base file, use:

git diff --base <homework.md>

- The following command is used to see the conflicts between branches before merging them:
git diff <source-branch> <target-branch>

