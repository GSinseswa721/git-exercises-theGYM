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
Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git checkout feature-branch
error: pathspec 'feature-branch' did not match any file(s) known to git

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git status
On branch ft/contact-page
nothing to commit, working tree clean

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git checkout -b ft/team-page
fatal: a branch named 'ft/team-page' already exists

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/team-page)
$ git log
commit 82c6e5358c3707a0bf1591e13d4fbb1a8b0f43de (HEAD -> ft/team-page, origin/ft/team-page)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Fri Jul 28 11:09:00 2023 +0200

    added team page

commit 37f0256ef4e1c4aa6b03439605815bdea248438f (origin/main, origin/HEAD, main, ft/contact-page)
Merge: 16848b6 abbfc89
Author: Gloria Niyonkuru Sinseswa <85382004+GSinseswa721@users.noreply.github.com>
Date:   Fri Jul 28 10:57:41 2023 +0200

    Merge pull request #3 from GSinseswa721/ft/service-redesign

    added service list

commit abbfc897808bc94640d9d38c85ea70f179c77ac1 (origin/ft/service-redesign, ft/service-redesign)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Thu Jul 27 12:36:39 2023 +0200

    updated readme
:

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git cherry-pick git checkout feature-branch
fatal: bad revision 'git'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git cherry-pick 82c6e5358c3707a0bf1591e13d4fbb1a8b0f43de1~
fatal: bad revision '82c6e5358c3707a0bf1591e13d4fbb1a8b0f43de1~'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git cherry-pick 82c6e5358c3707a0bf1591e13d4fbb1a8b0f43de1
fatal: bad revision '82c6e5358c3707a0bf1591e13d4fbb1a8b0f43de1'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git cherry-pick 82c6e5358c3707a0bf1591e13d4fbb1a8b0f43de1
fatal: bad revision '82c6e5358c3707a0bf1591e13d4fbb1a8b0f43de1'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git cherry-pick 82c6e5358c3707a0bf1591e13d4fbb1a8b0f43de1
fatal: bad revision '82c6e5358c3707a0bf1591e13d4fbb1a8b0f43de1'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git cherry-pick 82c6e5358c3707a0bf1591e13d4fbb1a8b0f43de
[ft/contact-page fe441cf] added team page
 Date: Fri Jul 28 11:09:00 2023 +0200
 1 file changed, 11 insertions(+)
 create mode 100644 team.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/Documents/git-exercises-theGYM (ft/contact-page)
$ git log
commit fe441cf6fecbd0efbde0190adabfb486a1d45dd1 (HEAD -> ft/contact-page)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Fri Jul 28 11:09:00 2023 +0200

    added team page

commit 37f0256ef4e1c4aa6b03439605815bdea248438f (origin/main, origin/HEAD, main)
Merge: 16848b6 abbfc89
Author: Gloria Niyonkuru Sinseswa <85382004+GSinseswa721@users.noreply.github.com>
Date:   Fri Jul 28 10:57:41 2023 +0200

    Merge pull request #3 from GSinseswa721/ft/service-redesign

    added service list

commit abbfc897808bc94640d9d38c85ea70f179c77ac1 (origin/ft/service-redesign, ft/service-redesign)
Author: Gsinseswa721 <glorianiyonkurusinseswa@gmail.com>
Date:   Thu Jul 27 12:36:39 2023 +0200

    updated readme
:
  
