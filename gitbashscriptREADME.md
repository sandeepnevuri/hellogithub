



Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub/gitproject (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   alpha
        new file:   alphat
        new file:   ../scribble

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../sandeepp/


Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub/gitproject (main)
$ git add *

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub/gitproject (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   alpha
        new file:   alphat
        new file:   ../scribble

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../sandeepp/


Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub/gitproject (main)
$ cd ..

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git add *

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   gitproject/alpha
        new file:   gitproject/alphat
        new file:   sandeepp/WEB-NOTE-GROUP-I-CORRIGENDUM20220521205858.pdf
        new file:   scribble


Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git commit -m "firstcommit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Shyam Kumar@DESKTOP-0RSTV2B.(none)')

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ ^C

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git config --global user.email "sandeepnevuri@gmail.com"

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$  git config --global user.name "sandeepnevuri"

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git commit -m "firstcommit"
[main e5fc91b] firstcommit
 4 files changed, 6 insertions(+)
 create mode 100644 gitproject/alpha
 create mode 100644 gitproject/alphat
 create mode 100644 sandeepp/WEB-NOTE-GROUP-I-CORRIGENDUM20220521205858.pdf
 create mode 100644 scribble

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 183.78 KiB | 7.35 MiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/sandeepnevuri/hellogithub.git
   1e8467f..e5fc91b  main -> main

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git pull
Already up to date.

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git fetch

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git pull
Already up to date.

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git add *


Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$


Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git fetch
From https://github.com/sandeepnevuri/hellogithub
 * [new branch]      feature1   -> origin/feature1

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git branch
* main

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (main)
$ git checkout feature1
Switched to a new branch 'feature1'
D       sandeepp/WEB-NOTE-GROUP-I-CORRIGENDUM20220521205858.pdf
branch 'feature1' set up to track 'origin/feature1'.

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature1)
$ git pull
Already up to date.

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature1)
$ git add *

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature1)
$ git commit -m "feature"
[feature1 05007a8] feature
 1 file changed, 3 insertions(+)

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature1)
$ git push origin feature1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 392 bytes | 130.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/sandeepnevuri/hellogithub.git
   e5fc91b..05007a8  feature1 -> feature1

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature1)
$ git fetch
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 622 bytes | 16.00 KiB/s, done.
From https://github.com/sandeepnevuri/hellogithub
 * [new branch]      feature2   -> origin/feature2
   e5fc91b..9b666e2  main       -> origin/main

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature1)
$ git branch
* feature1
  main

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature1)
$ git checkout feature2
Switched to a new branch 'feature2'
D       sandeepp/WEB-NOTE-GROUP-I-CORRIGENDUM20220521205858.pdf
branch 'feature2' set up to track 'origin/feature2'.

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature2)
$ git pull
Already up to date.

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature2)
$ git add *

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature2)
$ git commit -m "feature1"
[feature2 f8ea1d0] feature1
 1 file changed, 3 insertions(+), 1 deletion(-)

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature2)
$ git push origin feature2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 401 bytes | 200.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/sandeepnevuri/hellogithub.git
   9b666e2..f8ea1d0  feature2 -> feature2

Shyam Kumar@DESKTOP-0RSTV2B MINGW64 ~/OneDrive/Desktop/Sandeep/project/hellogithub (feature2)
$ git checkout feature2
