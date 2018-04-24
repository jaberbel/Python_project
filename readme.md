Basic steps to create and update a Git workflow in Python


**Starting a new project**
1. Create project directory on local machine
2. In terminal, navigate to newly created directory
3. Create a new git repo: `git init` 
4. Add a readme.md file that states what the project is all about: `touch readme.md`
5. Add a .gitignore file: `touch .gitignore`
6. Add files to staging: `git add -A` (taking a snapshot)
7. Add files (snapshot) to local repo: `git commit -m "commit message"`

8. Go to Github and add a new repository
9. After you create repo, copy the "remote add" line, then paste back within your project directory in your terminal
10. Now push your local repo to Github: `git push origin master`

**Updating an existing project**
1. After you make your updates, add files to staging `git add -A`(taking a snapshot)
2. Add files (snapshot) to local repo: `git commit -m "commit message"`
3. Now push your local repo to Github: `git push origin master`

## Markdown tips
[tips] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)