Vamos a codificar
2 linea
.
.
.
.
.
.
.
.
.
.
Como editar, cambiar nombre y que todo se guarde en en github.com
Sebastian Tregear
sebastian.tregear@L603-013 MINGW64 ~
$ pwd (ver en que carpeta estas)
/c/Users/sebastian.tregear

sebastian.tregear@L603-013 MINGW64 ~
$ cd helloword/(cambiar donde estas)(dir en cmd)

sebastian.tregear@L603-013 MINGW64 ~/helloword (master)
$ ls(ver que archivos hay en donde estoy)
readme

sebastian.tregear@L603-013 MINGW64 ~/helloword (master)
$ mv readme readme.md (cambiarle el nombre a la hoja de codigo)

sebastian.tregear@L603-013 MINGW64 ~/helloword (master)
$ git add readme.md (hacer cambios desde la computadora)

sebastian.tregear@L603-013 MINGW64 ~/helloword (master)
$ git commit -m "Agregando mi nombre" (crear ese cambio anterior)
[master 595ce9a] Agregando mi nombre
 1 file changed, 13 insertions(+)
 create mode 100644 readme.md

sebastian.tregear@L603-013 MINGW64 ~/helloword (master)
$ git push (cambio guardado)
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 333 bytes | 166.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/Taygerr/helloword.git
   36222ff..595ce9a  master -> master
   
sebastian.tregear@L603-013 MINGW64 ~/helloword (master)
$ git fetch(para ver si hay cambios en el servidor)
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/Taygerr/helloword
   595ce9a..f37f835  master     -> origin/master
   
   
   sebastian.tregear@L603-013 MINGW64 ~/helloword (master)
$ git pull (guardar esos cambios hechos desde el servidor a la computadora)
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/Taygerr/helloword
   f37f835..929894e  master     -> origin/master
Updating 595ce9a..929894e
Fast-forward
 readme.md | 49 ++++++++++++++++++++++++++++++++++++++++++++++++-
 1 file changed, 48 insertions(+), 1 deletion(-)

   

