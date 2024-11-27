unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git branch

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git branch main
fatal: not a valid object name: 'main'

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git branch -M main

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git branch

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git status
On branch main

No commits yet

Untracked files:
(use "git add <file>..." to include in what will be committed)
beach.mp4
index.html
logoHTML.png
index.html
logoHTML.png
index.html
index.html
logoHTML.png
style.css

nothing added to commit but untracked files present (use "git add" to track)

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git add .

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git status
On branch main

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)
new file: beach.mp4
new file: index.html
new file: logoHTML.png
new file: style.css

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git commit -m 'Initial commit'
[main (root-commit) ff5bcc9] Initial commit
4 files changed, 86 insertions(+)
create mode 100644 beach.mp4
create mode 100644 index.html
create mode 100644 logoHTML.png
create mode 100644 style.css

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 4.63 MiB | 11.72 MiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Bleucendre/HTML_CSS_TEST.git

- [new branch] main -> main

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git pull origin main
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 935 bytes | 93.00 KiB/s, done.
From https://github.com/Bleucendre/HTML_CSS_TEST
Unpacking objects: 100% (3/3), 935 bytes | 93.00 KiB/s, done.
From https://github.com/Bleucendre/HTML_CSS_TEST

- branch main -> FETCH_HEAD
  From https://github.com/Bleucendre/HTML_CSS_TEST
- branch main -> FETCH_HEAD
- branch main -> FETCH_HEAD
  ff5bcc9..d440aa8 main -> origin/main
  Updating ff5bcc9..d440aa8
  Fast-forward
  Fast-forward
  README.md | 1 +
  1 file changed, 1 insertion(+)
  create mode 100644 README.md

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git branch

- main

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git checkout -b 'feat-add-title'
Switched to a new branch 'feat-add-title'

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git branch

- feat-add-title
  main

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git dtatus
git: 'dtatus' is not a git command. See 'git --help'.

The most similar command is
status

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git status
On branch feat-add-title
nothing to commit, working tree clean

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git add index.html

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git commit -m 'Add title'
[feat-add-title 7653c4f] Add title
1 file changed, 5 insertions(+), 2 deletions(-)

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git push origin feat-add-title
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 351 bytes | 351.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'feat-add-title' on GitHub by visiting:
remote: https://github.com/Bleucendre/HTML_CSS_TEST/pull/new/feat-add-title
remote:
To https://github.com/Bleucendre/HTML_CSS_TEST.git

- [new branch] feat-add-title -> feat-add-title

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git pull origin feat-add-title
From https://github.com/Bleucendre/HTML_CSS_TEST

- branch feat-add-title -> FETCH_HEAD
  Already up to date.

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git add index.html

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git commit -m 'Change title'
[feat-add-title 30ece35] Change title
1 file changed, 1 insertion(+), 1 deletion(-)

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git push origin feat-add-title
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 295 bytes | 295.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Bleucendre/HTML_CSS_TEST.git
7653c4f..30ece35 feat-add-title -> feat-add-title

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (feat-add-title)
$ git checkout main
Switched to branch 'main'

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git pull origin main
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 941 bytes | 94.00 KiB/s, done.
From https://github.com/Bleucendre/HTML_CSS_TEST

- branch main -> FETCH_HEAD
  d440aa8..ef0c5b4 main -> origin/main
  Updating d440aa8..ef0c5b4
  Fast-forward
  README.md | 2 +-
  1 file changed, 1 insertion(+), 1 deletion(-)

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git merge feat-add-title
Merge made by the 'ort' strategy.
index.html | 7 +++++--
1 file changed, 5 insertions(+), 2 deletions(-)

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git add .

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git commit -m 'merge feat-add-title'
On branch main
nothing to commit, working tree clean

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git pudh origin main
git: 'pudh' is not a git command. See 'git --help'.

The most similar command is
push

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git push origin main
Enumerating objects: 12, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 851 bytes | 851.00 KiB/s, done.
Total 8 (delta 5), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (5/5), completed with 3 local objects.
To https://github.com/Bleucendre/HTML_CSS_TEST.git
ef0c5b4..5906927 main -> main

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git branch -d feat-add-title
Deleted branch feat-add-title (was 30ece35).

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git branch

- main

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$ git push origin --delete feat-add-title
To https://github.com/Bleucendre/HTML_CSS_TEST.git

- [deleted] feat-add-title

unoli@PC_OLIV MINGW64 ~/Documents/PROJECTS_TRAINING_SUMMER_2024/SANDBOX/HTML_CSS_TEST (main)
$
