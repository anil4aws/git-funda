# learn git

## some text git showed when I created new repo

## After installation of Git

git init 
## this will make the initialize reinitialize folder by adding .git 
## check further in Git/mingw64/share/doc/git-doc/git-init.html 

git add README.md

git commit -m "first commit"
## this will say 
## PS D:\workspace\kafka-for-learners> git commit -m "edited readm commit"
##Author identity unknown

##*** Please tell me who you are.

##Run

  ##git config --global user.email "you@example.com"
  ##git config --global user.name "Your Name"

##to set your account's default identity.
##Omit --global to set the identity only in this repository.

git config --global user.email "Anil Karnam"
git config --global user.name "Anil"

git commit -m "first commit"


git branch -M main

git remote add origin https://github.com/anil4aws/git-funda.git

git push -u origin main


## …or push an existing repository from the command line
git remote add origin https://github.com/anil4aws/git-funda.git
git branch -M main
git push -u origin main

## …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
