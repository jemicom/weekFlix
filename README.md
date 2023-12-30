ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3
$ cd day03_1230

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230
$ cd ..

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3
$ cd ..

ITSC@DESKTOP-PMHM7D7 MINGW64 /e
$ ls
'$RECYCLE.BIN'/ HTML/ project.txt 주말*3_token.txt
'@!dmJPb'/ javascript*영상/ 'System Volume Information'/ 주말\_frontend_1/
FOUND.000/ new_node/ '새 폴더'/ 주말\_frontend_2/  
 frontend_2/ project/ '새 폴더2'/ 주말\_frontend_3/

ITSC@DESKTOP-PMHM7D7 MINGW64 /e
$ cd 주말\_frontend_3

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3
$ ls
day01_1223/ day03_1230/ '주말\_frontend_3 (2).zip'

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230
$ git init
Initialized empty Git repository in E:/주말\_frontend_3/day03_1230/.git/

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230
$ git add .
fatal: detected dubious ownership in repository at 'E:/주말\_frontend_3/day03_1230'  
'E:/주말\_frontend_3/day03_1230' is on a file system that does not record ownership  
To add an exception for this directory, call:

        git config --global --add safe.directory 'E:/주말_frontend_3/day03_1230'

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230
$ git config --global --add safe.directory 'E:/주말\_frontend_3/day03_1230'

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git add .

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)
new file: index.html

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)
new file: index.html

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git commit -m "git commit test"
Author identity unknown

\*\*\* Please tell me who you are.

Run

git config --global user.email "you@example.com"
git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ITSC@DESKTOP-PMHM7D7.(none)')

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git config --global user.email "jemicom@gmail.com"

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git config --global user.name "jemicom"

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git commit -m "git commit test"
[master (root-commit) cf865f1] git commit test
1 file changed, 16 insertions(+)
create mode 100644 index.html

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git status
On branch master
nothing to commit, working tree clean

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git log
commit cf865f161a3a2542de8fa3ccae9194d1a59af7a4 (HEAD -> master)
Author: jemicom <jemicom@gmail.com>
Date: Sat Dec 30 13:44:53 2023 +0900

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git log
commit 83083076c724368735d6f600c21c5cb944910ba5 (HEAD -> master)
Author: jemicom <jemicom@gmail.com>
Date: Sat Dec 30 13:47:53 2023 +0900

    div 추가

commit cf865f161a3a2542de8fa3ccae9194d1a59af7a4
Author: jemicom <jemicom@gmail.com>
Date: Sat Dec 30 13:44:53 2023 +0900

    git commit test

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ ls -a
./ ../ .git/ index.html

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git branch -M master

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git remote add origin https://github.com/jemicom/week_day_03.git

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git push -u origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 867 bytes | 433.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0  
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/jemicom/week_day_03.git

- [new branch] master -> master
  branch 'master' set up to track 'origin/master'.

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git log
commit 83083076c724368735d6f600c21c5cb944910ba5 (HEAD -> master, origin/master)  
Author: jemicom <jemicom@gmail.com>
Date: Sat Dec 30 13:47:53 2023 +0900

    div 추가

commit cf865f161a3a2542de8fa3ccae9194d1a59af7a4
Author: jemicom <jemicom@gmail.com>
Date: Sat Dec 30 13:44:53 2023 +0900

    git commit test

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git add .

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git commit -m "한글 수정하여 추가"
[master 63f08b2] 한글 수정하여 추가
1 file changed, 4 insertions(+), 6 deletions(-)

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$ git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 351 bytes | 351.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/jemicom/week_day_03.git
8308307..63f08b2 master -> master
branch 'master' set up to track 'origin/master'.

ITSC@DESKTOP-PMHM7D7 MINGW64 /e/주말\_frontend_3/day03_1230 (master)
$
