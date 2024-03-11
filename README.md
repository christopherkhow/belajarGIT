Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

Christopher khow@LAPTOP-MNUIT3EF MINGW64 ~
$ cd "D:\Sem 4"

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4
$ git clone https://github.com/christopherkhow/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4
$ cd belajarGIT

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-git)
$ Touch Tugas-Git.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-git)
$ git commit -m "menambahkan Tugas-Git.txt"
[Tugas-git 34137f7] menambahkan Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git merge Tugas-git
Updating 1512251..34137f7
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 155.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/christopherkhow/belajarGIT.git
   1512251..34137f7  main -> main

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-html)
$ git commit -m "menambahkan Tugas-Html.txt"
[Tugas-html f0a4a84] menambahkan Tugas-Html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git merge Tugas-html
Updating 34137f7..f0a4a84
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 340 bytes | 113.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/christopherkhow/belajarGIT.git
   34137f7..f0a4a84  main -> main

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-css)
$ git commit -m "menambahkan Tugas-Css.txt"
[Tugas-css 36df3b8] menambahkan Tugas-Css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git merge Tugas-css
Updating f0a4a84..36df3b8
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 361 bytes | 180.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/christopherkhow/belajarGIT.git
   f0a4a84..36df3b8  main -> main

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-js)
$ git commit -m "menambahkan Tugas-Js.txt"
[Tugas-js 4f6a07d] menambahkan Tugas-Js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git merge Tugas-js
Updating 36df3b8..4f6a07d
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/christopherkhow/belajarGIT.git
   36df3b8..4f6a07d  main -> main

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-midProject)
$ touch Tugas-MidProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-midProject)
$ git commit -m "menambahkan Tugas-MidProject.txt"
[Tugas-midProject 81a3f4c] menambahkan Tugas-MidProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git merge Tugas-midProject
Updating 4f6a07d..81a3f4c
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 308 bytes | 308.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/christopherkhow/belajarGIT.git
   4f6a07d..81a3f4c  main -> main

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php 7f73706] Menambahkan Tugas-Php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git merge Tugas-php
Updating 81a3f4c..7f73706
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/christopherkhow/belajarGIT.git
   81a3f4c..7f73706  main -> main

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ touch Tugas-Finalproject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
On branch Tugas-finalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Finalproject.txt

nothing added to commit but untracked files present (use "git add" to track)

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
On branch Tugas-finalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Finalproject.txt

nothing added to commit but untracked files present (use "git add" to track)

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
On branch Tugas-finalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Finalproject.txt

nothing added to commit but untracked files present (use "git add" to track)

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ ^C^C

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ ^C

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git checkout -b Tugas-finalProject
fatal: a branch named 'Tugas-finalProject' already exists

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git add Tugas-Final-FinalProject.txt
fatal: pathspec 'Tugas-Final-FinalProject.txt' did not match any files

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git checkout -b Tugas-FinalProject
fatal: a branch named 'Tugas-FinalProject' already exists

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git branch -D Tugas-Final-Project
error: branch 'Tugas-Final-Project' not found

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git branch -D Tugas-FinalProject
Deleted branch Tugas-FinalProject (was 7f73706).

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-finalProject)
$ git checkout -b Tugas-FinalProject
Switched to a new branch 'Tugas-FinalProject'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-FinalProject)
$ touch Tugas-FinalProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-FinalProject)
$ git branch -D Tugas-FinalProject
error: cannot delete branch 'Tugas-FinalProject' used by worktree at 'D:/Sem 4/belajarGIT'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-FinalProject)
$ git branch -D Tugas-FinalProject
error: cannot delete branch 'Tugas-FinalProject' used by worktree at 'D:/Sem 4/belajarGIT'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-FinalProject)
$ git branch -D Tugas-FinalProject
error: cannot delete branch 'Tugas-FinalProject' used by worktree at 'D:/Sem 4/belajarGIT'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-FinalProject)
$ ^C

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-FinalProject)
$ git branch -d Tugas-FinalProject
error: cannot delete branch 'Tugas-FinalProject' used by worktree at 'D:/Sem 4/belajarGIT'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-FinalProject)
$ git branch -D Tugas-FinalProject
error: cannot delete branch 'Tugas-FinalProject' used by worktree at 'D:/Sem 4/belajarGIT'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-FinalProject)
$ git checkout -b Tugas-FinalProject
Switched to a new branch 'Tugas-FinalProject'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-FinalProject)
$ git checkout -b Tugas-Finalproject
Switched to a new branch 'Tugas-Finalproject'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-Finalproject)
$ touch Tugas-FinalProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-Finalproject)
$ git add Tugas-FinalProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-Finalproject)
$ git  commit -m "Menambahkan Tugas-Finalproject.txt"
[Tugas-Finalproject (root-commit) 7ad3b53] Menambahkan Tugas-Finalproject.txt
 8 files changed, 16 insertions(+)
 create mode 100644 README.md
 create mode 100644 Tugas-Css.txt
 create mode 100644 Tugas-FinalProject.txt
 create mode 100644 Tugas-Git.txt
 create mode 100644 Tugas-Html.txt
 create mode 100644 Tugas-Js.txt
 create mode 100644 Tugas-MidProject.txt
 create mode 100644 Tugas-Php.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-Finalproject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git merge Tugas-Finalproject
fatal: refusing to merge unrelated histories

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git branch -D Tugas-FinalProject
Deleted branch Tugas-FinalProject (was 7ad3b53).

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git checkout -b Tugas-Finalproject
Switched to a new branch 'Tugas-Finalproject'

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-Finalproject)
$ touch Tugas-FinalProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-Finalproject)
$ git add Tugas-FinalProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-Finalproject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-Finalproject 789960e] Menambahkan Tugas-FinalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (Tugas-Finalproject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git merge Tugas-Finalproject
Updating 7f73706..789960e
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 102.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/christopherkhow/belajarGIT.git
   7f73706..789960e  main -> main

Christopher khow@LAPTOP-MNUIT3EF MINGW64 /d/Sem 4/belajarGIT (main)
$
