# github
Notes about using github

## How to start
1. Create local folder for storing git repositories (repos), e.g. c:\git
2. Install Git for Windows
3. Create new subfolders under c:\git, each subfolder means separate repo, e.g. c:\git\project

## Initialize local repo
1. Open Git CMD and navigate to c:\git\project
2. "git init" - initializes the tracking on the current repo, now repo is ready for local work

## Add files to the repo
1. add/create new file to the repo
2. "git status" - displays current status (untracked files, or something to commit, etc.)
3. "git add <file or folder>" - adds new files to tracking
4. "git commit -m <message>" - commits the changes to the repo, -m means "message" - always required for commit
  
## Bind to github
1. Create new repo at github (via web portal https://github.com/yuriyrozhok)
2. "git remote add origin https://github.com/yuriyrozhok/project.git" - binds current local repo to github's repo

## Upload local changes to github
1. "git push -u origin master" - pushes commited changes from the local repo to github

## Download remote changes from github
1. "git pull origin master" - pulls commited changes from github to the local repo
