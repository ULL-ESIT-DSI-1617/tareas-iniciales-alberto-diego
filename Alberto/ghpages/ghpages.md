# Gh-pages

<div style="text-align:center"><img style="width:40%; height:40%" src="images/gh-pages.jpg"/></div>


### ¿Qué es gh-pages?
Las gh-pages o Github pages son páginas web que Github pone a nuestra disposición para nuestros proyectos, con la particularidad de que estas deben de estar alojadas en los repositorios propios de Github. Con el simple gesto de actualizar nuestro repositorio, también estaremos haciendo lo propio con la gh-page.

### Creación de una gh-page
Suponiendo que tenemos un código correspondiente a una página web, para incluirlo en una gh-page se puede hacer de varias maneras:

* Mediante Interfaz Gráfica:
Github proporciona por cada repositorio una opción en la que indicamos la activación de una gh-page y hacia que rama queremos que apunte.

<div style="text-align:center"><img style="width:70%; height:70%" src="images/gh-pagegui.png"/></div>

* Mediante la creación directa de una rama **gh-pages**:
Otra manera de publicar directamente una gh-page es crear una rama llamada **gh-pages** en la que alojemos ahí nuestro código de la página web.

<div style="text-align:center"><img style="width:70%; height:70%" src="images/ghpagebranch.png"/></div>

### Módulo gh-pages despliegue automático
Este script de Node.js usa el módulo gh-pages como interfaz para interactuar con el repositorio.
Previamente se debe instalar dicho módulo para ser utilizable.

```
npm install gh-pages --save-dev
```

Su uso básico es el siguiente:

```
var ghpages = require('gh-pages');
var path = require('path');

ghpages.publish(path.join(__dirname, 'dist'), function(err) { ... });
```

>Calling this function will create a temporary clone of the current repository, create a gh-pages branch if one doesn't already exist, copy over all files from the base path, or only those that match patterns from the optional src configuration, commit all changes, and push to the origin remote.

>If a gh-pages branch already exists, it will be updated with all commits from the remote before adding any commits from the provided src files.

Básicamente tras la ejecución de este script se realizará un despliegue de gh-pages en el repositorio que le indiquemos a la funcion **publish()**, si dicha rama **gh-pages** no existe, la creará de forma automática.
