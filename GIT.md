# curso de git

## comandos basicos

* `git help`  ayuda

* `git config--global -e`  editar el archivo global de git

* `git config --global user. user "Miguel"`  estableser nombre de usuario global para git

* `git config --global user. email "Miguel@girasolo.com"` estableser un correo global para git

* `git init ` inicializar una carpeta como un proyecto de git

* `git add . ` agregar todos los archivos para que este al pendiente de los cambios

* `git commit -m "Mensage"`  hacer un esnapshot del estado actual de los archivos

* `git checkout -- . ` reconstruye el proyecto a como estaba en el ultimo commit

* `git add -A` incluir todos los archivos modificados

* `git reset 'nombreArchivo'` //para excluir un archivo de el repositorio

* `git add "*.txt"` agrega todos los txt del TODO el proyecto

* `git add *.txt` agrega todos los txt en el directorio actual

* `git add -all` incluir todos los archivos

* `git add pdfs/*.pdf`  incluir todos los archivos de la carpeta pdfs

* `git add pdfs/`  para incluir todos los archivos dentro de esa carpeta

* `git log --oneline --decorate --all --graph`

* `git status -s` para mostrar solo los archivos que han sido modificados

* `git diff` para saber que fue loque se modifico o es lo que esta diferente

* `git diff --staged` para diferenciar lo que esta diferente en los archivos del esenario

* `git reset HEAD README.md` es para sacar un archivo del stage

* `git commit --amend -m "Actualizamos README.md"` actualizar mensage del commit

* `git reset --soft HEAD^` desaser ultimo commit

* `git reset --soft 252565` ir aun commit en especifico

* `git reset --mixed` quitar arcivos de el staged pero conservando sus modificaciones

* `git reflog` vet todods los comit hechos y desechos

* `git mv nombre_actual nombre_nuevo` renombrar un archivo

* `git rm nombre_archivo` eliminar archivo

* `git add -u` agregar un archivo renombrado

* `git branch nombrerama` crear una nueva rama

* `git checkout nombre de la rama` cambiar de rama

* `git merge nombre rama` unir rama con rama master

* `git branch -d nombre rama` borrar rama

* `git checkout -b nombre rama` crear una rama y moverte a ella al instante

* `git tag nombre tag` se crea un tag

* `git tag -d nombreTag` borrar tag

* `git push --tags` Subir tags al repositorio hosteado (GitHub)

* `git stash` guardar cambios sin usar commit y dejarlos archivos como en el ultimo commit

* `git stash pop` recuperar los cambios en el stash

* `git stash drop` borrar los stach

* `git revase` actualizar una rama con lo ultimo de master

* `git remote -v` ver la conexion a git hub

* `git remote add origin " ruta del repo " ` agregar un repo remoto al proyecto

* `git pull origin master` bajar cambios de un repo remoto al cual ya esta vinculado el proyecto

* `git push origin master` subir cambios al repo remoto

