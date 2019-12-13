




Version 1.01

<h1 align='center'> HOLA GIT </h1>

### *Comandos git*

Comandos para inicializar el git en esa carpeta:

    git init ./test/escenario1 
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

![git1](.\Imagenes\git1.png)

Despues rellenamos la siguiente ventana con el nombre del archivo y su descripcion:

![git2](.\Imagenes\git2.png)

Ahora vamos a seguir el ejemplo que nos sale en la pagina para añadir este .md:

![git3](\Imagenes\git3.png)

Primero voy a crear localmente una carpeta (Working) y voy a añadir este archivo y su correspondiente carpeta de imagenes:


### Biografías

Para la sintasis de [Markdown](https://markdown.es/sintaxis-markdown/)

Resumen de comandos de [Git](https://rogerdudler.github.io/git-guide/index.es.html)
