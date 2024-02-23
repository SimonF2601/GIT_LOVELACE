# Comando para conectar mi git local con git en la nube (remoto)

- git remote add nombre_conexion url_conexion ("Se utiliza cuando en la nube esta vacio", " en nombre de la conexion: el default name es origin, sin embargo se puede poner cualquiera" )

# Comando para clonar o traer un repositorio de git remoto 

- git clone url_conexion

# Comando para listar las conexiones remotas 

- git remote -v

# Comando para eliminar una conexión remota

- git remote remove nombre_conexión

# Comando para enviar informacion al git remoto

- git push
- git push nombre_conexion nombre_rama
- git push -u nombre-conexion nombre_rama ("La -u sirve para crear la rama si no esta creada, y la crea con el nombre puesto en el comando" )

# Comando para obtener cambios o la informacion que hay en el git remoto

- git pull
- git pull nombre_conexion nombre_rama

###

