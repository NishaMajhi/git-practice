# Git Commands

- For Initialing an empty git folder
    - git init 
- For Adding files for staging
    - git add <file_path> -> for single file
    - git add . -> for adding all files
- For commiting staging area code 
    - git commit -m " "
- For showing log history
    - git log -> give litle bit more details info about log
    - git log --oneline -> give log data in one line shorter manner
- For showing details of specific commit
    - git show <SHA(commit_id)>
- For watching difference between current saved code and previous code
    - git diff
- For Reverting/Reseting 
    - git reset --hard <SHA(commit_id)>
    - git revert <SHA(commit_id)>