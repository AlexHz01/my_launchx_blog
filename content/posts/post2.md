---
title: "Linux_Mint"
date: 2022-11-23
description: 'Configuracion de tu entorno en LinuxMint'
---

---
### Crear una llave SSH para GitHub

instalamos `sudo apt install openssh-server`

Para crear una llave ssh lo primero que tenemos que hacer es ubicar la carpeta `~/.ssh` podemos ingresar a la carpeta `cd ~/.ssh` y si no tenemos la carpeta podemos crearla desde la terminal o directamente en la crpeta home de nuestra pc, terminal ==> `mkdir .ssh`

Una vez ubicado en la carpeta .ssh colocamos en nuestra terminal `ssh-keygen -t rsa -b 4096 -C “name@email”`

nos pedira que le ingresemos un nombre y una contraseña(colocamos a nuestra preferencia)

a hora solo nos queda ingresar el codigo que se encuentra en .ssh/ssh.pub en nuestro git hub y a hora podemos clonar cualquier repo a nuestra pc 

---  

### Comandos Utiles para la terminal

---
