#Git Quick Start
$mkdir tossbrinkatgit //create local folder
$cd tossbrinkatgit //change directory
$fn init --runtime java
$git init //initalize git repository .git
$git config user.email 'myemail@email.com'
$git config user.name 'myname'
$git add . //add all files to staging area
$git status //status of file
$git rm --cached *.* //remove the file
$git commit -m 'Initial commit' //commit with all files
$touch error.log
$touch .gitignore //gitignore and add entry error.log or addd the /directory
$git add .
$git commit -m 'Another commit' //commit with all files
$git status //on branch master

#branch
$git branch feature
$git checkout feature
$git status
#add some files
$git add .
$git commit -m 'commit at branch' //commit with all files
$git status
$git checkout master
$git merge feature

#create newrepo at github
$git remote
$git remote remove orgin
$git remote add origin https://github.com/tossbrink/tossbrinkatgit.git
$git remote
$git branch -M main
$git push -u origin main

#create readme.md and push
$touch README.md