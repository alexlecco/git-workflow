# descartar cambios y volver al ultimo commit estable en Github
``` bash
git stash
``` 

# limpiar el stash
``` bash
git stash clear
``` 

# descartar commits locales y volver al ultimo commit estable en Github
``` bash
git reset --hard origin/<branch_name>
``` 

# Volver temporalmente a un commit anterior
``` bash
git checkout [revision] .
git reset --hard;
``` 

# Cambiar el author del ultimo commit (cambiar de alexlecco24@gmail.com => alex.villecco@globant.com)
``` bash
git commit --amend --author="Author Name <alex.villecco@globant.com>"
``` 
