# What have I done:


### 1. Prepared workspace 

1.1 Launched MINGW32
1.2. Changed directory to disc C
`cd c`
1.3. Created project folder
`mkdir projects`
1.4. Moved to projects folder
`cd projects`
1.5. Created folder for the project, named articles
`mkdir articles`
1.6. Moved into it
`cd articles`
1.7. Created readme file
`touch readme.md`
1.8. Created file for the first article
`touch Article#1.md`
1.9. Initialized Git in project folder
`git init`
1.10 Opened readme file and pasted all this text into it
`vim readme.md` for opening file, `p` for pasting from clipboard, `:wq` for write (saving changes) and quit

### 2. Worked with article #1

2.1. Added both files to the index:
`git add .`
2.2. Created first commit
`git commit -m "Created project. Described section 1 (preparing workspace) in readme.md"`
2.3. Added article's content
`vim Article#1.md` for opening file, `p` for pasting from clipboard, `:wq` for write (saving changes) and quit
2.4. Checked git status for modified file and commited it
`git status` for checking modified Article#1.md file, `git add .` for adding files for next commit and `git commit -m "Added article #1 with users comments"`
2.5. Created new branch for editing Article #1 (checking and fixing errors in it).
`git branch article1/checkerrors` for creating a new branch, `git checkout article1/checkerrors` to move to created branch
2.6. After fixing errors in Article 1 commited changes in new branch
`git add "Article#1.md"`, `git commit -m "Fixed typos and errors in Article#1"`
2.7. Merged `article1/checkerrors` branch with master one
`git checkout master` to switch to master branch, `git merge article1/checkerrors` to merge recently created branch with own changes with master branch
2.8. Added own comment to the article
`git branch article1/addowncomment` to create new branch, `git add .` to add edited article file for next commit, `git commit -m "Added own comment for Article #1"` to commit changes, `git checkout master` and `git merge article1/addowncomment` to merge these two branches.

### 3. Worked with article #2.

3.1. Created new article
`git branch article2/createraw`, `git checkout article2/createraw`, `git add Article#2.md`, `git commit -m "Created Article #2"` `git checkout master`, `git merge article2/createraw`
3.2. Added markup to the article
`git branch article2/addmarkup`, `git checkout article2/addmarkup`, `git add Article#2.md`, `git commit -m "Added markdown markup to Article #2 :D"` `git checkout master`, `git merge article2/addmarkup`
3.3. Added own comment
`git branch article2/owncomment`, `git checkout article2/owncomment`, `git add Article#2.md`, `git commit -m "Added own comment to Article #2"` `git checkout master`, `git merge article2/owncomment`
3.4. Edited own comment
`git branch article2/editowncomment`, `git checkout article2/editowncomment`, `git add Article#2.md`, `git commit -m "Added sincere post scriptum to own comment to Article #2"` `git checkout master`, `git merge article2/editowncomment`

### 4. Pushed project on GitHub

4.1. Set remote repository URL
`git remote add origin https://github.com/laFreeFall/Articles-and-thoughts.git`
4.2. Pushed local branch and set remote as upstream
`git push --set-upstream origin master`

