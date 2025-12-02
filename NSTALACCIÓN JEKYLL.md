# INSTALACCIÓN JEKYLL
 
Primero actualizaremos el sistema 

![](img/act2-1.png)

Utilizaremos el siguiente comando para instalar Ruby y sus heramientas necesarias para utilizar las gemas, en toda la instalación se recomienda no usar el usuario "root"

![](img/act2-2.png)

Establecemos los comandos para que las gemas se instalen localmente

![](img/act2-3.png)

Descargamos la gema de jekyll

![](img/act2-4.png)

Y así hemos conseguido instalar jekyll de manera local
# SITIO JEKYLL (MINIMA)

## Local

Para crear un sitio web en local con jekyll utilizaremos los siguientes comandos

![](img/act2-5.png)

vamos a la carpeta y personalizamos nuestros datos que saldran en nuestro sitio web configurando el archivo _config.yml

![](img/act2-6.png)

![](img/act2-7.png)

Guardamos y salimos

### Ahora personalizaremos las páginas "index.markdown" y "about.markdown"

lo primero crearé la carpeta "img" para las imagines de las paginas

![](img/act2-8.png)

nano index.markdown

![](img/act2-9.png)

guardamos

ahora enviaremos la imagen a la maquina a traves del comando scp

![](img/act2-10.png)

nano about.markdown

![](img/act2-11.png)

### Creo una nueva página

como tematica de la página serán los albumes del grupo

nano albumes.markdown, para crear el documento y lo editaremos

![](img/act2-12.png)

y guardamos

### Creo los posts

Creamos los post con el nano

![](img/act2-13.png)

Guardo y creo 2 más

![](img/act2-14.png)

ahora probaremos que funcione correctamente

iniciamos el servicio con la ip

![](img/act2-15.png)

y funciona

![](img/act2-16.png)

## GITHUB PAGES

ahora realizaremos el despliege con github pages

convertiemos la carpeta de la página en un repositorio con git init, añadiremos el repositorio remoto y creamos la rama gh-pages

![](img/act2-17.png)

Finalmente subiremos el repositorio local al remoto

![](img/act2-18.png)



