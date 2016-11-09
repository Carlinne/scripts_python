#Scripts de Python
=================================================

###Lista de comandos de Python
1. 
2. 
3. 


###Lista de comandos de Git
1. git tutorial config
2. Iniciar repositorio
git init
3. Checar estado del repo
git status
4. Agregar archivos
git add
nombreArchivo.Extension
5. Crear commit(Historial) del codigo
git commit -m "Descripcion"
6. Agregar repositorio remoto
git add remote origin 
master http://direcion/repo
7. Subir cambios por 1era vez 
git push -u origin master
8. Checar historial de cambios 
git log

##Páginas de Git
https://git-scm.com/docs/gittutorial
https://git-scm.com/downloads

##Comandos Usados
Comandos
git config --global user.name "Carlinne"
git config --global user.email carli.pacheco95@gmail.com
git init
git status
//Aparecen los 2 archivos creados
git add .gitignore
git add README.md
git status
//Los 2 archivos aparecen en verde 
git commit -m "Agregado Archivos Iniciales, .gitignore, README"
git log

Si se modifica un archivo, se guarda de la sig manera para que los datos se actualizen:

git add --all //Agregar archivos
git commit -m "Modificado Archivos iniciales" //Agregar historial
git push //Subir cambios