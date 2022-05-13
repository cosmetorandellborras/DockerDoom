# DockerDoom

## Objetivos
Los objetivos de esta práctica son arrancar un contenedor de docker que contiene el videojuego clásico "Doom"

## Paso 1
Descargar el contenedor desde la siguiente dirección:
[Descarga dockerdoomd](https://web.archive.org/web/20160310005603/https://gideonred.com/bins/dockerdoomd.tar.gz)

## Paso 2

Una vez descargado, descomprimiremos el archivo con el siguiente comando:
~~~
tar -vzxf dockerdoomd.tar.gz
~~~
Y lo ejecutamos mediante el siguiente comando:
~~~
./dockerdoomd
~~~
![terminal](https://github.com/cosmetorandellborras/DockerDoom/blob/main/terminal.png)

## Paso 3

Como indica el mensaje que nos manda la terminal, para conectarse al contenedor hay que hacerlo via VNC a través del puerto 5900.

Para ello, abrimos nuestro visor de VNC y nos conectamos al contenedor con la siguiente dirección
~~~
localhost:5900
~~~
![juego](https://github.com/cosmetorandellborras/DockerDoom/blob/main/juego.png)
