---
permalink: /example-repo/
title: Version control and git basics task
---
## This project is the version control and git basics task from Hyperion Dev.
* **It contains a hello_world.js program**
* **It contains a screenshot of some commands that have been run in the terminal**
  
The hello_world.js program is a very short program designed to show the words "hello world" when it is run.
The commands in the screenshot are as follows:
* git init to initialise a new repository
* git status to show that there is a clean working directory
* a code file with hello_world.js
* git status command showing that hello_world.js is untracked
* git add command followed by hello_world.js to start tracking the new file
* a git status command to show the hello_world.js is tracked and staged to be commited
* a change to the hello_world.js file to print the message "Git is awesome!"
* a re-run of the git status showing that hello_world is in a section "changes not staged for commit" (meaning the file is tracked but has been modified and not staged)
* re-run if git add
* re-run of git status showing that the file is now staged for the next commit
* running the git commit -m command and a message after the -m switch
* running git status showing a clean working directory
* running git log seeing the commit listed
