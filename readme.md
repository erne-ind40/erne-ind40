hola mundo

ya llegue.
Run
       CREDENCIALES
  git config --global user.email "you@example.com"
to set your account's default identity.
Omit --global to set the identity only in this repository.
PS C:\Users\PILARES\Desktop\repositorio> git config --global user.name "erne"     
PS C:\Users\PILARES\Desktop\repositorio> git commit -m "mi primer commit"
[master (root-commit) 6ab0e4b] mi primer commit
 1 file changed, 1 insertion(+)
 create mode 100644 readme.md

PS C:\Users\PILARES\Desktop\repositorio> git branch -M main
PS C:\Users\PILARES\Desktop\repositorio> git branch        
* main
.git
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Writing objects: 100% (3/3), 217 bytes | 217.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/erne-ind40/erne-ind40.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\PILARES\Desktop\repositorio> git add readme
fatal: pathspec 'readme' did not match any files
PS C:\Users\PILARES\Desktop\repositorio> git add readme.md
PS C:\Users\PILARES\Desktop\repositorio> git commit -m "segundo comit"
[main 5eefa49] segundo comit
 1 file changed, 3 insertions(+), 1 deletion(-)
PS C:\Users\PILARES\Desktop\repositorio> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 261 bytes | 261.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/erne-ind40/erne-ind40.git
   6ab0e4b..5eefa49  main -> main
PS C:\Users\PILARES\Desktop\repositorio>