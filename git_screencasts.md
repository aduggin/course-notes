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

## Setup and Init

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









