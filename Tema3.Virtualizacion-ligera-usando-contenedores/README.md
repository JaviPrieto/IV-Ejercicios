# Ejercicios Tema 3

Ejercicios correspondiente a https://jj.github.io/IV/documentos/temas/Contenedores

## Ejercicio 1
**Instalar docker y/o otro gestor de contenedores como Podman/Buildah.**

#### Instalar Docker
En primer lugar eliminamos en caso de que existan, versiones antiguas de Docker:

![img-old-docker](https://github.com/JaviPrieto/IV-Ejercicios/blob/master/Tema3.Virtualizacion-ligera-usando-contenedores/imagenes/old-docker.png)

Actualizamos el índice de paquetes con: **sudo apt-get update** .

Instalamos los paquetes necesarios para permitir a apt usar un repositorio sobre HTTPS:

![img-update](https://github.com/JaviPrieto/IV-Ejercicios/blob/master/Tema3.Virtualizacion-ligera-usando-contenedores/imagenes/update.png)

Añadimos la clave GPG de Docker:

![img-download](https://github.com/JaviPrieto/IV-Ejercicios/blob/master/Tema3.Virtualizacion-ligera-usando-contenedores/imagenes/download.png)

Verificamos que tenemos la clave con la figerprint:

![img-fingerprint](https://github.com/JaviPrieto/IV-Ejercicios/blob/master/Tema3.Virtualizacion-ligera-usando-contenedores/imagenes/fingerprint.png)

Instalamos la ultima versión de Docker:

![img-estable](https://github.com/JaviPrieto/IV-Ejercicios/blob/master/Tema3.Virtualizacion-ligera-usando-contenedores/imagenes/docker-install.png)

Probamos si está instalado y funciona correctamente:

![img-hellowolrd](https://github.com/JaviPrieto/IV-Ejercicios/blob/master/Tema3.Virtualizacion-ligera-usando-contenedores/imagenes/hello-world.png)










