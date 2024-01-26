#comando utiles de Git
#cuando se hace una modificacion se tiene que hacer de nuevo Git add. y git add commit
#rama-heroe es el nombre de la rama
1. git init
2. git add . ()
3. git reset . (revierte todo lo que hace el git add)
4. git commit -m "PRIMERA VERSION"()
5. git checkout --. (Regresa todos los archivos hasta el ultimo comit realizado)
6. git log (listados de los Comit)
7. git commit --amend (sirve para corregir los nombres de los comit, luego presionamos la letra Y para modificar o agregar nuevo texto, para salir es ESC :wq!)
8. git checkout -b (rama-heroes) <=(nombre de la rama) (crea una rama secundaria a partir del ultimo comit realizado)
8. git checkout (nombre de la rama) te lleva a la rama que has colocado
9. git branch (te muestra todas las ramas)
10. git checkout master (te lleva a la rama master o principal)
11. git merge (nombre de la rama)( fusiona la rama con la rama principal)
12. git branch -d rama-heroes
13. git push (sube los cambios al repositorio de github)
14. git commit -am (sirve para hacer el git add y git commit de forma simultanea)