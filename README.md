# Github-Codes.
-------------------------------------------------
A) git codes for Story (Version Control)-
-------------------------------------------------
1)Create Chapter1.txt and write something  in it
-------------------------------------------------
git init                                                                (initilizing)
git status                                                              (status)
git add .                                                               (adding to workspace)
git commit -m "Chapter 1"                                               (commit)
git log                                                                 (commit id)
-------------------------------------------------------------
2)Create Chapter2.txt and Chapter3.txt write something in it
-------------------------------------------------------------
git add .                                                               (adding to workspace)
git commit -m "Chapter 2 & 3"                                           (commit)
git log                                                                 (commit id)
-----------------------------------
3)change something in Chapter3.txt 
-----------------------------------
git checkout Chapter3.txt                                               (rollback to old commit id)
--------------------------------------
Codes to upload into remote repository
--------------------------------------
git remote add origin <url>
git branch -M main
git push -u origin main
-----------------------------------
