---
title: "Linux_Mint"
date: 2022-11-23
description: 'Configuracion de tu entorno en LinuxMint'
---

---  

### Instalacion de SNAPCRAFT

Snapcraft es una herramienta que permite a los desarrolladores crear paquetes de cualquier aplicación para ser utilizados en Snappy. Es decir, reúne todas las dependencias necesarias para el empaquetado de las aplicaciones y poder ser ejecutadas

comandos para instalar 

- 1 `sudo rm /etc/apt/preferences.d/nosnap.pref`
- 2 `sudo apt update`
- 3 `sudo apt install snapd`

conesto podemos instalar desde la terminal cualquier programa que este en la store de snapcraft

---

---
### Crear una llave SSH para GitHub

- instalamos `sudo apt install openssh-server`
- Para crear una llave ssh lo primero que tenemos que hacer es ubicar la carpeta `~/.ssh` podemos ingresar a la carpeta `cd ~/.ssh` y si no tenemos la carpeta podemos crearla desde la terminal o directamente en la crpeta home de nuestra pc, terminal ==> `mkdir .ssh`
- Una vez ubicado en la carpeta .ssh colocamos en nuestra terminal `ssh-keygen -t rsa -b 4096 -C “name@email”` nos pedira que le ingresemos un nombre y una contraseña(colocamos a nuestra preferencia)
- A hora solo nos queda ingresar el codigo que se encuentra en `.ssh/ssh.pub` en nuestro git hub y a hora podemos clonar cualquier repo a nuestra pc 

---  

### Intalar un gestor de base de datos e IDE

Un buen gestor de base de datos para linux mint es DBeaver podemos intalar con el comando `sudo snap install dbeaver-ce`
para instalar pycharm `sudo snap install pycharm-professional --channel=2022.1/stable --classic`
Podemos ir directo a la store de snpacraft y descargar una version en especifico

---

---  

### Configuracion de la terminal con ZSH
- instalamos `sudo apt-get install git zsh`
- instalamos `sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"`
- clonamos `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`
- colocamos `ZSH_THEME="powerlevel10k/powerlevel10k"` en `~/.zshrc`. (podemos usar los editores nano o vim)
- Reinicie Zsh con `exec zsh`.
- Descargamos e instalamos una de las 4 fuentes [fuentes](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k)
- Escribimos en la terminal `10k configure` para configurar a nuestro gusto la terminal
---

---  

### Instalacion de nvm

- lo primero es instalar `wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash`
- a hora con el comando `nvm ls-remote` nos listara todas las versiones disponibles instalamos la mas preferente 
- Para instalar una version `nvm install v16.18.1` 


---
