#curso python Django

## Session 2
### GIT
* Clonar repositorio
'''
git clone git@github.com:ericsondbv/curso_python_django.git
'''
*configurar git
git config --global user.name "Ericson Briceño"
git config --global user.email edbv1984@gmail.com


crear el archivo .gitignore
touch .gitignore

* git status
para ver el cambio de nuestro repositorio

git status -u

para ver 

* para agregar a git

git add .   # para agregar todo desde la ruta actual en la que estoy

* para guardar cambios

git commit -m "first commit"

*para ver listado de cambios o commits

git log 

*descargar cambios a nuestro repositorio/cambios de equipo de trabajo
git pull
git pull origin maste

*para subir los cambios a nuestro repo
git push
git push origin master

* ver mis rutas remotas
git remote show 
git remote show origin

* listado de ramas de proyecto
git branch
* para crear rama
    git branch sesion2
* para cambiar de rama
git checkout sesion2

* para deshacer un cambio no agregado
git checkout --archivo modificado.txt

* para deshacer cambios ya agregado

git reset HEAD archivomoficado.txt

*ver lista de cambios

git diff archivomodificado.txt

*unir cambios de una rama a otra

ir a la rama destino y ejecutar --
git merge ramaorigen



### Instalar Django
### Configurar un proyecto Django
### Crear Modelos
### Crear un Administrador
