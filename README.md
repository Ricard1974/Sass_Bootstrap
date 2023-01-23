Plantilla Base para Bootstrap y SASS

Plantilla basica para empezar a editar clases de Bootstrapo con CSS.


## Installation

Creamos una carpeta con nuestro proyecto

```bash
mkdir nombreProyecto
cd nombreProyecto
```
Necesitas tener insstalado node.js
https://nodejs.org/es/


Instalar SASS
```
npm install --save-dev sass
```

Instalar Bootstrap
```
npm install bootstrap --save
```
Descarga este repositorio y lo descomprimes dentro de nombreProyecto


Con la terminal dentro de nombreProyecto 

Instalamos dependencias https://www.npmjs.com/package/font-awesome
```
npm install --save @fortawesome/fontawesome-free
```

Instalamos autoprefixer

```
npm install postcss-cli autoprefixer --save
```

Ejecutamos el script de package.json
```
npm run compile:sass
```



## Documentation

[Documentation](https://linktodocumentation)


## Appendix

Si usas VS Code recoimiendo instalar las extensiones 

Description: Indented Sass syntax Highlighting, Autocomplete & Formatter
Version: 1.8.23
Publisher: Syler
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented

Name: Sass Autocompile
Id: darius2652.sass-autocompile
Description: SASS compiler for VS Code based off Atom's "sass-autocompile"
Version: 0.0.7
Publisher: Dian Jonker
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=Darius2652.sass-autocompile

Name: SCSS IntelliSense
Id: mrmlnc.vscode-scss
Description: Advanced autocompletion and refactoring support for SCSS
Version: 0.10.0
Publisher: mrmlnc
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss


## FAQ

#### Que fichero he de tocar para sobreescribir las variables?

scss\custom.scss

#### Donde esta el fichero resultante?

assets\css\custom.css
#### Que fichero he de hacer referencia?
```
<link rel="stylesheet" href="assets/css/custom.css">
```
#### Dónde estan las variables que puedo cambiar?

node_modules\bootstrap\scss\_variables.scss

