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