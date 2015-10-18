Please read this!!

Git Config Initial setup
git config --global user.name "Prince Escueta"
git config --global user.email prinzz06@gmail.com


Add file 
Add to stage
Commit Changes

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