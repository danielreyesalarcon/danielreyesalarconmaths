$ cd C:/Users/user/my_project
$ git init
$ git add LICENSE
$ git commit -m 'Initial project version'
$ git clone https://github.com/libgit2/libgit2 mylibgit
s git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
$ echo 'My Project' > README
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)
  
    README
  
 nothing added to commit but untracked files present (use "git add" to track)
  
