# Git Cheatsheet

# Start a new project

```shell
$ mkdir project_name
$ git init
$ touch readme.md
$ git add readme.me
$ git commit -m"initial commit"
```
### Do some work and then save it

First do some work

```Shell

$ git status
$ git add <shatever file>
$ git status
$ git commit -m"I made a bunch of changes, there are so many details, wee."
```

### Share my work with the world!

firstl, create a github repo

```Shell
$ git remote add origin git@github.com:<github username>/<name of repository>.git
$ git push -u origin master


