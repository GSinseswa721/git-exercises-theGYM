<h1>GIT EXERCISES SOLUTIONS</h1>
<h2>BUNDLE 1 # EXERCISE 1</h2>

$ git add README.md

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/documents/git-exercises-GYM (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


GLORIA@DESKTOP-1F1FCSK MINGW64 ~/documents/git-exercises-GYM (main)
$ git commit -m "init project"
[main (root-commit) 45c2d15] init project
 1 file changed, 2 insertions(+)
 create mode 100644 README.md

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/documents/git-exercises-GYM (main)
$ git remote add origin https://github.com/GSinseswa721/git-exercises-theGYM.git

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/documents/git-exercises-GYM (main)
$ git status
On branch main
nothing to commit, working tree clean
LORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (main)
$ git status
On branch main
nothing to commit, working tree clean

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (main)
$ git remote add origin https://github.com/GSinseswa721/git-exercises-theGYM.git
error: remote origin already exists.

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (main)
$ git push --set-upstream origin main
Enumerating objects: 3, done.      
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 276 bytes | 69.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/GSinseswa721/git-exercises-theGYM.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (main)
$ git checkout dev
error: pathspec 'dev' did not match any file(s) known to git

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (main)
$ git checkout -b dev
Switched to a new branch 'dev'

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/GSinseswa721/git-exercises-theGYM/pull/new/dev
remote:
To https://github.com/GSinseswa721/git-exercises-theGYM.git
 * [new branch]      dev -> dev

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (dev)
$ git checkout -b test
Switched to a new branch 'test'

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/GSinseswa721/git-exercises-theGYM/pull/new/test
remote:
To https://github.com/GSinseswa721/git-exercises-theGYM.git
 * [new branch]      test -> test

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (test)
$ git checkout dev
Switched to branch 'dev'

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (dev)
$ git branch -D test
Deleted branch test (was 45c2d15).

GLORIA@DESKTOP-1F1FCSK MINGW64 ~/Documents/git-exercises-GYM (dev)
$ git push origin --delete test
To https://github.com/GSinseswa721/git-exercises-theGYM.git
 - [deleted]         test
```
