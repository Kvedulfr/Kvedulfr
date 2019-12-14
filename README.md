




Version 1.01

<h1 align='center'> HOLA GIT </h1>

### *Comandos git*

Comandos para inicializar el git en esa carpeta:

    git init ./test/escenario1 <- Direccion de nuestra carpeta

Comando para saber el estado en el que se encuentra nuestros archivos antes de hacer el commit:

    git status

Para añadir a stage (a partir de aqui se puede recuperar):

    git add <archivo>
Hacemos el commit para confirmar los cambios(si hacemos el commit solo se abre en mi caso el VisualCode o el editor que hallamos elegido por defecto):

    git commint -m "Este es mi primer commit"

Para ver todos los cambios realizados:

    git log --oneline

Creamos un archivo para *ignorar* todos los archivos que no queramos subir:

	nano .gitignore //con el nano editamos como si fuera archivo de texto y agregamos los directorios y archivos que no queremos guardar. 


Para crear una copia del repositorio ejecutado usamos el comando:

	git clone /path/to/repository<--La ruta que en donde los quieres guardar:

o

    git clone username@host:/path/to/repository //Para un servidor remoto

Para ver las diferencias entre un archivo el cual hemos modificado utilizamos el siguiente comando:

    git diff 
y si el archivo el cual queremos comprobar se encuentra en el head usaremos el siguiente:

    git diff <head>

Si lo que queremos es subir nuestro repository en commit al repositorio remoto usaremos el siguiente comando:

    git push

O si queremos recogerlo del remoto al commit usaremos el fetch 

    git fecth

En el siguiente esquema podremos ver de forma mas general estos comandos donde actuan por si no tenemos claro como funciona todavia:

 
![img](http://blog.podrezo.com/wp-content/uploads/2014/09/git-operations.png)
## GitHud
Primero vamos a crear un repositorio en [github][linkg], para ello hay que crearse una cuenta (en mi caso ya tenia una) y en la pagina de inicio le damos a Start a project

[linkg]: https://github.com/

![git1](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git1.png)

Despues rellenamos la siguiente ventana con el nombre del archivo y su descripcion:

![git2](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git2.png)

Ahora vamos a seguir el ejemplo que nos sale en la pagina para añadir este .md:

![git3](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git3.png)

Primero voy a crear localmente una carpeta (Working) y voy a añadir este archivo y su correspondiente carpeta de imagenes y añadimos los archivos:

![git4](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git4.png)

Ahora vamos hacer el commit: 

![git5](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git5.png)

Enlazamos a nuestro github:

![git6](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git6.png)

Tras esto solo quedaría hacer un push teniendo que poner nuestras credenciales:

![git7](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git7.png)

Esta sería mi lista de los commit que he hecho hasta ahora:

![git8](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git8.png)

A continuación voy a crear un archivo el cual voy hacer que git lo ignore:

![git9](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git9.png)

Como vemos al hacer el ```git status``` nos ignora el archivo:

![git10](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git10.png)

Ahora vamos a crear una *branch* (rama) en la cual podremos modificar todo lo que queramos sin tener que usar la *Master* (Proyecto principal) para luego en un futuro fusionarlas y si el resultado nos gusta.
Para ello vamos usar ```git branch <nombre de la rama>``` con la que la creamos y luego usaremos ```git checkout <nombre de la rama>``` para posicionarnos en ella:

![git11](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git11.png)

Vamos a crear una etiqueta o ```tag``` para ello vamos hacerlo desde GitHub dande a la pestaña *release* dentro de nuestro repositorio:

![git12](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git12.png)

Depués pulsamos en tag (*Paso 1*) y luego en Create new a Release (*Paso 2*):

![git13](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git13.png)

Ahora el la siguiente pagina podremos añadir el titulo de nuestra etiqueta ademas a que rama se lo quieres colocar y añadir una descripción y abajo del todo podremos indicar si es *Pre-Release* es decir para indicar que todavia no esta acabado :

![git14](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git14.png)

Tras esto podremos ver todos las etiquetas creadas:

![git15](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git15.png)

Ahora vamos a añadir un colaborador al repositorio:

![git16](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git16.png)

Ahora vamos a crear en la rama un archivo 2.txt y vamos a hacerle un `commit`

![git17](https://github.com/Kvedulfr/Kvedulfr/blob/master/Imagenes/git17.png)



<h1 align=center>Repositorios de compañeros</h1>

NOMBRE | ENLACE
--|--
RAFA | [Repository Rafa][rafa]
JOSÉ | [Repository Jose][jose]
CHECA | [Repository Checa][checa]
MIRIAM | [Repository Miriam][miriam]

[rafa]: https://github.com/RuFFuS4/campusciff
[checa]: https://github.com/nitreer/campusciff
[jose]: https://github.com/campusciff-Vivinh0
[miriam]: https://github.com/MIRIAM-GIT/campusciff



### Biografías

Para la sintasis de [Markdown](https://markdown.es/sintaxis-markdown/)

Resumen de comandos de [Git](https://rogerdudler.github.io/git-guide/index.es.html)
