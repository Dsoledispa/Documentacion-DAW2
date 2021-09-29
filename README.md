# GIT
#### Comandos basicos de git
```
git init
git status //muestra el estado del area de trabajo
git add -A //añade todo
git add "filename"
git commit -m "message"
git log //muestra historial (id's) de commits
git show [commit]
```
#### Branches (ramas)
```
git branch //listado de ramos y en que rama estas
git branch "filename" // crear rama nueva
git checkout "branch name"
git branch -m old-branch new-branch //renombrar
git branch -d "branch name" //eliminar branch (tienes que estar fuera de rama)
git reset --hard "commit" //para volver en un punto anterior
git log >> logs //para crear un documento que contenga los logs
// si solo se pone un > se elimina el doc
```
#### Merge (fusion)
```
git merge oneCol (dentro de master)
```
#### Layout
```
git add index.html
git commit -m "primera version"
//despues de apartar el contenido css en un fichero aparte
git branch estructura
git checkout estructura
git branch
git add index.html
git commit -m "estructura de ficheros y carpetas"
git branch galeria
git branch
git checkout galeria
git branch
```
