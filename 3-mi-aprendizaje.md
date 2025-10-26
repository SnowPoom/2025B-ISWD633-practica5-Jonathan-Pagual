# Compose
Antes de la práctica, se me hacía muy complicado estar ejecutando docker run para cada contenedor que necesitara. Sin embargo, con el archivo compose.yaml se me hizo mucho más fácil, ya que permite configurar varios servicios o contenedores, definiendo sus puertos, volúmenes, etc. Luego ejecutar un único comando para levantar todos los servicios a la vez.
# Ejercicio
La parte más complicada de esto fue buscar toda la documentación de SonarQube, ya que estaba dividida entre Docker Hub y la página oficial de la imagen. La parte crucial fue encontrar la información sobre el JDBC de PostgreSQL y cómo colocarlo correctamente en la URL que solicita SonarQube.
