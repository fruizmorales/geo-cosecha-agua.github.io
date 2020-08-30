# Sitio web del Portal Geoespacial del Proyecto Cosecha de Agua en Nicaragua

## Descripción general
Este repositorio contiene ...

## Ejecución del programa
Los siguientes comandos deben ejecutarse en la línea de comandos del sistema operativo. Se recomienda utilizar la interfaz de línea de comandos de Anaconda. Se asume que el ambiente Conda ha sido creado de la manera que se muestra en la sección siguiente a esta.
```shell
# Activación del ambiente Conda
$ conda activate geo-cosecha-agua-sitio-web

# Clonación del repositorio
$ git clone https://github.com/geo-cosecha-agua/geo-cosecha-agua.github.io.git
$ cd geo-cosecha-agua.github.io

# Prueba del sitio con el servidor interno de Jekyll (el resultado queda en http://127.0.0.1:4000/)
$ jekyll serve

# Modificaciones ...

# Actualización del repositorio y de los archivos GeoJSON generados
$ git add .
$ git commit -m "Comentario apropiado para reflejar los cambios"
$ git push

# Desactivación del ambiente Conda
$ conda deactivate
```

## Creación y configuración del ambiente Conda
El ambiente Conda solamente debe crearse una vez. Luego puede seguir usándose de la manera que se especifica en la sección anterior.
```shell
# Actualización de Conda
$ conda update -n base -c defaults conda

# Creación del ambiente
$ conda create -n geo-cosecha-agua-sitio-web

# Activación del ambiente
$ conda activate geo-cosecha-agua-sitio-web

# Instalación de paquetes
$ conda install -c conda-forge rb-jekyll

# Desactivación del ambiente
$ conda deactivate
```
