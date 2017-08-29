# Git Command
**Git revision control as follows**

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)


### Create a new local repository
```git-init
$ cd project directory
```
```git-init
$ git init
```
***Git will reply
Initialized empty Git repository in .git***
```git-init
$ git tag [-l]/[-a] v1.2 9fceb02 -m "Message here"
$ push --tags origin master
```
Or you can follow:
```git-init
$ git tag [-l]/[-a] v1.2 9fceb02 -m "Message here"
$ git push origin --tags
```
Or you can follow:
```git-init
$ git tag [-l]/[-a] v1.2 9fceb02 -m "Message here"
$ git push --tags
```
```git-init
# delete local tag '12345'
git tag -d 12345
# delete remote tag '12345' (eg, GitHub version too)
git push origin :refs/tags/12345
# alternative approach
git push --delete origin tagName
git tag -d tagName
```
