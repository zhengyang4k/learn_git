Learning Git
===

This repo is used to explore 'new'(at least for me) git features.


## Create a git repo

```bash
$ git init
$ git remote add origin git@github.com:zhengyang4k/learn_git.git
$ vi README.md
$ git add README.md
$ git commit -m"initial commit"
$ git push -u origin master # -u stand for upstream
```

## Basic commands
```bash
# checking status of current branch
$ git status
$ git add README.md
$ git commit -m"message"
$ git push
# add and commit together
$ git commit -am"message"
```
