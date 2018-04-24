## Markdown Cheatsheet
[tips] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


## Basic steps to create and update a Git workflow in Python


**Starting a new project**
1. Create project directory on local machine
2. In terminal, navigate to newly created directory
3. Create a new git repo: `git init` 
4. Add a readme.md file that states what the project is all about: `touch readme.md`
5. Add a .gitignore file: `touch .gitignore`
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
2. Create a new branche for this specific document `git checkout -b hello_world.py` (-b for branch)
3. Modify your new branch document
4.  Add it `git add.` ( adding a point meaning everything there is updated)
5. Commit  `git commit -m " adding this modified document to the new branch and not merging it to the master just so everyone in the team can see and agree on it"`
6. pushing the modified document to the branch `git push origin hello_world.py`

