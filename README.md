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
$ git add README  
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
  
  new file:  README
  
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout --<file>..." to discard changes in working directory)
  
   modified:  CONTRIBUTING.md
$ git add CONTRIBUTING.md
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)
  
  new file:  README
  modified:  CONTRIBUTING.md
$ vim CONTRIBUTING.md
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)
  
  new file: README
  modified: CONTRIBUTING.md
  
Changes not staged to commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)
  
  modified:  CONTRIBUTING.md
$ git add CONTRIBUTING.md
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)
  
  new file:  README
  modified:  CONTRIBUTING.md 
