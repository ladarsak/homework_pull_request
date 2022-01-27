# Git Commands
## Start with git
    > git help
        * use to study you dumbass
    > git config --global user.name "name"
        * username
    > git config --global user.emale "name@email.com"
        * user e-mail
    > git init
        * repository initialisation
## Adding files to git
    > git add .
        * add all files for tracking
    > git add filename
        * add one file
    > git commit -m "message"
        * make the commit at last!
## Hey Repo, how do you do?
    > git status
        * what's tracking
    > git log
        * what's commited
    > git diff
        * what's the difference between the file's versions

## Intercommits travels
    > git checkout commit_code
        * makes the choosen commit the last one
    > git checkout master
        * returns the "main" status to the *real* last one

## Add some pics
![not found](20170626.jpg)

## Branches in Git
* to see all branches:
    > git branch
* to make branch:
    > git branch_name
* to transfere between them:
    > git checkout branch_name
* to delete:
    > git branch -d branch_name
* automatically add to commit without an "add" command
    > git commit -a -m "[message]" 
## More about deleting
* to delete a branch despite any objections:
    > git branch -D branch_name            

## Merge and Conflicts
* to add information into current branch from a branch_name:
    > git merge branch_name
* To resolve a merge conflict redundant strings should be removed and text corrected manually (e.g. just delete <<<HEAD)

## Help
* to receive info about command:
    > git command_name --help
    
## First time at GH
**Make difference between local and remote commits:**

main (green) is local;

origin/main (red) is a remote one.

If you made changes in the 2nd local clone, make sure you had pulled them to the 1st one before you start to work with it

* To check if you are connected to a remote repo:

    > git remote

* To receive remote version:
    > git pull

* To send your local changes to a remote repo:
    > git push

* To connect to a remore repo:
    >git remote add origin repo_link_here

* To push to a remote repo where there is no the same branch as that you are pushing from:
    > git push --set-upstream origin branch_name_here
    