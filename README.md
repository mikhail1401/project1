# Git basics

## Recap of the previous class
- git init
- git status
- git add . 
- git commit 

- combining the commands >> git add. | git commit -m 'started project with readme'
  156  git show
  157  git checkout master
  158  git checkout master
  159  git branch mikhail1
  160  git branch mikhail2
  161  git branch mikhail3
  162  git branch
  163  # git branch name - create new branch without switching to it
  164  # git checkout -b name - creates new branch with switching to it
  165  # git branch - shows all the branches
  166  # git checkout name - switching to a different branch
  167  history | tail -10
  168  history | tail
  169  history 
  170  history | tail -15 >> README.md

1. basic
2. github exercises
# hello text
* some bullet points here
## hello
### hello
text body

## Take aways from git sessions
* local
- create a git repository: create a folder, initialize git (tracking)
''' git init
# add some files (text, python etc.) or update, add all file to tracking system (git)
git add.
git commit -m 'meaningdule message that summirezes your changes'
# if you want to publish: create repo in github, copy the url that ends with .git
get set-upstream origin url
git push 

# add files to '.gitignore' exclude from tracking and publishing to the cloud repository
cat >> .gitignore
data/
mynotes.txt

# publish ignoring mentoined files or directories
git push

* Branching
- git branch # list all existing branches
- git branch newbranch # create a new branch and not switching
- git checkout - b newbranch # creating and switching to new branch
- git checkout branch # switching to existing branch

* Working with github
- git clone url.git # clone brand new project from the cloud
- git push # publish the changes from your local to cloud
- git pull # get the updates from cloud repository

## Working with class file, get updates and make changes in your branch
1. clone the repository from asotools
'''
git clone <url>
cd newrepo
git checkout -b 'yourbranch'
'''
2. make changes in your repository, local changes.
3. Go to your github account, create a new repository to save YOUR changes
4. Get the URL of that repositry from GitHub
5. Set the your branch upstream to your GitHub repository that you just created.
'''
git push --set-upstream <url from your github repository>
'''
6. To get the updated from asotoolsny repository, switch to master branch and then git push
'''
git checkout master
git pull
'''
7. To get new changes from updated master to your branch:
'''
git rebase master
'''
  testing pull command
