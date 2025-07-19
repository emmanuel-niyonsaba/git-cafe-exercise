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
```
## Bunble 6
## Exercises
```bash

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (ft/menu)
$ git checkout -b fix/menu
Switched to a new branch 'fix/menu'

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$ git add .

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$ git commit -m"refactor: add contact"
[fix/menu 1f4b7c3] refactor: add contact
 1 file changed, 1 insertion(+), 1 deletion(-)

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$ git push
fatal: The current branch fix/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin fix/menu

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$  git push --set-upstream origin fix/menu
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 311 bytes | 311.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'fix/menu' on GitHub by visiting:
remote:      https://github.com/emmanuel-niyonsaba/git-cafe-exercise/pull/new/fix/menu
remote:
To https://github.com/emmanuel-niyonsaba/git-cafe-exercise.git
 * [new branch]      fix/menu -> fix/menu
branch 'fix/menu' set up to track 'origin/fix/menu'.

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$
```
## Bandle 6 
## Exercises 3
```bash
user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$ git add .

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$ git commit -m"fix: contact"
[fix/menu a283c6c] fix: contact
 1 file changed, 1 insertion(+), 1 deletion(-)

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$ git commit --amend"fix: telphone"
error: unknown option `amendfix: telphone'
usage: git commit [-a | --interactive | --patch] [-s] [-v] [-u[<mode>]] [--amend]
                  [--dry-run] [(-c | -C | --squash) <commit> | --fixup [(amend|reword):]<commit>]  
                  [-F <file> | -m <msg>] [--reset-author] [--allow-empty]
                  [--allow-empty-message] [--no-verify] [-e] [--author=<author>]
                  [--date=<date>] [--cleanup=<mode>] [--[no-]status]
                  [-i | -o] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                  [(--trailer <token>[(=|:)<value>])...] [-S[<keyid>]]
                  [--] [<pathspec>...]

    -q, --[no-]quiet      suppress summary after successful commit
    -v, --[no-]verbose    show diff in commit message template

Commit message options
    -F, --[no-]file <file>
                          read message from file
    --[no-]author <author>
                          override author for commit
    --[no-]date <date>    override date for commit
    -m, --[no-]message <message>
                          commit message
    -c, --[no-]reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --[no-]reuse-message <commit>
                          reuse message from specified commit
    --[no-]fixup [(amend|reword):]commit
                          use autosquash formatted message to fixup or amend/reword specified commit
    --[no-]squash <commit>
                          use autosquash formatted message to squash specified commit
    --[no-]reset-author   the commit is authored by me now (used with -C/-c/--amend)
    --trailer <trailer>   add custom trailer(s)
    -s, --[no-]signoff    add a Signed-off-by trailer
    -t, --[no-]template <file>
                          use specified template file
    -e, --[no-]edit       force edit of commit
    --[no-]cleanup <mode> how to strip spaces and #comments from message
    --[no-]status         include status in commit message template
    -S, --[no-]gpg-sign[=<key-id>]
                          GPG sign commit

Commit contents options
    -a, --[no-]all        commit all changed files
    -i, --[no-]include    add specified files to index for commit
    --[no-]interactive    interactively add files
    -p, --[no-]patch      interactively add changes
    -o, --[no-]only       commit only specified files
    -n, --no-verify       bypass pre-commit and commit-msg hooks
    --verify              opposite of --no-verify
    --[no-]dry-run        show what would be committed
    --[no-]short          show status concisely
    --[no-]branch         show branch information
    --[no-]ahead-behind   compute full ahead/behind values
    --[no-]porcelain      machine-readable output
    --[no-]long           show status in long format (default)
    -z, --[no-]null       terminate entries with NUL
    --[no-]amend          amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    --post-rewrite        opposite of --no-post-rewrite
    -u, --[no-]untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)    
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character


user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$ git commit --amend" -fix: telphone"
error: unknown option `amend -fix: telphone'
usage: git commit [-a | --interactive | --patch] [-s] [-v] [-u[<mode>]] [--amend]
                  [--dry-run] [(-c | -C | --squash) <commit> | --fixup [(amend|reword):]<commit>]
                  [-F <file> | -m <msg>] [--reset-author] [--allow-empty]
                  [--allow-empty-message] [--no-verify] [-e] [--author=<author>]
                  [--date=<date>] [--cleanup=<mode>] [--[no-]status]
                  [-i | -o] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                  [(--trailer <token>[(=|:)<value>])...] [-S[<keyid>]]
                  [--] [<pathspec>...]

    -q, --[no-]quiet      suppress summary after successful commit
    -v, --[no-]verbose    show diff in commit message template

Commit message options
    -F, --[no-]file <file>
                          read message from file
    --[no-]author <author>
                          override author for commit
    --[no-]date <date>    override date for commit
    -m, --[no-]message <message>
                          commit message
    -c, --[no-]reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --[no-]reuse-message <commit>
                          reuse message from specified commit
    --[no-]fixup [(amend|reword):]commit
                          use autosquash formatted message to fixup or amend/reword specified commit
    --[no-]squash <commit>
                          use autosquash formatted message to squash specified commit
    --[no-]reset-author   the commit is authored by me now (used with -C/-c/--amend)
    --trailer <trailer>   add custom trailer(s)
    -s, --[no-]signoff    add a Signed-off-by trailer
    -t, --[no-]template <file>
                          use specified template file
    -e, --[no-]edit       force edit of commit
    --[no-]cleanup <mode> how to strip spaces and #comments from message
    --[no-]status         include status in commit message template
    -S, --[no-]gpg-sign[=<key-id>]
                          GPG sign commit

Commit contents options
    -a, --[no-]all        commit all changed files
    -i, --[no-]include    add specified files to index for commit
    --[no-]interactive    interactively add files
    -p, --[no-]patch      interactively add changes
    -o, --[no-]only       commit only specified files
    -n, --no-verify       bypass pre-commit and commit-msg hooks
    --verify              opposite of --no-verify
    --[no-]dry-run        show what would be committed
    --[no-]short          show status concisely
    --[no-]branch         show branch information
    --[no-]ahead-behind   compute full ahead/behind values
    --[no-]porcelain      machine-readable output
    --[no-]long           show status in long format (default)
    -z, --[no-]null       terminate entries with NUL
    --[no-]amend          amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    --post-rewrite        opposite of --no-post-rewrite
    -u, --[no-]untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character


user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$ git commit --amend -m"fix: telphone"
[fix/menu 58aafe3] fix: telphone
 Date: Sat Jul 19 17:48:57 2025 +0200
 1 file changed, 1 insertion(+), 1 deletion(-)

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 314 bytes | 314.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/emmanuel-niyonsaba/git-cafe-exercise.git
   f1245c9..58aafe3  fix/menu -> fix/menu

user@EmmauelNiyonsaba MINGW64 /d/CodingRelated/git-cafe-exercise (fix/menu)
$