Learning Git
===

This repo is used to explore 'new'(at least for me) git features.


## Shell primer

```bash
$ # how to move faster in bash
Moving:
$ # ctrl + <left arraw>/<right arraw> moving one word at a time
$ # ctrl + a/e move to the begining/end of the current line

Clearing:
$ # ctrl + u clear up to the beginning of the line
$ # ctrl + c cancel current line
$ # ctrl + l clear screen
$ # ctrl + w/k remove characters on the left/right
$ # ctrl + y recall deleted command

Searching:
$ # ctrl + r search for a recently typed command
$ # ctrl + g cancel searching
```

## zsh Setup
```bash
$ # install autojump a.k.a. j <term>
$ # install oh-my-zsh and choose theme miloshadzic
```

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
$ git commit -m"initial commit" # if -m is ommited, default text editor will be open for entering message
# push to remote, and setup upstream
$ git push -u origin master # -u stand for upstream, first time only
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
