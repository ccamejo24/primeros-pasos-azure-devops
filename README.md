# Jugando con Git

 - Clonar un repositorio
 
`git clone [url-repositorio-remoto]`    

 - Agregar algunos ficheros

`git add [nombre-fichero]`

- Ver estado

`git status ` 

 - Hacer commit

`git commit -m "Mensaje commit" ` 

 - Enviar ficheros al repositorio remoto

`git push ` 

 - Crear dos branch (una desde consola y otra desde el portal)

`git branch "features/mi-rama2" ` 

o (para crearla y cambiarse a ella)

`git switch -c "features/mi-rama2" ` 

 - Obtener listado de todas las ramas remotas

`git pull ` 

 - Cambiar de branch

`git switch "features/mi-rama2" ` 

o

`git checkout "features/mi-rama2" ` 

 - Hacer cambios en ambas ramas
 - Hacer un merge de una y una pull request de la otra (resolver conflictos)
 
 `git merge [rama-ejemplo] `  

- Subir fichero secreto.txt por error
- Eliminarlo he ignorarlo para que no pase nuevamente
