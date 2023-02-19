# GIT BASICS - detials for loacl repo
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
- `git restore`: to restore or undo changes.
# GIT REMOTES
- `git remote add`: to add remote to the git repository.
- `git push <where> <what>`: to sync local changes to remote.
        - `<where>`: is the remote.
		-`<what>`: the local branch name.
- Adding Remote Commit 1
- Adding Remote Commit 2
