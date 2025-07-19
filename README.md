# git-cafe-exercise
``
## Bundle 5 
## Exercises 2
```bash

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$ git add .

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$ git commit -m"refactor: add restaurant"
[main 9f4b8e6] refactor: add restaurant
 1 file changed, 1 insertion(+), 1 deletion(-)

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/emmanuel-niyonsaba/git-cafe-exercise.git
   d1d3f9c..9f4b8e6  main -> main

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$
```
## Bundle 6
## Exercises 1
```bash
user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$ git add .

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$ git commit -m"refactor: add restaurant"
[main 9f4b8e6] refactor: add restaurant
 1 file changed, 1 insertion(+), 1 deletion(-)

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/emmanuel-niyonsaba/git-cafe-exercise.git
   d1d3f9c..9f4b8e6  main -> main

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$ git add .

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$ git commit -m"done by B5 E2"
[main dbeefb6] done by B5 E2
 1 file changed, 27 insertions(+)

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 700 bytes | 700.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/emmanuel-niyonsaba/git-cafe-exercise.git
   9f4b8e6..dbeefb6  main -> main

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (main)
$ git checkout -b ft/menu
Switched to a new branch 'ft/menu'

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (ft/menu)
$ git add .

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (ft/menu)
$ git  commit -m"newFeature menu "
[ft/menu cb8ed7f] newFeature menu
 1 file changed, 11 insertions(+)
 create mode 100644 menu.html

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (ft/menu)
$ git push
fatal: The current branch ft/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/menu

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (ft/menu)
$  git push --set-upstream origin ft/menu
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 449 bytes | 449.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/emmanuel-niyonsaba/git-cafe-exercise/pull/new/ft/menu
remote:
To https://github.com/emmanuel-niyonsaba/git-cafe-exercise.git
 * [new branch]      ft/menu -> ft/menu
branch 'ft/menu' set up to track 'origin/ft/menu'.

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (ft/menu)
$
