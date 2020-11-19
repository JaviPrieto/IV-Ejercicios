# Ejercicios Tema 4

Ejercicios correspondiente a https://jj.github.io/IV/documentos/temas/Intro_concepto_y_soporte_fisico

## Ejercicio 1
**Darse de alta en algún sistema de integración continua y posteriormente activar el repositorio en el que se vaya a aplicar la integración continua.**

En primer lugar para empezar a trabajar con Travis CI debemos dirigirnos a su página oficial, la cual encontramos en el [siguiente enlace](https://travis-ci.org/).

Una vez dentro nos registramos si aún no tenemos cuenta, en Sign Up.

Lo siguiente es conectar nuestro repositorio Github con Travis CI:

![img-github-travis](https://github.com/JaviPrieto/IV-Ejercicios/blob/master/Tema4.Integracion-continua/imagenes/github-travis.png)

Una vez nos hemos dado de alta y hemos activado el repositorio en el que vamos a aplicar la integración continua, tenemos que crear un fichero de configuración para ejecutar la integración y tenemos que añadirlo a nuestro repositorio.

![img-travis](https://github.com/JaviPrieto/IV-Ejercicios/blob/master/Tema4.Integracion-continua/imagenes/travis.png)


## Ejercicio 2

**Configurar integración continua para nuestra aplicación usando Travis o algún otro sitio.**


Se ha configurado la integración continua sobre el repositorio [PeluqueriaUnisex](https://github.com/JaviPrieto/PeluqueriaUnisex), puede que sea modificado para ejecutar los tests haciendo uso del contenedor creado en el hito 3.

```
languaje: python
python:
  - "3.7"
before_install:
  - pip install --no-cache-dir -r requirements.txt
install:
  - cd app/src; python cita.py
script: make test
```

Podemos observar que funciona con la siguiente imagen:

![img-integracion](https://github.com/JaviPrieto/IV-Ejercicios/blob/master/Tema4.Integracion-continua/imagenes/integracion.png)

Pero me está dando error, luego procedo a arreglarlo:




