# git basics

## recap of the previous class
_ git init
_ git status
_ git add .
_ git commit
,,,
- combining the commands  >>git add . | git commit -m 'comment'
-git show - displays the commits (logs)
  125  git status
  126  git commit -am |'updated readme file with new commands'
  127  git showgit
  128  git log
  129  git branch
  130  clear
  131  git checkout -b iroda1
  132  git checkout -b iroda2
  133  history | tail 
  134  history | tail >> README.md
# This is my changes in README
## 01/26/2020
## Take aways from git sessions
* local
-create a git repository: creare a folder. initialize git (tracking)
''' git init
# add some files (text, python etc) or update, add al file to tracking system (git)
git add .
git commit -m  'meaningful message that summurizes your changes'
# if you want to publish : create repo in github, copy the url that ends with .git  
git set-upstream origin url
git push
# add files to '.gitignore' there is . because there is hidden file.
if you dont want include some files to track or publish  use
git ignore
cat >> .gitignore


