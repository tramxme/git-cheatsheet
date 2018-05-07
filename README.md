# git-cheatsheet
- **git init**                         : Initialize a Git repo here
- **git status**                       : Check the current status of our project
- git add <filename>               : Add <filename> to the staging area
- git add .                        : Add all untracked files to the staging area
- git commit -m "Message"          : Store staged changes with a message
- **git commit -a -m "Message"** : Add changes from all "tracked" files and commit (Doesn't add new untracked files)
- **git commit --amend -m "newMessage"** : Add to the last commit all staged changes and create new commit message (Don't do after push)
- **git log**                          : See all the changes we've committed so far
- git remote add <remoteRepoName> <RepoURL>  : Add a remote repo
Ex: git remote add origin https://abc.com  - remote name is "origin" and remote URL is "https://abc.com"
- **git remote rm <name>** : Remove remotes
- **git remote -v** : Show remote repoes  == **git remote --verbose**
- git push -u <remoteRepoName> <localBranchName>: Push local changes to remote repo 
Ex: git push -u origin master - -u tells Git to remember the params so next time, we can simply run "git push", "origin" is the name of the remote repo, "master" is the default local branch name
- **git pull** : Pull all changes from remote
- git pull <remoteRepoName> <branchName>   : Pull down any new changes
Ex: git pull origin master
- **git help** 
- **git help <command>** : Get description on <command> 
- **git config** : Set up git
Ex: git config --global user.name "abc" 
- **git diff** : Show unstaged differences since last commit
- **git diff --staged** : View staged differences
- **git reset HEAD <fileName>** 
- **git reset --soft HEAD^**: Undo last commit and put changes into staging (Now you can make changes and re-commit) (Don't do after push)
- **git reset --hard HEAD^**: Undo last commit and delete all changes (Don't do after push)
- **git reset --hard HEAD^^**: Undo last 2 commits and all changes (Don't do after push)
- **git checkout -- <fileName>** : Delete all changes since <fileName>
  
  
 
