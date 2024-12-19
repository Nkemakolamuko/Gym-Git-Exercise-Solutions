# Gym-Git-Exercise-Solutions

## Bundle 01

### Exercise_1

```bash
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions
$ mkdir project

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions
$ cd project/

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project
$ git init
Initialized empty Git repository in C:/Users/vinti/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project/.git/

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ touch index.html style.css script.js

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ mkdir assets

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git branch -m main master

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (master)
$ git branch -m master main

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add --all

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git commit -m "Initial commit --"
[main (root-commit) 1fd399f] Initial commit --
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html
 create mode 100644 script.js
 create mode 100644 style.css

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git remote add origin git@github.com:Nkemakolamuko/bundle1_exercise_1.git

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 237 bytes | 237.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:Nkemakolamuko/bundle1_exercise_1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git checkout -b dev
Switched to a new branch 'dev'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (dev)
$ git checkout -b test
Switched to a new branch 'test'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (test)
$ git branch
  dev
  main
* test

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (test)
$ git checkout dev
Switched to branch 'dev'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (dev)
$ git branch -d test
Deleted branch test (was 1fd399f).

```

## Bundle 01

### Exercise_2

```bash
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ touch home.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ code home.html
Run with 'code -' to read output from another program (e.g. 'echo Hello World | code -').

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to track)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash save "The home file"
No local changes to save

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash list

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add home.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash save "The home file -"
Saved working directory and index state On main: The home file -

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ touch about.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash save "The about file -"
No local changes to save

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add about.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash save "The about file -"
Saved working directory and index state On main: The about file -

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ touch team.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add team.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash save "The team file -"
Saved working directory and index state On main: The team file -

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash list
stash@{0}: On main: The team file -
stash@{1}: On main: The about file -
stash@{2}: On main: The home file -

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash pop stash@{1}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (5e249e9fd0b42a0cff7e2d092f2b4eb14151016c)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash pop stash@{2}
fatal: log for 'stash' only has 2 entries

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash list
stash@{0}: On main: The team file -
stash@{1}: On main: The home file -

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash pop stash@{1}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (0ffa2c8203ac35ccb8b4f6190ee763d710dde066)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   about.html


vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add about.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html


vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$  git commit -m "Bring back the about and home files that were stashed -"
[main 4745c65] Bring back the about and home files that were stashed -
 2 files changed, 22 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 550 bytes | 183.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To github.com:Nkemakolamuko/bundle1_exercise_1.git
   1fd399f..4745c65  main -> main

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash pop
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (83fda1ea63ea4f598e6ea9415478e8771d0b946c)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html


vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add team.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git reset

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add team.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash save "Team file page -"
Saved working directory and index state On main: Team file page -

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git pop
git: 'pop' is not a git command. See 'git --help'.

The most similar command is
        log

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git stash pop
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (25c923ce3d028162934f5e3869aa08672646cdd1)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git reset

```

## Bundle 02

### Exercise_1

```bash
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/bundle-2)
$ touch services.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/bundle-2)
$ git add services.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/bundle-2)
$ git commit -m "Create a branch and add services page to it --"
[ft/bundle-2 7b220c6] Create a branch and add services page to it --
 1 file changed, 11 insertions(+)
 create mode 100644 services.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/bundle-2)
$ git push origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 463 bytes | 231.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Nkemakolamuko/bundle1_exercise_1/pull/new/ft/bundle-2
remote:
To github.com:Nkemakolamuko/bundle1_exercise_1.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

no changes added to commit (use "git add" and/or "git commit -a")

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/bundle-2)
$ git add services.html
g
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/bundle-2)
$ git commit -m "Few changes --"
[ft/bundle-2 6021451] Few changes --
 1 file changed, 1 insertion(+), 1 deletion(-)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/bundle-2)
$ git push --set-upstream origin ft/bundle-2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 299 bytes | 74.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:Nkemakolamuko/bundle1_exercise_1.git
   7b220c6..6021451  ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

```

## Bundle 02

### Exercise_2

```bash
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git pull
remote: Enumerating objects: 2, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (2/2), 1.78 KiB | 18.00 KiB/s, done.
From github.com:Nkemakolamuko/bundle1_exercise_1
   4745c65..0723fcf  main       -> origin/main
Updating 4745c65..0723fcf
Fast-forward
 services.html | 11 +++++++++++
 1 file changed, 11 insertions(+)
 create mode 100644 services.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git checkout ft/service-redesign
error: pathspec 'ft/service-redesign' did not match any file(s) known to git

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git branch ft/service-redesign

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git branch
  dev
  ft/bundle-2
  ft/service-redesign
* main

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ ls
about.html  assets/  home.html  index.html  script.js  services.html  style.css  team.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

no changes added to commit (use "git add" and/or "git commit -a")

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add services.html
g
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git commit -m "Newly added changes -"
[main 12e1014] Newly added changes -
 1 file changed, 1 insertion(+)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/service-redesign)
$ git status
On branch ft/service-redesign
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git reset

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/service-redesign)
$ git status
On branch ft/service-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

no changes added to commit (use "git add" and/or "git commit -a")

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/service-redesign)
$ git add services.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/service-redesign)
$ git commit -m "Newly added modification -"
[ft/service-redesign a2bf0af] Newly added modification -
 1 file changed, 1 insertion(+)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/service-redesign)
$ git push --set-upstream origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 327 bytes | 327.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/Nkemakolamuko/bundle1_exercise_1/pull/new/ft/service-redesign
remote:
To github.com:Nkemakolamuko/bundle1_exercise_1.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add services.html
g
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git commit -m "Modify same line as did the other branch -"
[main 861bd28] Modify same line as did the other branch -
 1 file changed, 1 insertion(+), 1 deletion(-)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git push
To github.com:Nkemakolamuko/bundle1_exercise_1.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'github.com:Nkemakolamuko/bundle1_exercise_1.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 930 bytes | 21.00 KiB/s, done.
From github.com:Nkemakolamuko/bundle1_exercise_1
   0723fcf..657abd6  main       -> origin/main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main|MERGING)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/service-redesign)
$ git diff

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/service-redesign)
$ git push
Everything up-to-date

```
