- `git init` : initialize the current folder to Git Repository.
- `git clone <URL>` : brings in the remote Git repo from <URL> the current folder.
- `git status`: tells us the state of the repository
- `git add <file_name>`: adds file to the staging area
- `git commit <file_name>`: commit the staged file.
       `git commit -m <commit_msg> <file_name>`: commit the staged file with commit message.
- `git log`: to view at the history of the repository.
      `git log --oneline`: to view short history in one line.
- `git diff HEAD~<commit#hash>`: to view the difference between two commits.
- `git commit --amend`: to amend the previous commit (It just replaces the previous commit with new commit with changes)
      - if no changes are made, then the commit message is changed