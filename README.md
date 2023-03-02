# ProyectoPython
Proyecto Python para clase

Este proyecto se basa en ejecutar un script en Python con librerías instaladas (Usando pip)

# Creación

El fichero ```Dockerfile``` contiene toda la secuencia de órdenes necesaria para partiendo del contenedor de Python oficial, generando una nueva imagen
de docker con Python y la librería pytube instalada

# Ejecución
Desde el ```docker-compose.yml```ejecutamos el conteneder, con el script y apuntando el directorio actual hacia un directorio ```app```, desde el que se lanzará el 
script dentro del contenedor