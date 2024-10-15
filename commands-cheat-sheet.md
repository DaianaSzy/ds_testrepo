# Terminal command cheat sheet

## General commands:

* `pwd` to check where you currently
* `ls` list all files on your machine
* `cd <name>` change directory
* `cd ..` change back to parent directory
* `mkdir <name>` create directory
* `:wq` save and exit a program

## Git
**Clone**
* `git clone <ssh link>` to clone a repo

**Pull**
* `git pull` to update your branch

**Status**
* `git status` to see what all changed

**Commit & Push**
* `git add <file name>` add changes to commit
* `git commit -m "message you want to write with your commit"` commit changes to the active branch
* `git push` upload changes to github

**Fetch**
* `git remote add upstream <ssh connection>` fetch original repo
* `git remote -v` to check if the fetch is correct
* `git fetch upstream`
* `git merge upstream/main` merge original repo with your local repo