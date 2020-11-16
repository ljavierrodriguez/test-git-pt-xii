### Comando para preparar archivos a guardar en el repositorio
    $ git add . 
    $ git add -A
    $ git add *home*
    $ git add index.html

### Comando para deshacer la preparacion de los archivos a guardar

    $ git rm --cached <file>

### Comando para guardar en el repositorio local

    $ git commit -m "Este es una prueba"
    $ git commit

### Comando para regresar un cambio despues de un commit

    $ git checkout <file>
    $ git checkout <branch>


### Comando para crear nueva rama y activarla
- crear la rama
    $ git branch <branch>
- activa la rama
    $ git checkout <branch> 
- crear y activar la rama
    $ git checkout -b <branch>


### Unir ramas con merge

    $ git merge <branch_origen> <branch_destino>
