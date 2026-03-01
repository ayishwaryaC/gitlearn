## git add -> git commit -> git push :)

## git add gitlearn1.txt 

## git commit -m "gitlearn1.txt added"

## git push origin main -----  main branch 

PS C:\Users\ayishwaryac\Documents\github command learning> cd gitlearn
PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> git add gitlearn1.txt
fatal: pathspec 'gitlearn1.txt' did not match any files
PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> 
PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> git add gitlearn1.txt
PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> git command - m "gitlearn1.txt added"
git: 'command' is not a git command. See 'git --help'.
PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> git commit -m "gitlearn1.txt added"
[main (root-commit) 5bb9d29] gitlearn1.txt added
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 gitlearn1.txt

PS C:\Users\ayishwaryac\Documents\github command learning\gitlearn> git push origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 220 bytes | 220.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ayishwaryaC/gitlearn.git
 * [new branch]      main -> main

## git pull           -----   pull to git repository 

PS C:\Users\ayiahwaryac\Documents\github command learning\gitlearn> git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 1.02 KiB | 104.00 KiB/s, done.
From https://github.com/ayishwaryaC/gitlearn
   5bb9d29..ffc52fc  main       -> origin/main
Updating 5bb9d29..ffc52fc
Fast-forward
 gitlearn2.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 gitlearn2.txt


## Git branch :)

PS C:\Users\ayishwarya\Documents\github command learning\gitlearn> git branch 
* main
PS C:\Users\ayishwarya\HEGURU\Documents\github command learning\gitlearn> 

## Git barnch name to change  :)

PS C:\Users\ayishwarya\Documents\github command learning\gitlearn> git branch -m master
PS C:\Users\ayishwarya\Documents\github command learning\gitlearn> git branch 
* master
PS C:\Users\ayishwarya\Documents\github command learning\gitlearn>



