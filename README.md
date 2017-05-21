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