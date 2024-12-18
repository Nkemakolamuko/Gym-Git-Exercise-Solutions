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
