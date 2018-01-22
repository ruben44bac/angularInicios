# angularInicios
Proyecto con angular, primeros pasos

## Instalación 

Para poder comenzar con un nuevo proyecto de angular es necesario tener instalado **node**:
* https://nodejs.org/es/

Posteriormente instalamos Angular CLI:

 *The Angular CLI is a command line interface tool that can create a project, add files, and perform a variety of ongoing development tasks such as testing, bundling, and deployment.*

* https://angular.io/guide/quickstart

Ahora, vamos a verificar que tengamos todo instalado con las siguientes líneas de comando:

* node -v *para verificar la versión de Nodejs*
* ng -v *para verificar la versión de AngularCLI*

## Problemas para reconocer *ng*

Probablemente se trate de un problema con las variables de entorno, en este link puedes encontrar una solución:

* https://stackoverflow.com/questions/37991556/ng-is-not-recognized-as-an-internal-or-external-command}

## Nuevo proyecto

Para poder crear un nuevo proyecto vamos a ingresar la siguiente línea de comando:

`ng new NOMBRE_PROYECTO`

Recuerda cambiar la palabra NOMBRE_PROYECTO por el nombre de tu proyecto, en nuestro caso no es necesario que creemos uno nuevo ya que podemos clonar este repositorio y trabajar sobre el.

## Instalando paquetes y dependencias

Antes de compilar nuestro proyecto debemos de instalar todaslas dependencias necesarias para que este funcione adecuadamente, estas dependencias las podemos encontrar en nuestro archivo `package.json`


````
{
  "name": "angularInicios",
  "version": "0.0.0",
  "license": "MIT",
  "scripts": {
    "ng": "ng",
    "start": "ng serve",
    "build": "ng build",
    "test": "ng test",
    "lint": "ng lint",
    "e2e": "ng e2e"
  },
  "private": true,
  "dependencies": {
    "@angular/animations": "^4.2.4",
    "@angular/common": "^4.2.4",
    "@angular/compiler": "^4.2.4",
    "@angular/core": "^4.2.4",
    "@angular/forms": "^4.2.4",
    "@angular/http": "^4.2.4",
    "@angular/platform-browser": "^4.2.4",
    "@angular/platform-browser-dynamic": "^4.2.4",
    "@angular/router": "^4.2.4",
    "core-js": "^2.4.1",
    "rxjs": "^5.4.2",
    "zone.js": "^0.8.14"
  },
  "devDependencies": {
    "@angular/cli": "1.4.5",
    "@angular/compiler-cli": "^4.2.4",
    "@angular/language-service": "^4.2.4",
    "@types/jasmine": "~2.5.53",
    "@types/jasminewd2": "~2.0.2",
    "@types/node": "~6.0.60",
    "codelyzer": "~3.2.0",
    "jasmine-core": "~2.6.2",
    "jasmine-spec-reporter": "~4.1.0",
    "karma": "~1.7.0",
    "karma-chrome-launcher": "~2.1.1",
    "karma-cli": "~1.0.1",
    "karma-coverage-istanbul-reporter": "^1.2.1",
    "karma-jasmine": "~1.1.0",
    "karma-jasmine-html-reporter": "^0.2.2",
    "protractor": "~5.1.2",
    "ts-node": "~3.2.0",
    "tslint": "~5.7.0",
    "typescript": "~2.3.3"
  }
}
````
