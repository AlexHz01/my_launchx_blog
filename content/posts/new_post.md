---
title: "Git + GitHub"
date: 2022-05-04
description: 'Git + GitHub y terminal'
---

---
### Como Crear un Repo remoto con Git + GitHub

Para poder crear un repo remoto desde GitHub de manera facil tendremos que crear una llave SSH en nuestra pc.  
[Created key SSH in us pc](https://www.youtube.com/watch?v=g0ZV-neSM7E&list=PLIazsGwUK1x2Kwf-jlU0TjsGb-E4ddlGS&index=1&t=548s)

1. 1- Utilizaremos la plataforma de GitHub para subir nuestra repo locales 
2. 2- Creamos una repo en GitHub y copiamos el link del repo 
3. 3- Creamos una carpeta  en nuestra PC 
4. 4- Abrimos la carpeta con una terminal
5. 5- Estando dentro de la carpeta desde la terminal inicializamos git con el sig. comando  ` git init `
7. 6- Utilizamos el comando ` git remote add origin ` + el url del repo creado en GitHub
8. 7- A hora ya podemos agregar carpetas con el comando ` git add ` + El nombre del archivo
9. 8- Una vex agregada las carpetas podemos hacer un commit con el comando `commit -m "Name File"`
10. 9- Por ultimo subimos el archivo a GitHub con el comando ` git push -u origin main ` 
11. 10- A hora solo nos queda ir al repo de GitHub y buscar repo creado en el paso 2

> El archivo .git es de suma importancia y por ese motivo nunca se debe eliminar 
---  

### Comandos Utiles para la terminal

1. `ls -la` --------------> Nos muestra los archivo ocultos
2. ` ls `   --------------> Nos muestra las carpetas y archivos
3. ` cd `   --------------> Abre carpetas 
4. ` cd ..` --------------> Nos regresa una carpeta atras 
5. `  mkdir ` ------------> Crea una Nueva carpeta 
6. ` touch  ` ------------> Crea un archivo

---
