# Gym-Git-Exercise-Solutions

# Bundle 01

## Exercise_1

```bash
vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions
$ mkdir project

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions
$ cd project/

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project
$ git init
Initialized empty Git repository in C:/Users/vinti/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project/.git/

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ ls

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ ls -a
./  ../  .git/

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (main)
$ git branch -m main master

vinti@SLIMs MINGW64 ~/OneDrive/Desktop/Projects/Gym_Rwanda/gym-git-exercise-solutions/all-solutions/project (master)
$ git branch -m master main

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
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


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
