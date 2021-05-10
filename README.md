# Git

- Commits, que va a contener un conjunto de archivos y un mensaje / comentarios respecto a las modificaciones que se hicieron en el código y un usuario asignado. 

- Buenas prácticas de commits:
    - Atómicos
    - Descriptivos


## Añadir archivos

- git add nombreDelArchivo
- git add .

Con git add agrego archivos a una "canasta", a un grupo de archivos que van a ser commiteados, con los datos que tienen en ese momento.

## Commitear los archivos

Cada commit que se está armando debe tener un mensaje, para agregar el mensaje:
- git commit -m "mensaje"
Que agregará el mensaje a los archivos añadidos con git add (con los datos que tenían en ese momento)