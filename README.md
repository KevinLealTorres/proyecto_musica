# Proyecto de música

- Por: Kevin Alejandro Leal
- Para la materia: Computación en Java
- A día: Viernes, 3 de mayo de 2024

---


## ¿Qué es?
Es un proyecto de Jakarta EE para acceder a una base de datos MySQL y hacer operaciones dentro de la base de datos
"music". 


## Requerimientos:

1. IntelliJ IDEA Community
2. Java JDK 22 o superior
3. Maven (Para instalar las dependencias de Jakarta EE)


## Cómo configurar
1. (opcionalmente) hacer un pull para las nuevas actualizaciones de este repo, con el comando ```git pull origin main```
2. En ```proyecto_musica/src/resources/META-INF/``` debes cambiar el archivo ```persistence.xms```, en el apartado de
usuario y contraseña de la base de datos
3. Actualizar las dependencias de Maven (```proyecto_musica/pom.xml```), ya sea que lo hagas con las herramientas de 
IntelliJ o manualmente (```mvn clean install```)

