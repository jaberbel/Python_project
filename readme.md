## Markdown Cheatsheet
[tips] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Starting with git
1. Install git  [ git] (https://git-scm.com/downloads)

2. Go to your terminal ( cmd if you are on windows)
3. To check if it git is well installed type `git -- version`
4. Include your name and email:

 `git config --global user.name 'Jaberbel' `

 `git config --global user.email 'Jaber.@yabadabadab.com' `

 `git config --list `


## Basic steps to create and update a Git workflow in Python [video here] (https://www.youtube.com/watch?v=HVsySz-h9r4)


**Starting a new project**
1. Create project directory on local machine
2. In terminal, navigate to newly created directory
3. Create a new git repo: `git init` 
4. Add a readme.md file that states what the project is all about: `touch readme.md`
5. Add a .gitignore file: `touch .gitignore` ( this is a file were we tell git to ignore these files from being upladed )
6. Add files to staging: `git add -A` (taking a snapshot) ( -A for all, this could be replaced by a specific file example : **Readme.md**)
7. Add files (snapshot) to local repo: `git commit -m "commit message"`

8. Go to Github and add a new repository
9. After you create repo, copy the "remote add" line, then paste back within your project directory in your terminal
10. Now push your local repo to Github: `git push origin master`

**Updating an existing project**
1. After you make your updates, add files to staging `git add -A`(taking a snapshot)
2. Add files (snapshot) to local repo: `git commit -m "commit message"` (-m for message)
3. Now push your local repo to Github: `git push origin master`

## Working as a group on a project

1. Pulling the master: the last updated document after merging all branches `git pull origin master`
2. Create a new branch (called hello_world.py) for this specific document `git checkout -b hello_world.py` (-b for branch) 
You can see now if you type `git status` that we are on that branch.

3. Modify your new branch document
4.  Add it `git add .` ( adding a point meaning everything there is updated)
5. Commit  `git commit -m " adding this modified document to the new branch and not merging it to the master just so everyone in the team can see and agree on it"`
6. pushing the modified document to the branch `git push origin hello_world.py`


## Resolving conflicts
1. always a good idea to start with `git status`
