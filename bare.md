bare repositories
	solo tiene una area de repositorio
	no tiene ni working ni staging area
	se trabaja con ellso solo con pull y push
como crear un bare repositorio
	git init --bare repo.git (simpre temrian en .git)
server
	bare repositorio
local
	git clone ../server/repo.git repo (esto es en la maquina local)

local->server
	git push origin master
bare dentro del servidor
	Servidor
		creamos bare repository en servidor
	Local
		git clone <servidor>
		despues se ahce un git push con los cambios
	Servidor
		git clone repo.git deploy
		cd deploy(poniendo en producicon el proeycto)
		