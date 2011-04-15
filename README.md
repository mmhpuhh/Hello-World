Github Commands
===============

##Create folder, file, commit and push

mkdir [dir_name]
cd [dir_name]
git init
touch [file_name]
git add [file_name]
git commit -m '[message]'
git remote add origin git@github.com:[user]/[dir_name].git
git push -u origin master

##Commit and push local changes
git commit -a -m '[message]'
git push -u origin master

##Status (modifications, etc.)
git status
