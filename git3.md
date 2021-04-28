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

to see a list of all conflicts present use:

git diff

- ###  git tag  marks specific commits. Developers use it to mark release points like v1.0 and v2.0.

git tag 1.1.0 <instert-commitID-here>

- ### git log   is used to view the history of the repository listing certain details of the commit. When executing the command you get an output like this:

commit 15f4b6c44b3c8344caasdac9e4be13246e21sadw
Author: Jorge Chan <2009035 @ upy, edu.mx>
Date: Mon Oct 1 12:56:29 2016 -0600

- ### git reset  is used to reset the index and the working directory to the last commit state.

git reset - -hard HEAD

- ### git rm  can be used to remove files from the index and working directory.

git rm homework.txt

### git stash  will momentarily save changes that are not ready to commit. This way, you can come back to the project later.

git stash

###  git show  is used to show information about any git object.

git show

### git fetch  allows the user to search for all objects in a remote repository that are not currently in the local working directory.

git fetch origin

- *

### git cat-file ** is used to view the type and size information of a repository object. Use the -p option in conjunction with the object's SHA-1 value to view information for a specific object, for example:

git cat-file –p d670460b4b4aece5915caf5c68d12f560a9fe3e4


### git grep  allows the user to search for specific words and phrases in the commit trees, working directory, and staging area. To search for www.hostinger.com in all files, use:

git grep "www.hostinger.com"

### gitk  shows the graphical interface for a local repository. Just run:

gitk

- ###  git instaweb ** allows you to browse your local repository in the GitWeb interface. For example:

git instaweb –http = webrick

- ### git gc ** will clean up unnecessary files and optimize the local repository.

git gc

- ###  git archive  allows the user to create zip or tar archives containing the constituents of a single repository tree. For example:

git archive - -format = tar master

-

- ### git rebase  is used to apply certain changes from one branch to another. For example:

git rebase master
