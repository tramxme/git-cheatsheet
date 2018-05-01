# git-cheatsheet
git init                         : Initialize a Git repo here
git status                       : Check the current status of our project
git add <filename>               : Add <filename> to the staging area
git add .                        : Add all untracked files to the staging area
git commit -m "Message"          : Store staged changes with a message
git log                          : See all the changes we've committed so far
git remote add <remoteRepoName> <RepoURL>  : Add a remote repo
Ex: git remote add origin https://abc.com  - remote name is "origin" and remote URL is "https://abc.com"
git push -u <remoteRepoName> <localBranchName>: Push local changes to remote repo
Ex: git push -u origin master - -u tells Git to remember the params so next time, we can simply run "git push", "origin" is the name of the remote repo, "master" is the default local branch name
git pull <remoteRepoName> <branchName>   : Pull down any new changes
Ex: git pull origin master
