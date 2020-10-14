                               ** Apuntes de GitHub de Alejandro Mármol Muñoz**

Git : un sistema de control de versiones. Un software que permite registrar todo el historial de cambios de un proyecto.

Repositorio : proyecto que está siendo seguido por Git. Es decir, ya tiene un historial de Git en el que se estan registrando sus cambios.

Commit : cada uno de los cambios registrados en el historial de Git. Cada uno de los desarrolladores manda los commits de los cambios que ha hecho.

Working directory : donde se trabaja con todos los archivos 
  - git add
staying area : donde se agregan todos los archivos preparados para guardar       - git status para saber el espacio 
  - git commit                                                                     en el que estás
repository :  se crea una primera foto de la versión del código


Cómo subir los cambios
1. git add .
2. git commit -m "el cambio que has hecho"
3. git push

git log --oneline (te permite ver los commits que has hecho)
git retet --hard (el código del commit al que quieres retroceder u avanzar)

Cómo traer los cambios

git pull (mueve los datos del repositorio a la carpeta que ya está abierta; lo actualiza)
git clone http... (clona el repositorio)

Crear versiones con TAG

git tag version1.0 -m "Versión 1" : agrega la versión de nombre version1.0 con la descripción Versión 1
git push --tag