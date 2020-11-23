# Ejercicios git
En los siguientes ejercicios vamos a trabajar con una página web que es un portfolio, para poder ir visualizando el contenido simplemente tienes que abrir index.hml en el navegador.

## Ejercicio 1 - Prepare basic git environment
Vamos a preparar el proyecto 'portfolio'

	a) Crea un repositorio nuevo local llamadao portfolio
    b) Extrae los ficheros que te ha proporcionado el profesor en dicho repositorio.
    c) Crea un repositorio privado nuevo en github llamado 'portfolio' da acceso al usaurio del profesor e indica aquí la url
    d) Enlaza tu repositorio local con el repositorio remoto creado en el apartado anterior
    e) Haz lo necesario para que todos los ficheros estén disponibles en el respositorio remoto.
    f) Crea un directorio en tu carpteta personal llamado proyectosGit. ¡¡¡OJO NO LO HAGAS DENTRO DEL REPOSITORIO ANTERIOR!!!
    
## Ejercicio 2
En este ejercicio vamos crear dos copias del repositorio de github en nuestro directorio de proyectosGit para simular que trabajamos en dos ordenadores distintos uno será el de Julia y otro el de Pablo.

	a) Crea dos copias del respositorio portfolio de github llamadas porftJulia y portPablo.

## Ejercicio 3
Cámbiate al repositorio de portJulia y realiza los siguientes ejercicios en él.

	a) Vamos a organizar las carpetas:
    	- Mueve el directorio js al directorio assets con el comando mv 
    	- Comprueba el estado del repositorio y muéstralo aquí
    	- Muevel el directorio css al directorio assets con el comando git mv 
    	- Comprueba el estado del repositorio y muéstralo aquí
    b) Indica las diferencias que encuentras entre mover los ficheros de una forma o de otra.
    c) Añade los cambios al área de preparación.
    d) Comprueba el estado del repositorio y muéstralo aquí
    e) Guarda los cambios con un mensaje acorde a los cambios realizados.
    f) Olvidaste cambiar el código para que funciones correctamente la página, para ello tienes que modificar en el fichero index.html las siguientes líneas:
    	- 29, 30 y 31 añade assets/ delante de css. Las líneas quedarían así:
    	
        ` <link href="assets/css/styles.css" rel="stylesheet">
          <link rel="stylesheet" href="assets/css/heading.css">
    	  <link rel="stylesheet" href="assets/css/body.css">`
          
    	- 394 añade assets/ delante de js
    g) Añade los cambios al área de preparación y añade los cambios al commit anterior modificando el mensaje para que refleje también los nuevos cambios.
    h) Muestra los commits realizados en formato de una línea y pega aquí el resultado.
    i) Envía los cambios al repositorio remoto
    j) Modifica el fichero index.html, cambia en la línea 58 avataaars.svg por computer.png
    k) Comprueba el estados del respositorio y las diferencias del fichero.
    l) Añade el fichero al área de preparación.
    m) Vuelve a mostrar los cambios en el fichero.
    n) Envia los cambios al repositoiro remoto.
    
# Ejercicio 4
Vamos a trabajar en el repositorio de Pablo, en portPablo.

	a) Actualiza el repositorio portPablo y analiza los mensajes
    b) Crea un nuevo directorio llamado 'docs'
    	- Comprueba el estado del repositorio. ¿Qué ha pasado?
    	- Haz lo necesario para que los cambios aparezcan en el respositorio remoto
    c) Edita el fichero html y cambia todas las ocurrencias de 'Navendu Pottekkat' por tu nombre.
    	- Comprueba los cambios al repositorio remoto e indica lo que observas.
    d) Envía los cambios al repositorio remoto
    	    
# Ejercicio 5
Volvemos a trabajar en el repositorio de Julia, en portJulia.

	a) Crea el fichero page2.html con el siguiente contenido:

	<!doctype html>
	<html lang="en">
	  <head>
	    <!-- Required meta tags -->
	    <meta charset="utf-8">
	    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	
	    <!-- Bootstrap CSS -->
	    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
	
	    <title>Hello, world!</title>
	  </head>
	  <body>
	    <h1>Hello, world!</h1>
	
	    <!-- Optional JavaScript -->
	    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
	    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
	    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
	    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
	  </body>
	</html>
	
	b) Haz lo necesario para enviar los cambios al repositorio
	
# Ejercicio 6
Volvemos a trabajar en portPablo:

	a) Elimina el fichero LICENSE, utiliza únicamente 'rm'.
    	- comprueba el estado del repositorio analizando los mensajes.
    	- Deshaz el cambio.
    b) Elimina el fiechero LICENSE de nuevo, pero esta vez utiliza 'git rm'
    	- Comprueba el estado del repositorio analizando los mensajes.
    	- Deshaz el cambio.
    c) Elimina una vez más LICENSE y haz commit con los cambios.
    d) Recupera el fichero.
    d) Por último elimina el fichero del repositorio y haz que los cambios se reflejen en el repositorio remoto.
    
# Ejercicio 7
En portJulia:
	
    a) Actualiza el respositorio.
    b) Cambia en la línea 68 Machine Learning - Computer Vision por Frontend Developer y ML on Edge por Estudiante en IES Jacarandá
    c) Envía los cambios al repositorio remoto.
    
En portPablo:

	a) NO ACTUALICES EL REPOSITORIO
    b) Camba en la línea 68 Machine Learning - Compurter Vision por Fullstack Developer y Ml on Edge por Estudiante DAW en IES Jacarandá
    c) Realiza los pasos para conseguir que en el repositorio remoto quede como lo acabas de modificar.
    d) Averigua quién y cuando se creó el fichero page2.html
    
# Ejercicio 8
En portJulia:

	a) Actualiza el repositorio.
    b) Crea una rama llamada cambiandoProyectos.
    c) Cámbiate a dicha rama.
    d) Modifica el nombre de algún proyecto en el fichero index.html (Si no sabes como pregunta al profesor) y envía los cambios al repositorio remoto a su rama.
    e) Cámbiate a la rama main.
    f) Añade cualquier contenido al fichero page2.html.
    g) Incorpora los cambios de la rama master a la rama cambiandoProyectos.
    h) Muestra los cambios que se han ido produciendo en el repositorio de manera que se muestren las ramas gráficamente.
    i) Añade algún contenido al fichero page2.html y sube los cambios al respositorio.
    j) Incorpora los cambios de la rama cambiandoProyectos a la rama main.
    k) Elimina la rama cambiandoProyectos.
    l) Sube los cambios al respositorio remoto.
