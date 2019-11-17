
## Antonio Gonz�lez
 1. �Como se ve la versi�n de git?
	* git version
	* git status
	* git log
	* git commit
 2. �C�mo se comitea con mensaje largo?
	* git commit 
	* git commit -m
	* git commit -long_message
	* git commit -long
 3. �C�mo se a�ade contenido a la staging �rea?
 	* git commit
	* git pull 
	* git add
	* git push

Mar�a Jald�n Vargas
1. �Qu� comando es necesario para crear un repositorio?
 -git status
 -git add
 -git init
 -git config

2. Si deseas obtener una copia de un repositorio Git existente en GitHub, el comando que necesitas es :
 -git commit
 -git add
 -git log
 -git clone
3. �Cu�l es el comando utilizado para listar los cambios (commits) que han producido en el repositorio?
 -git init
 -git status
 -git tag
 -git log



Jorge Alonso L�pez

1 �Desde qu� tipos de repositorios se puede trabajar en Git?  
- Repositorios locales y remotos (Correcta)
- Repositorios locales
- Repositorios remotos
- Ninguna es correcta

2 �Cu�les de estas opciones no es un software de control de versiones?
- Git Hubb (Correcta)
- SVN
- Git
- Mercurial

3 �Con cu�les de estos comandos se muestra la diferencia entre las versiones?
- git log -p (Correcta)
- git log -stat
- git log commit
- git log

## Daniel Cano de Celis
 1. �Cu�l es el paso previo al commmit de un elemento?
 	* A�adir al stagging area mediante el comando git add.
 	* A�adir al stagging area mediante el comando git pull.
 	* A�adir al stagging area mediante el comando git touch.
 	* Ninguna de las respuestas anteriores es correcta.
 2. Dentro del c�digo hash generado en los commits, �Qu� parte de este indica el �ltimo commit realizado c�ando usas el commando git log --oneline?
 	* Los 7 �ltimos caracteres del c�digo hash.
 	* Los 7 primeros caracteres del c�digo hash.
 	* 7 caracteres de una parte aleatoria del c�digo hash.
 	* Ninguna de las anteriores, el c�digo hash no existe.
 3. �Qu� ocurre cuando en una misma rama dos o m�s usuarios realizan push simult�neamente sobre el mismo elemento/archivo/fichero?
 	* El m�s r�pido de Triana en pushear, aunque sea por un nanosegundo, es el que realiza el push.
 	* Git entra en conflicto y cancela todos los push.
 	* Git te solicita que pushees desde otra rama.
 	* Ningunta de las anteriores. Git peta y muere un gatito.


##CHRISTIAN PAYO PARRA
1. �QUE COMANDO DEBEMOS UTILIZAR PARA ACTUALIZAR LO PUSHEADO EN EL REPOSITORIO?
*GIT PULL
*GIT COMMIT 
*GIT LOG 
*GIT IGNORE

2.�CUAL ES LA MEJOR FORMA DE TRABAJAR VARIAS PERSONAS CON EL MISMO REPOSITORIO?
*HACIENDO USO DE LAS RAMAS 
*PONIENDOSE DE ACUERDO DE CUANDO HACER PULL Y PUSH
*TRABAJANDO EN FICHEROS DIFERENTES
*NO TRABAJANDO EN EQUIPO

3.�QUE OCURRE CUANDO DOS PERSONAS PUSHEAN EL MISMO ARCHIVO A LA VEZ?
*GIT DA UN ERROR QUE HAY QUE SOLUCIONAR
*GIT CAMBIA EL NOMBRE A UNO DE LOS ARCHIVOS
*GIT PRIORIZA EL DEL DUE�O DEL REPOSITORIO
*AMBOS QUEDAN ELIMINADOS 

##Carlos Gonz�lez Lozano
1.�Qu� comando se usa para subir las modificaciones al repositorio remoto?
V-git push
-git pull
-git putt
-git add

2.�C�mo se a�aden todos los archivos no trackeados al repositorio?
V-git add .
-git add *
-git add $
-git add -all

3.�Qu� formato hay que poner en git log --pretty= para obtener email del confirmador?
V-%ce
-%ae
-$ce
-$ae

4.�C�mo se ve tu configuracion de git?
V-git config --list
-git config -all
-git config --global
-git config -global

<<<<<<< HEAD
##Alejandro Ram�rez Ramos

1.-Creo que he configurado mal mi usuario de git en cmander. �C�mo lo compruebo?

*git config --global user.name "user"
*git status
*git config --user
*git config --list

2.-Este fin de semana he estado sin internet hasta hoy Lunes. El ordenador lleva encendido desde el viernes
porque no me acuerdo de los comandos que tengo que poner para guardarlos y subirlos a github. �Cu�les eran?
(los ";" son separadores de comandos)

*git add . ; git commit ; git pull ;
*git commit ; git push ;
*git pull --all ;
*git add . ; git commit ; git push ;

3.-Mi amigo Luis estaba trabajando conmigo en un repositorio de git, y no s� si esta ma�ana ha hecho cambios
en algo o no. �C�mo lo miro?

*git pull
*git push
*git info --"nombreRepositorio"
*git log
=======

## Teresa D�az Ayuga
1. �Cu�l es el comando para ver los commits del repositorio en una sola l�nea?
	* git log -oneline
	* git log
	* git status
	* git help

2. Si vamos a hacer push y no nos deja porque no est�n actualizados los ficheros, �qu� tenemos que hacer primero?
	* git pull
	* git add
	* git commit
	* git init

3. �Qu� comando se usa papara a�adir todos los ficheros de un repositorio?
	* git add .
	* git add
	* git add fichero
	* git add --fichero
>>>>>>> b702c735ff593a2b706ca4742e00c6df7968820d

##Alejandro Ram�rez Ramos

1.-Creo que he configurado mal mi usuario de git en cmander. �C�mo lo compruebo?

*git config --global user.name "user"
*git status
*git config --user
*git config --list

2.-Este fin de semana he estado sin internet hasta hoy Lunes. El ordenador lleva encendido desde el viernes
porque no me acuerdo de los comandos que tengo que poner para guardarlos y subirlos a github. �Cu�les eran?
(los ";" son separadores de comandos)

*git add . ; git commit ; git pull ;
*git commit ; git push ;
*git pull --all ;
*git add . ; git commit ; git push ;

3.-Mi amigo Luis estaba trabajando conmigo en un repositorio de git, y no s� si esta ma�ana ha hecho cambios
en algo o no. �C�mo lo miro?

*git pull
*git push
*git info --"nombreRepositorio"
*git log

PABLO GONZ�LEZ GONZ�LEZ

1. �Qu� haces cuando quieres realizar un commit con un comentario largo?
	* git commit -m "comentario"
	* git commit
	* git commit -l 
	* git commit ""

2. �Cu�les son los pasos para subir los proyectos Javas a tu repositorio de GitHub?
	* commit and push
	* add to index and push
	* add to index, commit
	* add to index, commit and push

3. �Qu� maneras son correctas para a�adir archivos al staging area?
	* git add .
	* git add "nombrerchivo"
	* Todas son correctas
	* Todas son incorrectas

AINARA GIL EGEA 
1.	�C�mo almacena Git sus datos?
	a)Maneja sus datos como un conjunto de copias instant�neas de un sistema de archivos miniatura. 
	b)Almacena la informaci�n como una lista de cambios en los archivos. 
	c)Guarda nuevos documentos por cada modificaci�n realizada por el usuario.
	d)Ninguna es correcta.

2.	Git tiene tres estados principales en los que se pueden encontrar tus archivos: 
	a)Confirmado, modificado y preparado.
	b)Confirmado, cambiado y terminado.
	c)Preparado, cambiado y terminado.
	d)Modificado, preparado y final. 

3.	Pasos a seguir para confirmar y subir tus cambios:
	a)Git add .   , git commit �m , git push
	b)Git push , git commit �m, git add . 
	c)Git status, git push, git diff
	d)Git commit �m, git pull, git push.

4.	�Cu�l es el comando para eliminar archivos?
	a)Git rm
	b)Git push
	c)Git log
	d)Git commit 

Francisco Javier Garcia Lara
1.	�Para confirmar los cambios del git commit que tenemos que escribir para confirmar el commit?
	- :wq
	- :aq
	- :exit
	- :!aq	
2.	Para descargar en local los cambios hechos, �qu� comando usamos?
	- Git pull
	- Git clone
	- Git status
	- Git update
3.	�Para que sirven las ramas?	
	- Para poder trabajar en paralelo con otro compa�ero y que no haya conflicto evitando as� los juicios por combate a la hora a la hora del push
	- Para poder a�adir a nuevos colaboradores
	- Para commitear sin conflicto
	- Fue resultado de una noche de fiesta y todav�a se le busca utilidad


Antonio Joaquin Montero Garc�a

1. �Qu� comando usas para ver con detalles los "commits" hechos en un repositorio?
	-git log -v
	-git commit -view
	-git status
	-Ninguna opci�n es correcta.

1. �Pueden dos usuarios operar sobre un mismo archivo a la vez?
	-S�, pero no es recomendable.
	-S�, sin ning�n problema.
	-No.
	-Dos personas no pueden usar el mismo repositorio.

3. �Puede una persona usar y editar mi repositorio p�blico?
	-S�, a�adiendo a este usuario como colaborador.
	-S�, solo necesita tu usuario.
	-No, los repositorios no se comparten.
	-Ninguna de las opciones es correcta.

Fernando Carrascal Gallego

1 �Qu� comando utilizamos en Git para saber si tenemos algo que a�adir a la stagging area o listo para hacer commit?
	*git status
	*git log
	*git init
	*git stage

2 �Cu�l de estas no es una ventaja de los sistemas de control de versiones?
	*Posibilidad de editar simult�neamente el mismo archivo viendo los cambios en tiempo real.
	*Poder comparar versiones, viendo cuales han sido los cambios realizados.
	*Crear distintas ramas del proyecto. 
	*Regresar a una versi�n anterior cuando lo que hemos desarrollado no nos ha dado los resultados esperados.

3 �Cu�l es el m�todo m�s recomendado para solucionar los conflictos entre dos versiones del mismo archivo?
	*Mezclar ambas versiones en una nueva
	*Descartar nuestros cambios locales
	*Descartar los cambios existentes en el repositorio
	*Ninguno de los tres m�todos es recomendable

Sergio Ortiz Molde


1. �Cu�les son los tres estados de git?
	a.Git directory, Staging area y Working directory
	b.Working directory, Bug Fixing, Bug Logs, Staging area.
	c.Setting properties, Workspace, Git directory.
	d.Ninguna de las respuestas es correcta.

2. �Qu� comandos hay que realizar para subir un cambio a un repositorio remoto?
	a.�git add .�, �git commit�, �git push�.
	b.�git log�, �git add .�, �git commit�.
	c.�git add .�, �git commit�, �git pull�.
	d.Ninguna opci�n es correcta.

3. �Qu� es necesario tener para poder clonar un repositorio?
	a.Un repositorio creado en la nube.
	b.Un repositorio en local.
	c.Tener acceso por SSH o HTML al repositorio.
	d.Todas las respuestas son correctas.


Francisco Javier Mateos Guill�n

1. �D�nde se env�an los archivos al ejecutar el comando "git add ."?
	- A la Staging Area
	- A la papelera de reciclaje
	- Ninguna de las anteriores es correcta
	- A GitHub

2. �Con qu� comando puedes sacar un archivo de la Staging Area?
	- git rm
	- git add ..
	- git -add .
	- git extract
3. �Cu�l es el orden correcto de estos comandos si lo que pretendo es guardar los cambios en un repositorio y subirlos a GitHub?
	- git add . / git commit / git push
	- git push / git commit / git add .
	- git commit / git add . / git push
	- git add . / git push / git commit


Cayetano Garc�a Mart�n

1 Lista todos los registros de cambios disponibles.
 git branch
 git status
 git log
2 Una vez ya tenemos el repocitorio en local y queremos bajar los cambios hechos, �qu� comando usamos?
Git pull
Git clone
Git status
Git update
1. Git es un software de control de versiones centralizado.
Falso
Verdadero

## Beatriz Garc�a Ruiz-Adame

1. �Qu� comando se utiliza para iniciar un repositorio?
	* git pull
	* git init
	* git push
	* Ninguna es correcta
2. �Para que utilizamos el comando git status?
	* Iniciar repositio
	* Clonar repositorio
	* A�adir comentarios
	* Ver estado
3. �Qu� comando utilizaos para clonar un repositorio?
	* git log
	* git clone
	* git push
	* Ninguna es correcta
