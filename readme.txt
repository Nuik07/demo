Just for use of git bash
Learning

" fhdsjf"  -> doesntt need to use string sign just to make obvious 

commands:
----------------------------
user-setup:
---------------

git config --global user.name "name" (add)
git config --global user.email "email"

git config --global user.name 
git config --global user.email (check) 

git init (master)

git status
git log 
git log -p
git log -2

git add "filename.ext" (put to stage)
git add -A (put to stage--all)

git commit -m "comment" (single line commit)
gt commit (detailed)

git checkout  (check all)
git checkout -f (all restore)
git checkout "filename.ext" (restore specific)


touch "filename.ext" (create)
git rm "filename.ext" (delete)

git diff (to see uncommited changes)
git reset --hard (reset to last commited changes)


git branch -M main (initial branch on main)
git push -u origin main (initial push)
git push(to push on main branch --> github/...)


igonere files:
-----------------------

tocuh .gitignore
-->> add the files name on gitignore (to ignore updating those )

<<<<<<< HEAD
=======
Branch:
----------------------

git branch (check)
git checkout -b 'main' (create branch and switch to it)
git checkout 'name'

now for local new branch, we have to create new branch on github:
------------------------------------------------------------------

git push --set-upstream origin 'name'



merge (commiting sub branch to main) : (have to from that branch)
---------------------------------------

git merge "name" (name of the branch where it will be pushed to main)
--------------------------------------------------------------------------
first -->>> add-> commit-> push sub branch
	    >>> git merge "name of the branch where it will pushed"
	    >>> push branch
second-->>> switch to master
third -->>> push to update 


>>>>>>> sub_01
Command line :
---------------------------------

cd .. (previous directory)
cd /c/..

mkdir "name" (make directory)
ls (folder details)
ls -l (detailed details)
clear