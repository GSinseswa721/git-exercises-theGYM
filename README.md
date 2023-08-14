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
 `* [new branch]      main -> main
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
` * [new branch]      dev -> dev

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
` * [new branch]      test -> test

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
fatal: subcommand wasn't specified; 'push' can't be assumed due to unexpected token 'services.html'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git stash pop services.html
error: services.html is not a valid reference

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git stash 
Saved working directory and index state WIP on ft/bundle-2: 4d7775f created service page

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git stash 
No local changes to save

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git stash pop services.html
error: services.html is not a valid reference

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'
Your branch is up to date with 'origin/ft/bundle-2'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git add *

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git commit -m "changes"
On branch ft/bundle-2
Your branch is up to date with 'origin/ft/bundle-2'.

nothing to commit, working tree clean

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git push main origin
fatal: 'main' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git push origin
Everything up-to-date

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git stash
No local changes to save

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'
Your branch is up to date with 'origin/ft/bundle-2'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git pull
Already up to date.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git stash pop services.html
error: services.html is not a valid reference

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git stash pop services.html
 *  History restored 


Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ 
 *  History restored 

fatal: subcommand wasn't specified; 'push' can't be assumed due to unexpected token 'services.html'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git stash pop services.html
error: services.html is not a valid reference

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git stash 
Saved working directory and index state WIP on ft/bundle-2: 4d7775f created service page

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git stash 
No local changes to save

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git stash pop services.html
error: services.html is not a valid reference

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'
Your branch is up to date with 'origin/ft/bundle-2'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git add *

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git commit -m "changes"
On branch ft/bundle-2
Your branch is up to date with 'origin/ft/bundle-2'.

nothing to commit, working tree clean

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git push main origin
fatal: 'main' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git push origin
Everything up-to-date

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git stash
No local changes to save

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'
Your branch is up to date with 'origin/ft/bundle-2'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git pull
Already up to date.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git stash pop services.html
error: services.html is not a valid reference

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git stash pop services.html
 *  History restored 


Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ 
 *  History restored 


Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git pull 
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 656 bytes | 218.00 KiB/s, done.
From https://github.com/GSinseswa721/git-exercises-theGYM
   5698a3e..16848b6  main       -> origin/main
Updating 5698a3e..16848b6
Fast-forward
 about.html    | 11 +++++++++++
 home.html     | 11 +++++++++++
 services.html | 11 +++++++++++
 3 files changed, 33 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 services.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git checkout -b ft/service-redesign
fatal: a branch named 'ft/service-redesign' already exists

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git checkout ft/service-redesign
error: Your local changes to the following files would be overwritten by checkout:
        services.html
Please commit your changes or stash them before you switch branches.
Aborting

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git checkout -D  ft/service-redesign
error: unknown switch `D'
usage: git checkout [<options>] <branch>
   or: git checkout [<options>] [<branch>] -- <file>...

    -b <branch>           create and checkout a new branch
    -B <branch>           create/reset and checkout a branch
    -l                    create reflog for new branch
    --guess               second guess 'git checkout <no-such-branch>' (default)
    --overlay             use overlay mode (default)
    -q, --quiet           suppress progress reporting
    --recurse-submodules[=<checkout>]
                          control recursive updating of submodules
    --progress            force progress reporting
    -m, --merge           perform a 3-way merge with the new branch
    --conflict <style>    conflict style (merge, diff3, or zdiff3)
    -d, --detach          detach HEAD at named commit
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -f, --force           force checkout (throw away local modifications)
    --orphan <new-branch>
                          new unparented branch
    --overwrite-ignore    update ignored files (default)
    --ignore-other-worktrees
                          do not check if another worktree is holding the given ref
    -2, --ours            checkout our version for unmerged files
    -3, --theirs          checkout their version for unmerged files
    -p, --patch           select hunks interactively
    --ignore-skip-worktree-bits
                          do not limit pathspecs to sparse entries only
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character


Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git branch -D  ft/service-redesign
Deleted branch ft/service-redesign (was 5698a3e).

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git status
On branch ft/service-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git add *

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git status 
On branch ft/service-redesign
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   services.html


Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git commit -m "added service list"
[ft/service-redesign e744292] added service list
 1 file changed, 9 insertions(+), 1 deletion(-)

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$ git push --set-upstream origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 466 bytes | 466.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/GSinseswa721/git-exercises-theGYM/pull/new/ft/service-redesign
remote:
To https://github.com/GSinseswa721/git-exercises-theGYM.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/service-redesign)
$

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/faq-page)
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-rede
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (main)
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (main)
$ git add --all

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (main)
$ git commit -m "changes on home page"
[main fa4fcce] changes on home page
 1 file changed, 1 insertion(+)

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git status
On branch ft/home-page-redesign
nothing to commit, working tree clean

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git log
commit c8ff6a6764103b8eaf627001cae0b5e6e6d72835 (HEAD -> ft/home-page-redesign, origin/ft/faq-page, ft/faq-page)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Tue Aug 1 11:36:33 2023 +0200

    faq revet

commit 502b347beee9f25df54e109e6f0ee26679041f3e
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Tue Aug 1 11:23:52 2023 +0200

    Add faq page

commit c0292e7f1b860795c1f993abc6b62be739a04062 (origin/ft/contact-page, ft/contact-page)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Tue Aug 1 11:15:16 2023 +0200

    Add contact page

commit fe441cf6fecbd0efbde0190adabfb486a1d45dd1
:
Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git status
On branch ft/home-page-redesign      
nothing to commit, working tree clean

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git log
commit f7a721ecf2b4f7ffe4620b05f92901a8a4db831a (HEAD -> ft/home-page-redesign)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Tue Aug 1 11:36:33 2023 +0200

    faq revet

commit cac287f74816c50d94d51b661b402b7ed1c5fabd
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Tue Aug 1 11:23:52 2023 +0200

    Add faq page

commit 9469df822cff5b1630b2eb834bc31bb3dce508ce

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git status
On branch ft/home-page-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git add home.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git commit -m "added menus"
[ft/home-page-redesign 11eb496] added menus    
 1 file changed, 7 insertions(+), 1 deletion(-)

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git push
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git push --set-upstream origin ft/home-page-redesign
Enumerating objects: 19, done.
Counting objects: 100% (19/19), done.
Delta compression using up to 12 threads
Compressing objects: 100% (17/17), done.
Writing objects: 100% (17/17), 1.80 KiB | 923.00 KiB/s, done.
Total 17 (delta 9), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (9/9), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/GSinseswa721/git-exercises-theGYM/pull/new/ft/home-page-redesign
remote:
To https://github.com/GSinseswa721/git-exercises-theGYM.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'
Your branch is up to date with 'origin/ft/faq-page'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/faq-page)
$ git status
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

nothing to commit, working tree clean

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/faq-page)
$ git checkout -b ft/merge
Switched to a new branch 'ft/merge'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/merge)
$ git status
On branch ft/merge
nothing to commit, working tree clean

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/merge)
$ git merge main
Merge made by the 'ort' strategy.
 home.html | 1 +
 1 file changed, 1 insertion(+)

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/merge)
$ git log
commit 79624b64a38cbe92adece366191451020cf38f18 (HEAD -> ft/merge)
Merge: c8ff6a6 fa4fcce
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Wed Aug 2 11:20:38 2023 +0200

    Merge branch 'main' into ft/merge

commit fa4fccef65319006902be85b1b112fa2d232df8c (main)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Wed Aug 2 10:58:12 2023 +0200

    changes on home page

commit c8ff6a6764103b8eaf627001cae0b5e6e6d72835 (origin/ft/faq-page, ft/faq-page)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Tue Aug 1 11:36:33 2023 +0200

    faq revet

:

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/merge)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
Your branch is up to date with 'origin/ft/home-page-redesign'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/home-page-redesign)
$ git log
commit 11eb496111074f11a8174e7d25d30a4702c1a5f5 (HEAD -> ft/home-page-redesign, origin/ft/home-page-redesign)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Wed Aug 2 11:07:06 2023 +0200

    added menus

commit f7a721ecf2b4f7ffe4620b05f92901a8a4db831a
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Tue Aug 1 11:36:33 2023 +0200

    faq revet

commit cac287f74816c50d94d51b661b402b7ed1c5fabd
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Tue Aug 1 11:23:52 2023 +0200

    Add faq page

commit 9469df822cff5b1630b2eb834bc31bb3dce508ce
:
  $ git push origin ft/squashing
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 367 bytes | 367.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0        
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/GSinseswa721/git-exercises-theGYM/pull/new/ft/squashing
remote: 
To https://github.com/GSinseswa721/git-exercises-theGYM.git
 * [new branch]      ft/squashing -> ft/squashing

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git diff ft/squashing

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git checkout ft/squashing
Switched to branch 'ft/squashing'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/squashing)
$ git log
commit 42dcb079c2461cf12d4e93687e5faa7d6acadae4 (HEAD -> ft/squashing)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Mon Aug 14 20:46:16 2023 +0200

    footer changes squashing

commit 38a65e7d6ce49ff05a48d3ed777323479b3ce0b7 (origin/main, origin/HEAD, git-copy/main, main)
Merge: 9d93899 bfdf1b6
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Thu Aug 3 11:21:19 2023 +0200

    Merge branch 'main' of https://github.com/GSinseswa721/git-exercises-theGYM

commit 9d93899307cf976664a3752fe638d13b8ae85151
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
:

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/squashing)
$ git checkout ft/footer
Switched to branch 'ft/footer'
Your branch is up to date with 'origin/ft/footer'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git log
commit 66d915fe56d8474eeb7f51e2194ffca171dd1253 (HEAD -> ft/footer, origin/ft/footer)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Mon Aug 14 19:23:28 2023 +0200

    feat: add footer contents

commit bde5ae9bdbecb6b51905ce6607904b3202be3409
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Mon Aug 14 19:18:58 2023 +0200

    feat: add footer file

commit 38a65e7d6ce49ff05a48d3ed777323479b3ce0b7 (origin/main, origin/HEAD, git-copy/main, main)
Merge: 9d93899 bfdf1b6
Auth

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/squashing)
$ git status
On branch ft/squashing
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   footer.html


Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/squashing)
$ git commit -m "footer changes squashing"
[ft/squashing 42dcb07] footer changes squashing
 1 file changed, 8 insertions(+)
 create mode 100644 footer.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/squashing)
$ git log
commit 42dcb079c2461cf12d4e93687e5faa7d6acadae4 (HEAD -> ft/squashing)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Mon Aug 14 20:46:16 2023 +0200

    footer changes squashing

commit 38a65e7d6ce49ff05a48d3ed777323479b3ce0b7 (origin/main, origin/HEAD, git-copy/main, main)
Merge: 9d93899 bfdf1b6
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Thu Aug 3 11:21:19 2023 +0200

    Merge branch 'main' of https://github.com/GSinseswa721/git-exercises-theGYM

commit 9d93899307cf976664a3752fe638d13b8ae85151
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
:
Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git checkout -b ft/footer
Switched to a new branch 'ft/footer'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git add footer.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git commit -m "feat: add footer file"
[ft/footer bde5ae9] feat: add footer file       
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 footer.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git status
On branch ft/footer
nothing to commit, working tree clean

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git status
On branch ft/footer
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   footer.html

no changes added to commit (use "git add" and/or "git commit -a")

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git add --all

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git commit -m "feat: add footer contents"
[ft/footer 66d915f] feat: add footer contents
 1 file changed, 8 insertions(+)

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git push
fatal: The current branch ft/footer has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/footer

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git push --set-upstream origin ft/footer
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 618 bytes | 206.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/GSinseswa721/git-exercises-theGYM/pull/new/ft/footer
remote:
To https://github.com/GSinseswa721/git-exercises-theGYM.git
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/footer)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (main)
$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/squashing)
$ git status
On branch ft/squashing
nothing to commit, working tree clean

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/squashing)
$ git merge --squash ft/footer
Updating 38a65e7..66d915f
Fast-forward
Squash commit -- not updating HEAD
 footer.html | 8 ++++++++
 1 file changed, 8 insertions(+)
 create mode 100644 footer.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-exercises-theGYM (ft/squashing)
$ git log
commit 38a65e7d6ce49ff05a48d3ed777323479b3ce0b7 (HEAD -> ft/squashing, origin/main, origin/HEAD, git-copy/main, main)
Merge: 9d93899 bfdf1b6
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Thu Aug 3 11:21:19 2023 +0200

    Merge branch 'main' of https://github.com/GSinseswa721/git-exercises-theGYM

commit 9d93899307cf976664a3752fe638d13b8ae85151
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Thu Aug 3 11:20:25 2023 +0200

    feat: changes on home

commit bfdf1b6d0e383bd2446ae7cdcfb5e9c7008d7707
Author: Gloria Niyonkuru Sinseswa <85382004+GSinseswa721@users.noreply.github.com>
:
