\# Remote Repository Investigation



\## Git Fetch vs Git Pull



`git fetch` downloads the latest information from the remote repository without changing the current local branch.



`git pull` downloads the latest changes and integrates them into the current local branch.



\## origin/main vs main



`origin/main` is the remote-tracking branch representing the state of `main` on GitHub after fetching.



`main` is the local branch on my computer.



They can be different until changes are fetched, pulled, or pushed.



\## Commands Used



\- `git remote -v` - shows configured remote repositories.

\- `git branch -a` - shows local and remote branches.

\- `git fetch` - updates remote-tracking information.

\- `git status` - shows the current branch and working-tree status.

