CSA-complexity
==============

This is the algorithic complexity problem set.

##Getting Started

configure your local git instance
```
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR EMAIL ADDRESS"
```

To download the files to your local machine 
```
git clone https://github.com/user/repo.git
```
see [fetching a remote](https://help.github.com/articles/fetching-a-remote) for more information.

## Tracking and Syncing changes

As you make changes you will need to track them with commits.  You will also need to sync your changes to github.

```
$ git status
```
Lists all new or modified files to be commited
```
$ git add [file]
```
adds the listed file to the staging area
```
$ git reset [file]
```
Unstages the file, but preserve its contents
```
$ git diff
```
Shows file differences not yet staged
```
$ git diff --staged
```
Shows file differences between staging and the last file version
```
$ git commit -m "[descriptive message]"
```
Records file snapshots permanently in version history. The -a option adds all tracked files to the commit.  If you include "fixes #2" in the message, github will link to and close issue #2.
```
$ git stash
```
Temporarily stores all modified tracked files
```
$ git pull
```
fetches any changes from github and merges them with your code
```
$ git push
``` 
sends all of your commits to github

A larger list of [git commands can be found here](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)

##Assignment

Due 10/3 at 3:15pm.  No resubmissions.

You must push your commits to github.  No other submissions are required.  You *may* check your account at github.com to make sure your files are online.
