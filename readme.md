## git add -> git commit -> git push :)

## git add gitlearn1.txt 

## git commit -m "gitlearn1.txt added"

## git push origin main -----  main branch 

- PS C:\Users\ayishwaryac\Documents\github command learning> cd gitlearn
- PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> git add gitlearn1.txt
- fatal: pathspec 'gitlearn1.txt' did not match any files
- PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> 
- PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> git add gitlearn1.txt
- PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> git command - m "gitlearn1.txt added"
git: 'command' is not a git command. See 'git --help'.
- PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> git commit -m "gitlearn1.txt added"
[main (root-commit) 5bb9d29] gitlearn1.txt added
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 gitlearn1.txt

 ---
 
- PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> git push origin main
- info: please complete authentication in your browser...
- Enumerating objects: 3, done.
- Counting objects: 100% (3/3), done.
- Writing objects: 100% (3/3), 220 bytes | 220.00 KiB/s, done.
- Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
- To https://github.com/ayishwaryaC/gitlearn.git
 * [new branch]      main -> main

---
## git pull           -----   pull to git repository 

- PS C:\Users\ayiahwaryac\Documents\github command learning\gitlearn> git pull
- remote: Enumerating objects: 4, done.
- remote: Counting objects: 100% (4/4), done.
- remote: Compressing objects: 100% (3/3), done.
- remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
- Unpacking objects: 100% (3/3), 1.02 KiB | 104.00 KiB/s, done.
- From https://github.com/ayishwaryaC/gitlearn
   5bb9d29..ffc52fc  main       -> origin/main
   
- Updating 5bb9d29..ffc52fc
- Fast-forward
 gitlearn2.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 gitlearn2.txt

---
## Git branch :)

- PS C:\Users\ayishwarya\Documents\github command learning\gitlearn> git branch 

* main

- PS C:\Users\ayishwarya\HEGURU\Documents\github command learning\gitlearn> 

---
## Git branch name to change  :)

- PS C:\Users\ayishwarya\Documents\github command learning\gitlearn> git branch -m master
- PS C:\Users\ayishwarya\Documents\github command learning\gitlearn> git branch 

* master
  
- PS C:\Users\ayishwarya\Documents\github command learning\gitlearn>

---
## new branch created on repository 
First create main branch to add another branch - ex : main2 (branch created)


- PS C:\Users\ayishwaryaC\Documents\github command learning\gitlearn> git branch -a
* master
-  remotes/origin/HEAD -> origin/main
- remotes/origin/main
- PS C:\Users\ayishwaryaC\Documents\github command learning\gitlearn> git pull 
- remote: Enumerating objects: 16, done.
- remote: Counting objects: 100% (16/16), done.
- remote: Compressing objects: 100% (15/15), done.
- remote: Total 15 (delta 7), reused 0 (delta 0), pack-reused 0 (from 0)
- Unpacking objects: 100% (15/15), 5.53 KiB | 108.00 KiB/s, done.
- From https://github.com/ayishwaryaC/gitlearn

   ffc52fc..bbff581  main       -> origin/main
   
 * [new branch]      main2      -> origin/main2
   
Updating ffc52fc..bbff581

Fast-forward

 readme.md | 61 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 
 1 file changed, 61 insertions(+)
 
 create mode 100644 readme.md
- PS C:\Users\ayishwaryaC\Documents\github command learning\gitlearn> git branch -a
* master
- remotes/origin/HEAD -> origin/main
- remotes/origin/main
- remotes/origin/main2
- PS C:\Users\ayiahwaryaC\Documents\github command learning\gitlearn> 

- HERE - git branch -a -> list the branch the code avaibale 
     - now in my repository i created branch as main2 
     -  now i enter the command on terminal - git branch -a (it doent shown )
     -  now to use git pull
     -  then again you put cmd - git branch -a 
     -  IT SHOWS ->  main and main2
     -  * master - > represent as current branch i using .
---
IF I WANT TO MOVE BRANCH AS main2 , to use below cmd 



- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> git checkout main2
- branch 'main2' set up to track 'origin/main2'.
- Switched to a new branch 'main2'
- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> git branch   
- * main2
-  master
- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> 

now the * main2 represent as we are in main2 branch .

---
## Here i added new file on my folder as gitlearn3.txt 
- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> git status
- On branch main2
- Your branch is up to date with 'origin/main2'.

- Untracked files:
-  (use "git add <file>..." to include in what will be committed)
        gitlearn3.txt

- nothing added to commit but untracked files present (use "git add" to track)
- PS C:\Users\HEGURU\Documents\github command learning\gitlearn>


<img width="450" height="450" alt="image" src="https://github.com/user-attachments/assets/269ba71c-3cc5-4258-a6cf-d73462144100" />

---
here the U - denotes Untracked 
Now to change as A - Added

<img width="450" height="450" alt="image" src="https://github.com/user-attachments/assets/b481bd5d-6469-478e-9d43-4a0d5670ff62" />

- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> git status
On branch main2
Your branch is up to date with 'origin/main2'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        gitlearn3.txt

nothing added to commit but untracked files present (use "git add" to track)
- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> git add gitlearn3.txt
- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> 


- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> git add gitlearn3.txt
- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> git commit -m "gitlearn3.txt added new file"
[main2 cbcaad0] gitlearn3.txt added new file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 gitlearn3.txt


- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> git push origin main2
- Enumerating objects: 3, done.
- Counting objects: 100% (3/3), done.
- Delta compression using up to 12 threads
- Compressing objects: 100% (2/2), done.
- Writing objects: 100% (2/2), 245 bytes | 245.00 KiB/s, done.
-  Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
- remote: Resolving deltas: 100% (1/1), completed with 1 local object.
- To https://github.com/ayishwaryaC/gitlearn.git
   bbff581..cbcaad0  main2 -> main2
- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> 




- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> git commit -m " created new file in new branch" 
- On branch main2
- Your branch is up to date with 'origin/main2'.
nothing to commit, working tree clean
- PS C:\Users\HEGURU\Documents\github command learning\gitlearn> git push origin main2
Everything up-to-date
