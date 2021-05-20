# _git branch_

- lists local branches, and marks the current branch

# _git status_

- shows local, uncommitted changes

# _git add_

1. `git add .` - stages all local changes 

# _git commit_

1. `git commit -m "your message here"` - commits all staged changes with the message  

# _git push_

1. `git push` - pushes all changes in current local branch to the remote branch with the same name
2. `git push ＜remote-name＞ ＜remote-branch-name＞` - same as above except it pushes to specified remote and branch name, ex. **_git push origin dev_**  

# _git checkout_
1. `git checkout ＜existing-branch＞` - switches to existing local branch with name _＜existing-branch＞_
  
2. `git checkout -b ＜new-branch＞` - creates new branch baseed off of current HEAD and switches to it immediatelly 
3. `git checkout -b ＜new-branch＞ ＜existing-branch＞` - creates new branch based off of existing-branch and switches to it immediatelly 
