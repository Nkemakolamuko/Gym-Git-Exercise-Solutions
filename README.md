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

## Bundle 03

### Exercise_1

```bash

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git branch -b ft/team-page
error: unknown switch `b'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --[no-]verbose    show hash and subject, give twice for upstream branch
    -q, --[no-]quiet      suppress informational messages
    -t, --[no-]track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --[no-]set-upstream-to <upstream>
                          change the upstream info
    --[no-]unset-upstream unset the upstream info
    --[no-]color[=<when>] use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --[no-]abbrev[=<n>]   use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --[no-]delete     delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --[no-]move       move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    --[no-]omit-empty     do not output a newline after empty formatted refs
    -c, --[no-]copy       copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --[no-]list       list branch names
    --[no-]show-current   show current branch name
    --[no-]create-reflog  create the branch's reflog
    --[no-]edit-description
                          edit the description for the branch
    -f, --[no-]force      force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --[no-]column[=<style>]
                          list branches in columns
    --[no-]sort <key>     field name to sort on
    --[no-]points-at <object>
                          print only branches of the object
    -i, --[no-]ignore-case
                          sorting and filtering are case insensitive
    --[no-]recurse-submodules
                          recurse through submodules
    --[no-]format <format>
                          format to use for the output


vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/team-page)
$ touch team.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/team-page)
$ ls
about.html  assets/  home.html  index.html  script.js  services.html  style.css  team.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/team-page)
$ git status
On branch ft/team-page
nothing to commit, working tree clean

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/team-page)
$ git status
On branch ft/team-page
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html

no changes added to commit (use "git add" and/or "git commit -a")

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/team-page)
$ git add team.html
g
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/team-page)
$ git commit -m "Our team page -"
[ft/team-page ece8cb9] Our team page -
 1 file changed, 4 insertions(+)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/team-page)
$ git push --set-upstream origin ft/team-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 520 bytes | 520.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Nkemakolamuko/bundle1_exercise_1/pull/new/ft/team-page
remote:
To github.com:Nkemakolamuko/bundle1_exercise_1.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git branch ft/contact-page

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git branch
  dev
  ft/bundle-2
  ft/contact-page
  ft/service-redesign
  ft/team-page
* main

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/team-page)
$ git log
commit ece8cb97e19c83072027d8e7b3856210c5bc72c6 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 12:11:59 2024 +0200

    Our team page -

commit 838db10e2caa93abcf0a4d8ed315e70308eb97d6 (origin/main, main, ft/contact-page)
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 11:50:06 2024 +0200

    My recent commit

commit f1c3b8083957b9c46867773ea68a603e85e90d27
Merge: 861bd28 657abd6
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 11:49:49 2024 +0200

    Merge branch 'main' of github.com:Nkemakolamuko/bundle1_exercise_1

commit 861bd28ad0e16b238974ca71cd5298bd587f5e61
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 11:47:46 2024 +0200

    Modify same line as did the other branch -

commit 657abd6b5e4297290fb6739e094ebab713fc650c
Merge: 0723fcf a2bf0af
Author: Nkem Vincent Nweke <101292204+Nkemakolamuko@users.noreply.github.com>
Date:   Thu Dec 19 11:46:00 2024 +0200

    Merge pull request #3 from Nkemakolamuko/ft/service-redesign

    Newly added modification -

commit a2bf0af978dc3a7827e4e05e37e98028de15c3f1 (origin/ft/service-redesign, ft/service-redesign)
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 11:43:09 2024 +0200

    Newly added modification -

commit 12e1014e695e62c3fd53714da3dc52f68a6a514d
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 11:37:45 2024 +0200

    Newly added changes -

commit 0723fcf9d28ee917323b1ac9b4bc10a0accf4f98
Merge: 2670638 6021451
Author: Peter Opara <oparap8@gmail.com>
Date:   Thu Dec 19 08:41:48 2024 +0100
:
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 12:11:59 2024 +0200

    Our team page -

commit 838db10e2caa93abcf0a4d8ed315e70308eb97d6 (origin/main, main, ft/contact-page)
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 11:50:06 2024 +0200

    My recent commit

commit f1c3b8083957b9c46867773ea68a603e85e90d27
Merge: 861bd28 657abd6
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 11:49:49 2024 +0200

    Merge branch 'main' of github.com:Nkemakolamuko/bundle1_exercise_1

commit 861bd28ad0e16b238974ca71cd5298bd587f5e61
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 11:47:46 2024 +0200

    Modify same line as did the other branch -

commit 657abd6b5e4297290fb6739e094ebab713fc650c
Merge: 0723fcf a2bf0af
Author: Nkem Vincent Nweke <101292204+Nkemakolamuko@users.noreply.github.com>
Date:   Thu Dec 19 11:46:00 2024 +0200

    Merge pull request #3 from Nkemakolamuko/ft/service-redesign

    Newly added modification -

commit a2bf0af978dc3a7827e4e05e37e98028de15c3f1 (origin/ft/service-redesign, ft/service-redesign)
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 11:43:09 2024 +0200

    Newly added modification -

commit 12e1014e695e62c3fd53714da3dc52f68a6a514d
Author: Slim <vintio234@gmail.com>
Date:   Thu Dec 19 11:37:45 2024 +0200

    Newly added changes -

commit 0723fcf9d28ee917323b1ac9b4bc10a0accf4f98
Merge: 2670638 6021451
Author: Peter Opara <oparap8@gmail.com>
Date:   Thu Dec 19 08:41:48 2024 +0100

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/contact-page)
$ git cherry-pick ece8cb97e19c83072027d8e7b3856210c5bc72c6
[ft/contact-page 0701b5c] Our team page -
 Date: Thu Dec 19 12:11:59 2024 +0200
 1 file changed, 4 insertions(+)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/contact-page)
$ git status
On branch ft/contact-page
nothing to commit, working tree clean

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/contact-page)
$ ls
about.html  assets/  home.html  index.html  script.js  services.html  style.css  team.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/contact-page)
$ touch contact.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/contact-page)
$ git status
On branch ft/contact-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html

nothing added to commit but untracked files present (use "git add" to track)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/contact-page)
$ git add contact.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/contact-page)
$ git commit -m "Add contact page -"
[ft/contact-page 9fe068f] Add contact page -
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/contact-page)
$ git push --set-upstream origin ft/contact-page
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 948 bytes | 474.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Nkemakolamuko/bundle1_exercise_1/pull/new/ft/contact-page
remote:
To github.com:Nkemakolamuko/bundle1_exercise_1.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/contact-page)
$ git branch -b ft/faq-page
error: unknown switch `b'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --[no-]verbose    show hash and subject, give twice for upstream branch
    -q, --[no-]quiet      suppress informational messages
    -t, --[no-]track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --[no-]set-upstream-to <upstream>
                          change the upstream info
    --[no-]unset-upstream unset the upstream info
    --[no-]color[=<when>] use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --[no-]abbrev[=<n>]   use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --[no-]delete     delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --[no-]move       move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    --[no-]omit-empty     do not output a newline after empty formatted refs
    -c, --[no-]copy       copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --[no-]list       list branch names
    --[no-]show-current   show current branch name
    --[no-]create-reflog  create the branch's reflog
    --[no-]edit-description
                          edit the description for the branch
    -f, --[no-]force      force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --[no-]column[=<style>]
                          list branches in columns
    --[no-]sort <key>     field name to sort on
    --[no-]points-at <object>
                          print only branches of the object
    -i, --[no-]ignore-case
                          sorting and filtering are case insensitive
    --[no-]recurse-submodules
                          recurse through submodules
    --[no-]format <format>
                          format to use for the output


vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ touch faq.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ git add faq.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ git commit -m "Create and add an faq page -"
[ft/faq-page 915443a] Create and add an faq page -
 1 file changed, 11 insertions(+)
 create mode 100644 faq.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ git push --set-upstream origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 465 bytes | 465.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Nkemakolamuko/bundle1_exercise_1/pull/new/ft/faq-page
remote:
To github.com:Nkemakolamuko/bundle1_exercise_1.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ git revert ece8cb97e19c83072027d8e7b3856210c5bc72c6
[ft/faq-page a75bbb0] Revert "Our team page -"
 1 file changed, 4 deletions(-)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ git status
On branch ft/faq-page
Your branch is ahead of 'origin/ft/faq-page' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:Nkemakolamuko/bundle1_exercise_1.git
   915443a..a75bbb0  ft/faq-page -> ft/faq-page

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ branch
bash: branch: command not found

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ git branch
  dev
  ft/bundle-2
  ft/contact-page
* ft/faq-page
  ft/service-redesign
  ft/team-page
  main

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ git push --set-upstream origin ft/team-page
Everything up-to-date
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

```

## Bundle 03

### Exercise_2

```bash
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/faq-page)
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/home-page-redesign)
$ git branch main
fatal: a branch named 'main' already exists

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ ls
about.html  assets/  home.html  index.html  script.js  services.html  style.css  team.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html
        faq.html

nothing added to commit but untracked files present (use "git add" to track)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add contact.html faq.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git commit -m "Some modification on the pages -"
[main b2d35fd] Some modification on the pages -
 2 files changed, 22 insertions(+)
 create mode 100644 contact.html
 create mode 100644 faq.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 599 bytes | 599.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To github.com:Nkemakolamuko/bundle1_exercise_1.git
   838db10..b2d35fd  main -> main

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/home-page-redesign)
$ git rebase origin/main
dropping 9fe068ff934911a75f54b0cfea5259d2f9253c9e Add contact page - -- patch contents already upstream
dropping 915443ab3273fe343b05f5a7e518d880f8fab67e Create and add an faq page - -- patch contents already upstream
Successfully rebased and updated refs/heads/ft/home-page-redesign.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/home-page-redesign)
$ ls
about.html  assets/  contact.html  faq.html  home.html  index.html  script.js  services.html  style.css  team.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/home-page-redesign)
$ git status
On branch ft/home-page-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/home-page-redesign)
$ git add home.html

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/home-page-redesign)
$ git commit -m "Make some further modifications --"
[ft/home-page-redesign de87bb6] Make some further modifications --
 1 file changed, 1 insertion(+)

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/home-page-redesign)
$ git push origin ft/home-page-redesign
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 1.06 KiB | 542.00 KiB/s, done.
Total 7 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Nkemakolamuko/bundle1_exercise_1/pull/new/ft/home-page-redesign
remote:
To github.com:Nkemakolamuko/bundle1_exercise_1.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign

```

## Bundle 04

### Exercise_1

```bash

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git remote add git-copy git@github.com:Nkemakolamuko/gym-git-exercise-clone.git

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git remote
git-copy
origin

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git status
git On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git add home.html
gi
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git commit -m "A modification to the home page -"
[main 0078e4e] A modification to the home page -
 1 file changed, 1 insertion(+)

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
Unpacking objects: 100% (1/1), 921 bytes | 12.00 KiB/s, done.
From github.com:Nkemakolamuko/bundle1_exercise_1
   b2d35fd..10abafc  main       -> origin/main
Auto-merging home.html
CONFLICT (content): Merge conflict in home.html
Automatic merge failed; fix conflicts and then commit the result.

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main|MERGING)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 656 bytes | 218.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
To github.com:Nkemakolamuko/bundle1_exercise_1.git
   10abafc..ae939ed  main -> main

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git push git-copy
Enumerating objects: 49, done.
Counting objects: 100% (49/49), done.
Delta compression using up to 4 threads
Compressing objects: 100% (48/48), done.
Writing objects: 100% (49/49), 7.97 KiB | 429.00 KiB/s, done.
Total 49 (delta 26), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (26/26), done.
To github.com:Nkemakolamuko/gym-git-exercise-clone.git
 * [new branch]      main -> main

```
