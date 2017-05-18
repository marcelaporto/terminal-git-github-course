# <dev/Mission>
## Git & Terminal Solution
*Instructor(s): Marcela, Yaritza | Expected Length: 1 Session*

## Show everyone who's boss
Do you have git? `git`

Setting you name in Git: `git config --global user.name "USERNAME"`

Setting you email: `git config --global user.email "email@example.com"`

## Navigate inside your computer

To see your path:`pwd`

To understand where to navigate to: `ls`

To navigate: `cd ~/Desktop`


## Create NASA HQ - San Francisco

`mkdir NASA-HQ`

## Create the Astronauts and Equipments Section in NASA HQ

`cd NASA-HQ`

`mkdir Astronauts`

`mkdir Equipments`


### Add the Astronauts

`cd Astronauts`

`touch sally.txt`

`touch bobby.txt`

`touch phillip.txt`

## Keep a log of what is happening

Make sure no one else is doing the log already: `ls -a`

Start: `git init`

### Add existing things to Git

`git status`

`git add <filename>`

`git commit -m "MESSAGE"`

`git status`

## Add favorite color in astronauts files

`open <nameoffile>`

do the changes

`git status`

`git add <filename>`

`git commit -m "MESSAGE"`

`git status`

## Add Cali branch

`git checkout -b california-features`

`cd Equipments`

`touch yoga-mats.txt`

`touch space-kale.txt`

`touch coffee-shop.txt`


`git status`

`git add <filename>`

`git commit -m "MESSAGE"`

`git status`


`git checkout master`

`git merge california-features`


## Connect to outerspace station

`cd ..`

`git clone https://github.com/marcelaporto/terminal-git-github-course/space-station`

`pwd`

`cd ..`

`cd space-station`

`git checkout -b sf-astronauts`

`pwd`

`mv ../NASA-HQ/Astronauts/sally.txt ./astronauts`

`mv ../NASA-HQ/Astronauts/bobby.txt ./astronauts`


`git status`

`git add <filename>`

`git commit -m "MESSAGE"`

`git status`


`git push origin sf-astronauts`


create pull request

## Send NASA HQ info to your Github Account

create empty repo in Github, get URL

`pwd`

`cd ..`

`cd NASA-HQ`

`git status`

`git remote add origin github.com/<username>/NASA-HQ.git`

`git push -u origin master`


## Last thing: Fork this repo so you have the info we talked about at your fingertips!

https://github.com/marcelaporto/terminal-git-github-course
