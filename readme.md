# Git Desarrollo Colaborativo

Esto es una guia para los alumnos de la capacitacion de __sistemas de control de versiones__ que cursan los dias _lunes miercoles y viernes de 14 a 17hs_

## Areas de GIT

* __Working Directory__: Corresponde a la carpeta donde INITializamos el repositorio, muy rara vez usamos la consola por aqui.
* __Staging Area (INDEX)__: Area de control de cambios

* __Repository (Local)__: El almacen local, corresponde a la carpeta donde se guardan las carpetas en formato BLOB usando una estructura hexadecimal

## Configuracion inicial

Antes de comenzar a trabajar en un proyecto es importante que configuremos nuestro nombre de usuario y correo con el que seremos identificados en los diferentes proyectos. Para ello utilizaremos los siguientes comandos

```sh
    git config --global user.name "username"
    git config --global user.email "user@server"
```