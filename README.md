# github
$ git init          //Initialize local Git Repository
$ git add <file>    //Add file to index
$ git status        //Check status of working tree
$ git commit        //Commit changes in index
$ git push          //Push to remote repository
$ git pull          //Pull latest from remote repository
$ git clone         //Clone repository into a new directory

Installing Git
Linux Debian
$ sudo apt-get install git

Linux Fedora
$ sudo yum install git

Mac
http://git-scm.com/download/mac

Windows
http://git-scm.com/download/win

$ git --version

$ touch index.html
$ touch app.js

$ git config --global user.name 'Tiago Ramos'
$ git config --global user.email 'tiagoramos2905@hotmail.com'
$ git add index.html
$ git status
$ git rm --cached index.html
$ git add *.html
$ git status
$ git rm --cached index.html
$ git add .
$ git status
$ git commit  
  Initial commit
</.git/COMMIT_EDITMSG[+] [unix] (15:40 08/05/2019)7,15 Tudo
:wq
$ git status
$ git add .
$ git commit -m 'change app.js'
$ touch .gitignore
$ touch log.txt
$ git add .
$ git status
$ git branch login
$ git status
$ git commit -m 'another change'
$ git ckeckout login
$ touch login.html
$ git add .
$ git commit -m 'login form'
$ git checkout master
$ git merge login
$ git remote
$ git remote add origin https://github.com/TiagoRamos1987/myapp.git
$ git remote
$ git push -u origin master
login...
$ touch README.md
$ git add .
$ git commit -m 'add readme'
$ git push
MyApp2
$ git clone https://github.com/TiagoRamos1987/myapp.git
$ git pull
-------------------------------------------------------------------------------
Quick setup — if you’ve done this kind of thing before
Set up in Desktop 
or 
HTTPS 
SSH 


Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore. 
…or create a new repository on the command line

echo "# laravel" >> README.md
git init
git add *
git add vendor/* -f
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/TiagoRamos1987/laravel.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin https://github.com/TiagoRamos1987/laravel.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
