# Github

<div style="text-align:center"><img style="width:40%; height:40%" src="images/github.png"/></div>


### ¿Qué es Github?
GitHub es una plataforma de desarrollo colaborativo de software para alojar proyectos utilizando el sistema de control de versiones Git.
GitHub aloja tu repositorio de código y te brinda herramientas muy útiles para el trabajo en equipo, dentro de un proyecto. Además de eso, puedes contribuir a mejorar el software de los demás. Para poder alcanzar esta meta, GitHub provee de funcionalidades para hacer un fork y solicitar pulls.

<div style="text-align:center"><img style="width:70%; height:70%" src="images/githubfork.png"/></div>

Realizar un fork es simplemente clonar un repositorio ajeno (genera una copia en tu cuenta), para eliminar algún bug o modificar cosas de él. Una vez realizadas tus modificaciones puedes enviar un pull al dueño del proyecto. Éste podrá analizar los cambios que has realizado fácilmente, y si considera interesante tu contribución, adjuntarlo con el repositorio original.

### Github desktop para Windows
>GitHub Desktop is a seamless way to contribute to projects on GitHub and GitHub Enterprise.

Github desktop es una versión de Github de escritorio para Windows y Mac. Ésta ofrece diferentes ventajas, como puede ser la rapidez de contribución como una mejor visibilidad de la evolución de los proyectos.

Para su instalación bastará con visitar la siguiente página web ([Aquí](https://desktop.github.com/)) y descargar e instalar el software proporcionado, sincronizar con tu cuenta de github, etc.

<div style="text-align:center"><img style="width:70%; height:70%" src="images/githubdesktop.png"/></div>

De esta manera, una vez instalado se podrá acceder a todas aquellas herramientas que están disponibles en la versión web, en la siguiente imagen se puede ver un ejemplo de un proyecto donde se visualiza la diferencia de un código con respecto a nuevas instantáneas (commit).

<div style="text-align:center"><img style="width:70%; height:70%" src="images/githubdesktop2.png"/></div>

## Hub

### ¿Qué es hub?

# **git + hub = github**

>hub is a command line tool that wraps git in order to extend it with extra features and commands that make working with GitHub easier.

Básicamente *hub* es una herramienta que nos facilita la interacción desde la línea de comandos con github, ésta es capaz de hacer todos aquellos procesos que haríamos desde la interfaz web de github, como por ejemplo crear un repositorio, eliminarlo, etc. Además nos provee de una sintaxis de fácil uso, ejemplo:

```
$ hub clone rtomayko/tilt

# expands to:
$ git clone git://github.com/rtomayko/tilt.git
```

Para instalar esta herramienta deberemos ejecutar los siguientes comandos:
```
$ git clone https://github.com/github/hub.git
$ cd hub
$ make install prefix=/usr/local
```
