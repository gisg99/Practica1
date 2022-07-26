# Practica 1
![Git y GitHub](https://camo.githubusercontent.com/38f113b96a368dfb7f634d2f2da97e7b8c748042d2a284b97c3fad048bb3ff55/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f323733322f312a6d74736b3366515f4252656d466964686b656c3364412e706e67 "Git y GitHub")
*En esta practica he aprendido a utilizar tanto Git como GitHub, merge, branches, push, pull y a trabajar en proyectos colaborando con muchas personas en GitHub.* :smile:

El "proyecto" de este repositorio es un simple blog de un equipo de futbol en el cual se anuncia una noticia :blue_heart:

#####  Aquí una lista de todo lo que he aprendido en el curso:
 
- [mkdir nombre_carpeta] Crear carpeta o directorio en Bash

- [touch archivo.arc] Crear archivo en Bash

- [code] Abrir VSCode

- [code archivo.arc] Abrir archivo determinado con VSCode

- [git init] Inicializar un repositorio de Git en el directorio actual

- [git config --list] Ver parametros de configuracion de Git

- [git config --list --show-origin] Ver rutas en donde hay configuraciones

- [git status] Ver el estado actual del repositorio, para saber si hay archivos sin guardar, sin trackear o modificados

- [git add archivo.arc] Trackear un archivo para que Git lo agregue a la lista del repositorio

- [git add .] Trackear todos los archivos y carpetas dentro del directorio actual

- [git commit -m "Mensaje"] Guardar todos los cambios del staging en el disco

- [git commit -am "Mensaje"] Guardar todos los cambios en el disco sin necesidad de añadirlos antes al staging, solo funciona si no hay archivos nuevos

- [git log archivo.arc] Ver los commits que se han hecho para determinado archivo del repositorio

- [git log] Ver los commits que se han hecho para todo el repositorio

- [git rm --cached archivo.arc] Borrar un archivo del staging pero no del disco, se puede usar cuando no queremos que el commit se ejecute para un solo archivo

- [git rm --force archivo.arc] Borrar un archivo tanto de la memoria temporal como del disco duro

- [git reset -soft hexacommit] El soft reset regresa el tiempo en el disco hasta cierto commit que le indiquemos pero mantiene el staging con los cambios actuales

- [git reset --hard hexacommit] El hard reset regresa el tiempo en el disco hasta cierto commit que le indiquemos borrando tanto los commits futuros en disco y los archivos en el staging

- [git checkout hexacommit] Mediante checkout podemos volver a una version anterior para hacer pruebas o cambios sin afectar a la version actual

- [git checkout nombre_rama] Ir de una rama a otra

- [git branch nombre_rama] Crear una copia exacta del commit mas reciente en otra rama

- [git show] Mostrar ultimos cambios

- [git merge nombre_rama] Combinar la rama en la que estamos  actualmente con la rama que indiquemos en el comando

- [git merge --abort] Abortar merge

- [git pull origin master] Traer desde un repositorio de GitHub los archivos a un repositorio local

- [git pull origin master --allow-unrelated-histories] Traer desde un repositorio de GitHub los archivos a un repositorio local ignorando que dichas historias no estén relacionada, esta opción se suele usar cuando vinculamos nuestros repositorios por primera vez

- [git push origin master] Enviar los archivos desde el repositorio local a el repositorio de GitHub indicado como origin

- [git clone https ://github.com/usuariopropietario/nombrerepositorio] Traer un repositorio desde GitHub a nuestra carpeta local y a la vez crear repositorio de Git en ese mismo directorio con dichos archivos
