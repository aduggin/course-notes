# Git Screencasts 
by Scott Chacon

1. [Setup and Init](http://www.youtube.com/watch?v=Esl439M154M)
2. [Normal Workflow](http://www.youtube.com/watch?v=U1ayH6KLqxo)
3. [Interactive Add](http://www.youtube.com/watch?v=i2D2HYFlOuU)
4. [Git Log](http://www.youtube.com/watch?v=jnGbU-_m8oY)
5. [Browsing](http://www.youtube.com/watch?v=cX9nT8gQQkA)
6. [Branching and Merging](http://www.youtube.com/watch?v=tl5IDfwdvxo)
7. [Rebasing](http://www.youtube.com/watch?v=FyxiLdelSqc)
8. [Distributed Workflow](http://www.youtube.com/watch?v=KWNIKb6sftw)
9. [Creating Empty Branches](http://www.youtube.com/watch?v=vf8NVmLcqT8)

## 1.Setup and Init

Commands show in the video:

| Command        | Description         |
| ------------- |-------------|
| git config --global user.name 'Al Duggin'     | Setup a git configurations globally |
| git config user.name     | Output a git configuration |
| cat ~./gitconfig| show the contents of gitconfig|
| git init     | initializes a directory as a Git repository |
| find .git/      | list everything in the repository      |
| git status      | view the status of your files in the working directory and staging area      |
| git add .      | adds file contents to the staging area      |
| git ls-files      | list the files in the index      |
| git ls-files --stage      | list the files in the index with extra details      |
| git commit      | records a snapshot of the staging area      |
| git log      | show the commit history      |
| git clone {uri}      | clone a repository      |


Related commands:

| Command        | Description         |
| ------------- |-------------|
| git config -l     | list all git configurations |
| git add git_screencasts.md     | add the contents of a particular file to the staging area |
| git commit -m "This is the first commit" | add a message to the commit (without opening an editor)|
| git commit -am "Updated my tracked file" | add and commit a tracked with a message|
| git log git_screencasts.md | show the commit history of a file|

## 2. Normal Workflow

Commands show in the video:

| Command        | Description         |
| ------------- |-------------|
| tree | output a directory listing in a tree format. |
| git rm robots.txt | Remove a file (from your working directory and from the git index) |
| git count-objects | count how many objects are in the repository |
| cmd | desc |

Git add is what adds the content into the repository
The commit adds the commit object and the tree object


Related commands:

| Command        | Description         |
| ------------- |-------------|
| brew install tree | install tree |



## 3. Add Interactive

Commands show in the video:

| Command        | Description         |
| ------------- |-------------|
| git add i | desc |


Related commands:

| Command        | Description         |
| ------------- |-------------|
| cmd | desc |


## Branching and Merging

Commands show in the video:

| Command        | Description         |
| ------------- |-------------|
| git branch | Show which branches there are and which one you are on |
| git branch blue | Create a new branch called blue |
| git branch -b email | Create a new branch called email and switch to it |
| git branch -b fixicon master| Create a new branch called fixicon based on the matser branch and switch to it |
| git log --oneline --graph --all | show graph of everything that is reachable in our history|
| git log --oneline --graph --decorate --all | show graph of everything that is reachable in our history and show your branches |
| git merge carousel | merge the branch 'carousel' into the current branch |
| git branch --merged | show the branches that have been merged|
| git branch --no-merge | show which branches haven't been merged yet |
| git branch -d blue | delete the blue branch|
| git branch -d blue email fixicon | delete multiple branches |
| git tag -a v1.0| tag current commit as 'v1.0' and add a tag message |
| git show| |


Related commands:

| Command        | Description         |
| ------------- |-------------|
| cmd | desc |


## chapter_title

Commands show in the video:

| Command        | Description         |
| ------------- |-------------|
| cmd | desc |


Related commands:

| Command        | Description         |
| ------------- |-------------|
| cmd | desc |










