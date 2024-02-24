# Git Commands
- git init

- git add <file_path>
- git add .

- git rm <file_path>

- git commit -m " "
- git commit -a -m ""

- git log
- git log --oneline

- git reset --hard <commit_id>
- git revert <commit_id>

- git pull
- git push
- git push -u origin main
- git push --set/upstream origin <branch_name>

- git remote add origin <origin_path>
- git branch -M main

- git branch
- git branch <branch_name>
- git checkout <branch_name>
- git checkout -b <branch_name>

- git merge <branch_name>
- git rebase <branch_name>

- git stash
- git stash apply

- git status
- git diff
- git blame <file_path>
- git show <commit_id>

# Git cheat sheet link [here](https://education.github.com/git-cheat-sheet-education.pdf)


# Version Controlling with Git

## Initializing Git Project
- git init 


## Adding Files to VCS
- git add <file_path> =>  for single file
- git add . => for adding all files

## Removing Files from VCS
- git rm <file_path>


## Commiting Files
- git commit -m " "
- git commit -a -m ""


## Logging Commit History
- git log => give litle bit more details info about log
- git log --oneline =>  give log data in one line shorter manner


## Reverting Back
- git reset --hard <SHA(commit_id)> => it will remove all the below commit from history and HEAD will pointing to this <commit_id>
- git revert <SHA(commit_id)> => it will write reverse code and when we stage it and commit it , it will create a new commit with the reverted code


## Git Remotes
- git remote add origin <origin_path>
- git branch -M main


## Pulling and Pushing 
- git pull
- git push
- git push -u origin main => for pushing code in origin server (only first time)
- git push --set/upstream origin <branch_name> (only first time)


## Branching in Git
- Creating Branches
    - git branch <branch_name>
    - git checkout -b <branch_name>
- See All Branches
    - git branch
- Switching Branches
    - git checkout <branch_name>
- Merging Branches
    - Merge
        - git merge <branch_name>
    - Rebase
        - git rebase <branch_name>


## Branch Tags
- group/name
    - e.g: 
        - feat/feat-a
        - bug/bug-a
        - wip/dashboard


## Stashing
- git stash
- git stash apply


## Other
- For Showing Details of Specific Commit
    - git show <SHA(commit_id)>
- For Showing who did Changes in Specific File 
    - git blame <file_path>
- For Watching Difference between Current Saved Code and Previous Code
    - git diff
- To see status of code means how many files are changed
    - git status
 


