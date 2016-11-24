Please read this!!
GIt hub REPO
https://github.com/prinzz06/git-tuts.git

Git Config Initial setup
git config --global user.name "Prince Escueta"
git config --global user.email prinzz06@gmail.com


Add file
Add to stage
Commit Changesasdfas

Modify
Add to staging area
Commit changes

Testing git dif in the middle


git add "filename"
git commit -m "Comment on the commited file"

other commands for adding
git add list of files  //add the list of files
git add --all		// add all files
git add *.txt		// add all txt files in current directory
git add docs/*.txt 	// add all txt files in docs directory
git add docs/		// add all files in docs directory
git add "*.txt"		//add all txt files in the whole project

git diff
lets you see what was added in the file if it has been modified
Green is the newly added line

git diff --staged
gets the difference of staged and previous commit

unstage
git reset HEAD filename

git checkout -- Filename
this will check out the previous commit

git commit -a -m "Shortcut in commiting"
This will add it to stage and commit it with comment
untracked files(New Files) will not be included in the commit

git reset --soft HEAD^ undo last commit and put it back to staging

forgot to add file to commit?
you can add it to your previous commit and ammend it
First Stage it
git add filename
git commit --amend -m "Adding more file to last commit"

git reset --hard HEAD^ undo last commit and all changes
git reset --hard HEAD^^ undo last 2 commits and all changes

Added Github repo
git remote add origin https://github.com/prinzz06/git-tuts.git

git remote -v

git push -u origin master
will ask for username and password

Password Caching
https://help.github.com/articles/set-up-git

git pull
pulls it from github

multiple remotes
add remote
git remote add <name> <address>

remove remote
git remote rm <name>

push remote
git push -u <name> <branch>
-u remembers the name and the branch
so next time you can just run git push

HEROKU another platform where you can create an account and use git
Check last part of level 2


git clone <url> <name>
or you can ommit the name and it will default to the name

create a branch for a new feature
git branch <name>

to move to a branch or timeline
git checkout <name>

to merge 2 branch or timelines
got to the master time line
git merge <branch name>

to delete a branch
git branch -d <branch name>

shortcut for adding and checkingout branch
git checkout -b <branch name>

conflict

JUST FINISHED GIT BRANCHES
DOING PUSH AND PULL TO GITHUB

Problem in merged when deleted file after merging crashed

https://github.com/prinzz06/git-tuts.git