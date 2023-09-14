# **Getting started with Git**
-----
# ** Part 1: GIT Set-up**


# •First step: u need to install git bash and create repo

## _useful command for gitbash_:
```
git init 	#initialise your repo
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

# •Second step: sign in GitHub.com


# •Third step: set up SSH or RSA key


# •Fourth step: connect your local repo to online one copy

## _you can do this by writing_ 
```
git remote add origin _link in your github copy_
git remote -v # here you check if you did everything right
```

# •Fifth step: push your local files to GitHub:
``` 
git push -u origin main # or master instead of main
# use this command only for the 1st time

git push # now you need to use only this command
git log  # check if everything is ok
git log --oneline
``` 

# •6th step: create README.md file and edit it
## _write there everything that other people should know about your project_
-----

# **Part 2: main info**

## _1. HASH - special number for every commit_

## _2. git log - can show information about commits_

## _3. HEAD - file on your computer that contains link to latest commit' HASH_

## _4. git status - (staged, unstaged , tracked, untracked, modified)_

## _5. commit messages (CM)- CM's should be informative and short. There are some rules for it, like:_
---
GitHub rule: mention #problem_number in your CM
Jira: corporate rule with identificators
[Convevntional commiting](https://www.conventionalcommits.org/ru/v1.0.0-beta.4/#%D1%81%D0%BF%D0%B5%D1%86%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F)
---
## _