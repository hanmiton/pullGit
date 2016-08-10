1.- Fork
2.- Añadir los remote
	git remote add origin ..........
	git remote add upstream ...........
2.- Actualziar cambios
	git fetch upstream
	git merge upstream/master
	ó
	git pull upstream master
3.- Ver cambios antes de subir a origin
	git fecth upstream
	/si hay cambios hacer el merge(fusion)
	git push origin master
git Tags
	son como commits abanderados
		annotated tags
		lightweight tags
git tag -a [version] -m  "mensaje"
	git checkout <tag>
tag sin mensaje
	git [version]
enlistar tag
	git tag
ancestrales
	git tag -a [version] <commit anteior>

git push origin --tags

Git extras 
	es una extension dentro de git
Git for mac
	syc o publish (windows)
	se ahce un git pull y un git push
ZenHub
	Proyect Managment
icebox
	son ideas que se tienen
backlog
	lo mas importante por desarrrollar
inProgrees
	que se encuentran desarrollando
reviewQA
	revision antes de ir a master
Done
	que se sube a repositorio master
Burndown
	como tu vas ejecutnado los issues
GitLab
	repositorios pribados
	sustituye los bare repositories
	Pipelines
		se ejecutan otros comando al hacer un push
html5 up 
	para descargar plantillas de html5
poner un blog online con git
	git checkout -b gh-pages
	git push origin gh-pages
	edit
		http://hanmiton.github.io/blog
post
 	href="http://miguenieva.github.io/blog/holamundo.html"
