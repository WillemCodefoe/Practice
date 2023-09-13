**Getting started with Git**
=====

First step: u need to install git bash and create repo

## useful command for gitbash:
```
git init #initialise your repo
cd /file_name/  # go to file_name
touch file_name # create file
mkdir dir_name  # create directory
pwd             # show you current dir  (?root?)

git add -all 
#or	          to add changed files in your repo
git add .

git commit -m 'patch-note' # update your files
git status     		   # check if everything is ok
```

Second step: sign in GitHub.com


Third step: set up SSH or RSA key


Fourth step: connect your local repo to online one copy

## you can do this by writing 
```
git remote add origin _link in your github copy_
git remote -v # here you check if you did everything right
```

Fifth step: push your local files to GitHub:
``` 
git push -u origin main # or master instead of main
# use this command only for the 1st time

git push # now you need to use only this command
git log  # check if everything is ok
``` 

6th step: create README.md file and edit it
## write there everything that other people should know about your project
-----

**Actually that's it**