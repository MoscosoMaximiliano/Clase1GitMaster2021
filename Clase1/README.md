# Clase 1 GIT

## [VIDEO CLASE 1](https://drive.google.com/file/d/1OzqMfquSQccfogWpzoQrPqTHxe4W6rwj/view)

Hola chicos, como estan! Bienvenidos al curso de ***GIT***, en esta clase vamos a ver como hacer lo siguiente:
- Crear un directorio
- Crear un archivo
- Crear un repositorio local
- Crear el repositorio en ***GitHub***
- Subir lo que hicimos de local a ***GitHub***

# Requerimientos

- [*Visual Studio Code*](https://code.visualstudio.com/) **Como Instalarlo**: https://www.youtube.com/watch?v=EZAbKNLkrSM
- [*GIT*](https://git-scm.com/) **Como Instalarlo**: https://www.youtube.com/watch?v=dbEqN7EY-Mg
- [Cuenta en GitHub](https://github.com/) **Como Instalarlo**: https://www.youtube.com/watch?v=tJfghRy_LCo



# CMD
A lo largo de este curso vamos a estar usando el ***CMD***. Para ejecutarlo de la forma mas efectiva y sin equivocarnos es:
> Presionar las teclas ***Win + R***
![Alt](./Run.png)

> Escribir cmd y luego darle a ***Ok***
![Alt](./RunCMD.png)

A continuación tendran una tabla con los comandos basicos de ***CMD***

| Comando  | Descripción | Parametros | Ejemplo
| ------------- |:-------------:| ------------- |------------- |
| cd | Usado para moverse entre directorios | `dir` a donde nos dirigimos | cd Desktop
| mkdir | Usado para crear una carpeta | `nombre` de la carpeta a crear | mkdir Clase1

## Visual Studio Code

> Dentro de ***CMD*** nosotros podemos abrir facilmente VSCode (Visual Studio Code) usando el siguiente comando 
`code .`

![Alt](./VSCode.png)

# GIT

A continuación se nos abrira el ***CMD*** y podremos empezar a trabajar. Primero que nada vamos a usar el siguiente comando para verificar si tenemos ***GIT***

`git --version`

Si nos aparece lo siguiente:
![Alt](./GitStatus.png)

Significa que tenemos todo en condiciones para empezar.

> En el caso de que les tire error, instalar [***GIT***](https://git-scm.com/)

## Comandos

A continuación tendran una tabla de los comandos de ***GIT***
> Vale aclarar que antes de los comandos que se ponen siempre va la palabra clave **git**, Ejemplo:

![!Alt](./GitExample.png)

| Comando  | Descripción | Parametros | Ejemplo
| ------------- |:-------------:| ------------- |------------- |
| status | Te devuelve un listado de los archivos que no estan <br />*trackeados* | - | git status
| remote| Este comando se utiliza para vincular <br />tu ***git*** local con el repositorio de ***github***   | `add`: agregar el apuntado del repo de github <br /> `origin`: nombre con el que te vas a referir a el link que usas del repo| remote add origin `LINK DE TU REPOSITORIO`|
| add | Usado para agregar los archivos <br/>en un area de pre-lanzamiento     |`.` usado para agregar todos los archivos| git add . ***o*** git add pepito.txt|
| commit | Este comando se usa para decir que ya estan<br/>listos los archivos para enviarse a la nube (github)     |`-m` utilizado para dar un mensaje al commit | git commit -m "Primer Commit" |
| push | Aca enviamos ya todos nuestros archivos directo<br/>al repositorio     |`origin` repo al que envias<br/>`master` rama a la que apuntas (se vera mas adelante en la cursada)|git push origin master|

# Objetivos

 - Crear un repositorio en GitHub llamado ***"TallerGitHub-[Pongan Su Nombre]"***
 - Crear una carpeta en su computadora llamado ***"TallerGitHub"***
 - Inicializar Git dentro de esa carpeta
 - Agregar el Remote de Github a nuestro git de ***TallerGitHub***
 - Crear un txt que adentro diga "Hice mi primer commit"
 - Llevar a cabo el **add**, **commit** y **push**
 - Verificar que se subio nuestro archivo a el repositorio


 # Felicidades, hiciste tu primer repositorio y lograste hacer un push!
