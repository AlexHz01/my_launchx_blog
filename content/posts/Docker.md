* docker images ( con esto podemos visualizar las imagenes en nuestra pc)
* docker pull univerciadadDB (Obtener una imagen o un repositorio de un registro)
* docker image rm "name or id" (para borrar una imegen creada)

- docker ps (para ver los contenedores "iniciados")
- docker ps -a (para ver todos nuestros contededores de nuestro sistema)

* docker --name NameNew NameOld (Si queremos cambiar el nombre)
* docker start NameNew ( con esto inicializamos el container)
* docker stop NameNew (detener los contenedores)

+ docker network ls( con esto visualizamos las networks creadas)
+ docker build -t nombre_imagen:version path (Construimos una imagen apartir de un archivo > Dockerfile)
+ docker network inspect ide-net (Ver las caracteristcias de la red creada)

Pasosos<br>
1 Descargar o crear la imagen<br>
2 Crear una red<br>
3 Inicializar el contenedor<br>
4 Configurar PYcharm<br>
