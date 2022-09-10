# AppleDataBase

Alojado en api.appledb.dev. Esto está diseñado para usarse en appledb.dev y ios.cfw.guide, sin embargo, también puede usar esta información en sus proyectos. Estructura del sitio web/API El sitio es un conjunto de archivos js/json estáticos que se alojan en el extremo de la API. Las actualizaciones de estos archivos después de una inserción harán que se construyan e implementen en el alojamiento de páginas de GitHub. La estructura de archivos se divide de la siguiente manera:

#.github/ Esta carpeta contiene varias definiciones para acciones y problemas de GitHub 

#.husky/ Esta es una herramienta de ayuda para asegurarse de que sus cambios estén "limpios" antes de un `git commit`. Se puede inclinar más sobre husky en https://typicode.github.io/husky/#/ 

#appledb-web/ 

#bypassApps/ *defineme* 

#bypassTweaks/ *defineme* 

#chipfiles/ Cada uno de estos archivos describe un procesador diseñado por Apple en particular (como el M1, A15, etc.). 

#DeviceFiles/ Cada uno de estos archivos describe un dispositivo Apple (como el iPhone 13 Pro Max, iPad Air, etc.). 

#DeviceGroupFiles/ Estos archivos agrupan los dispositivos relacionados en grupos relacionados (p. ej., los modelos de iPad con datos móviles y Wi-Fi están agrupados). 

#IOSfiles/ Estos son archivos que describen paquetes de software de SO en particular; a pesar del nombre de la carpeta, incluye más que versiones de iOS. 

#JailbreakFiles/ Estos describen herramientas particulares para lograr un jailbreak en un dispositivo. 

#node_modules/ Código de terceros que no está registrado en el repositorio que ayuda con la implementación, prueba, etc. de este repositorio. 

#Tests/ Estos son fragmentos de TypeScript/JavaScript que aseguran que no haya errores como falta de comillas o similares. en los archivos antes de intentar implementarlos. 

#Eslintrc.js/ Esto proporciona estilo EcmaScript/JavaScript/TypeScript y advertencias cuando ejecuta `npm run lint` 

#.gitignore Estos son archivos que nunca se registran en la copia de GitHub 

#Deploy.js * código de implementación heredado * - Se moverá a grunt 

#jest.config.json Configuración para el ejecutor de pruebas `jest` para los archivos en `tests/` 

=LICENCIA 
#Package.json Declara las diversas herramientas y comandos que utiliza el repositorio, como `npm test` 

#Package-Lock.json Un conjunto de las versiones correctas de herramientas para instalar en `node_modules/` - No editar a mano 

LÉAME.md 
Este archivo 

#tsconfig.json Configuración para permitir el uso de TypeScript y JavaScript 

#Update-Links.py * actualizador de enlaces heredados * - Mover a la tarea grunt



CONTRIBUTING

First fork the repository

Perform a git clone to your own computer and ensure you have NodeJS (https://nodejs.org/en/) installed.

In the working directory run npm install which will bring down the tools to check the code or to perform a build or other automated task.

Make edits

Run a git add . && git commit to save your work, and then git push to your fork. After that go to GitHub and open a Pull Request.

License
The data here is provided under a MIT license as described in the LICENSE file.

Credits
This repository is provided by littlebyteorg.

Portions of the data have been sourced from hack-different/apple-knowledge and the apple-data node package

Portions of the data have been sourced from theiphonewiki.com
