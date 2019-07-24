GIT Issue Solve
Create a new local repository
git init

Create a working copy of a local repository:
git clone /path/to/repository

Configure the author name and email address to be used with your commits.
Note that Git strips some characters (for example trailing periods) from user.name.
git config --global user.name "username"
git config --global user.email "user@example.com"

Add one or more files to staging (index):
git add

commit
Commit changes to head (but not yet to the remote repository):
git commit -m "Commit message"

commit with adding all files automatically
Commit any files you've added with git add, and also commit any files you've changed since then:
git commit -a

Send changes to the master branch of your remote repository:
git push origin master

List the files you've changed and those you still need to add or commit
git status

Create a new branch and switch to it:
git checkout -b

Switch from one branch to another:
git checkout

Delete the feature branch:
git branch -d

Push the branch to your remote repository, so others can use it:
git push origin

Push all branches to your remote repository:
git push --all origin

List all the branches in your repo, and also tell you what branch you're currently in:
git branch

check Conflict Status in git
git grep '<<<<<<< HEAD'
