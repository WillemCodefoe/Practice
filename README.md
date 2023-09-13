**Getting started with Git**
=====

_First step: u need to install git bash and create repo_

## useful command for gitbash:
```
git init #initialise your repo
cd /file_name/ # go to file_name
touch file_name # create file
mkdir dir_name # create directory
pwd # show you current dir  (?root?)

git add -all 
#or			to add changed files in your repo
git add .

git commit -m 'patch-note' # update your files
git status # check if everything is ok
```

_Second step: sign in GitHub.com_


_Third step: set up SSH or RSA key_


_Fourth step: connect your local repo to online one copy_

## you can do this by writing 
```
git remote add origin _link in your github copy_
git remote -v # here you check if you did everything right
```

_Fifth step: push your local files to GitHub:_
``` 
git push -u origin main # or master instead of main
# use this command only for the 1st time

git push # now you need to use only this command
git log # check if everything is ok
``` 

_6th step: create README.md file and edit it_
## write there everything that other people should know about your project
-----
**Actually that's it**