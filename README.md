# GIT
#### Comandos basicos de git
```
git init
git status //muestra el estado del area de trabajo
git add -A //añade todo
git add . //añade todo
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
#### Ejercicios
```
git add index.html
git commit -m "primera version"
//despues de apartar el contenido css en un fichero aparte
git branch estructura
git checkout estructura
// tambien se puede hacer las dos lineas anteriores juntos con git checkout -b estructura
git branch
git add index.html
git commit -m "estructura de ficheros y carpetas"
git branch galeria
git branch
git checkout galeria
git branch
git add index.html
git commit -m "modificación de bloques y galería"
git log
git log >> logs
git checkout master
git branch -D estructura
git branch -D galeria
git log
//Ejercicio 1
//Solo quedara registrado el commit hecho en master
//Ya estabas en la primera version, aunque si puedes volver
//He podido volver a la ultima version, ademas que en el log vuelve a aparecer el commit de esta version sin que mencione el branch galeria
/git status
//Ejercicio 4
git branch dev
git checkout dev
git add index.html
git commit -m "#2"
git checkout master
git merge dev
```

#### Bajar doc
```
git clone
```
