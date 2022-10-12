# Github assignment

1. Made new Repository in Github named Reza_GitAndGithub
   Copied the Repository Link.
2. sreza@REZA MINGW64 ~ (master)
   $ git clone https://github.com/sreza30th/Reza_GitAndGithub.git
   Cloning into 'Reza_GitAndGithub'...
   warning: You appear to have cloned an empty repository.

3. sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
   $ git log -oneline
   fatal: your current branch 'main' does not have any commits yet

4. sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
   $ touch Git.txt

sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
$ touch Github.txt


5. sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
   $ nano Git.txt

sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
$ nano Github.txt
6. Added README.md file by nano.README.md command and added the steps.git

7. $ git status
   On branch main

No commits yet

Untracked files:
(use "git add <file>..." to include in what will be committed)
Git.txt
Github.txt
README.md

nothing added to commit but untracked files present (use "git add" to track)

8. sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
   $ git push -u origin main
   Enumerating objects: 5, done.
   Counting objects: 100% (5/5), done.
   Delta compression using up to 8 threads
   Compressing objects: 100% (5/5), done.
   Writing objects: 100% (5/5), 885 bytes | 885.00 KiB/s, done.
   Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
   To https://github.com/sreza30th/Reza_GitAndGithub.git
* [new branch]      main -> main
  branch 'main' set up to track 'origin/main'.

9. sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
   $ mkdir temp

sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
$ cd temp

sreza@REZA MINGW64 ~/Reza_GitAndGithub/temp (main)
$ cp "C:\Users\sreza\Pictures\PictureDesktop.png" .

sreza@REZA MINGW64 ~/Reza_GitAndGithub/temp (main)
$ ls
PictureDesktop.png

10. sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
    $ touch .gitignore

11. sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
    $ touch temp >>.gitignore

12. $ git status
    On branch main
    Your branch is up to date with 'origin/main'.

Untracked files:
(use "git add <file>..." to include in what will be committed)
.gitignore
temp/

nothing added to commit but untracked files present (use "git add" to track)

13. $ git push -u origin main
    Enumerating objects: 6, done.
    Counting objects: 100% (6/6), done.
    Delta compression using up to 8 threads
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (5/5), 1.48 MiB | 3.27 MiB/s, done.
    Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
    To https://github.com/sreza30th/Reza_GitAndGithub.git
    869e489..d164107  main -> main
    branch 'main' set up to track 'origin/main'.

14. $ git branch
    differences
* main

sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
$ git checkout differences
Switched to branch 'differences'na

15. sreza@REZA MINGW64 ~/Reza_GitAndGithub (differences)
    $ nano Git.txt

sreza@REZA MINGW64 ~/Reza_GitAndGithub (differences)
$ nano Github.txt
(Added defination of git in Git.txt and defination of git in Git.txt)

16. sreza@REZA MINGW64 ~/Reza_GitAndGithub (differences)
    $ nano difference.txt
    (Added file name difference.txt and written difference
    between Git and Github)
17. README.md file updated by nano.README.md command

18. $ git status
    On branch differences
    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
    modified:   Git.txt
    modified:   Github.txt
    modified:   README.md