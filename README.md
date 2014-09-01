Learning Git
===

This repo is used to explore 'new'(at least for me) git features.


## Create a git repo

```bash
# init current directory to be a git repository
$ git init
# add remote tracking
$ git remote add origin git@github.com:zhengyang4k/learn_git.git
# create a new file and add to staging area
$ vi README.md
$ git add README.md
# commit to master (default), this will create master branch
$ git commit -m"initial commit"
# push to remote, and setup upstream
$ git push -u origin master # first time only
```

## Basic commands
```bash
$ git add README.md
$ git commit -m"message"
$ git push
# add and commit together
$ git commit -am"message"
```
