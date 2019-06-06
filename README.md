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
git commit --amend --author="Alex Villecco <alex.villecco@globant.com>"
``` 
# -------------------------------------------------------------------
# Como actualizar un repo forkeado

# Add the remote, call it "upstream":
git remote add upstream https://github.com/whoever/WHATEVER.git

# Fetch all the branches of that remote into remote-tracking branches,
# such as upstream/master:
git fetch upstream

# Make sure that you're on your master branch:
git checkout master

# Rewrite your master branch so that any commits of yours that
# aren't already in upstream/master are replayed on top of that
# other branch:
git rebase upstream/master

# -------------------------------------------------------------------
# GIT Invalid User Name
``` bash
$ git config --global --unset credential.helper manager
//and reset the Username and password
```
# -------------------------------------------------------------------
Revert git pull branch-2 in branch-1 unintentionally. (branch-1|MERGING)

$ git reset HEAD
$ git clean  -d  -f .

# -------------------------------------------------------------------

# -------------------------------------------------------------------

# -------------------------------------------------------------------

# -------------------------------------------------------------------

# -------------------------------------------------------------------

# -------------------------------------------------------------------

