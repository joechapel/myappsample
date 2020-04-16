#MyApp
This is MyApp learning git

#explanation
git init       // initialize local git repository
git add <file> // add file(s) to index
git status     // check status of working tree
git commit     // commit changes in index
git push       // push to remote repository
git pull       // pull latest from remote repository
git clone      // clone repository into a new directory

#download
linux  
sudo apt-get install git
sudo yum install git
http://git-scm.com/download/
http://git-scm.com/download/win
http://git-scm.com/download/mac

#installation
next next next
adjusting your path environment
use git and optional unix tools from windows command prompt (as find, sort...)
git --version

#local
at specific folder at gitcmd
git init
touch files
work with Atom (notepad editor for several languages)
git config --global user.name 'your name'
git config --global user.email 'your@email.com'
(git add file)
git add index.html /or
git add * .html (without spaces)   /or
git add .
git status

to remove cache
git rm --cached index.html
git status

touch .gitignore (add files don't want to add to repo or directories)
git add .
git status
git commit (open notepad or vi change #initial commit to initial commit)
or
git commit -m 'info regarding changes'

git branch login
git add .
git commit -m 'another change'
git checkout login

touch other file
git add .
git commit -m 'login form'
git checkout master

change some files
git merge login (merge versions from login to master)


#push to git repo
access to github
add repository
add name
add description - public
create repository

git remote
git remote add origin https://github.com/joechapel/myappsample.git
git add .
git commit -m 'something'
git push -u origin master

touch README.md
edit README
git add .
git commit -m 'added readme'
git push

refresh at github repo



to clone the repo
go to specific folder at your operating system
git clone https://github.com/joechapel/myappsample.git


if the app is work by a team and other change the repo
at your environment you need to put
git pull
