# Titulo Grande (H1) 
## Subtitulo (H2)

# Comandos de Git

git   config   --global  user.name   "Your name"
-- Explicacion
git: comando 
--global: Que se hara
user.name: Especificacion 
"Your name":Atributo


## Comando para ver la versión de Git

- git --v
- git --version

## Comandos para configuracion inicial de Git

- git config --global user.name "Your name" ("Funciona para agregar el user a git")
- git config --global user.email "Your email" ("Funciona para agregar el user a git")
- git config --global core.editor "code --wait" ("Predetermina a VS code como editor")
- git config --global -e 

## Comandos para editar o ver la configuracion de Git

- git config --global --edit 
- git config --global --list (Este ayuda a listar) 

PD: Para salir del edit si es VIM es Esc y :wq . Si es NANO es con ctrl + O y ctrl + X

## Como iniciar git en un directorio

- git init 

Hara aparecer el archivo  .git que es la conexion de entre el proyecto y el directorio remoto.

- git config --global init.defaultBranch main 
Este comando ayuda a nombrar la rama main por defecto 

## Comando para saber el estado de nuestros archivos

- git status 

## Comando para listar las versiones de mi proyecto

- git log 
- git log --oneline

## Comando para cambiar el nombre de las ramas 

git branch -m "nombre antiguo" "nombre nuevo"

## Comando para cambiar de versión

- git checkout <Id del commit o nombre de la rama>

##

- git config --global core.autocrlf true ("Sirve para darle el caracter que necesita window para su salto de linea)

## Comando para eliminar archivos desde git, se debe hacer commit cuando no se elimine correctamente

- git rm --cached nombre_archivo  -> "Este cached tiene  como funcion de recargar el VS"
- git rm nombre_archivo 

## Comando para recuperar/descartar (cambios) archivos de un commit anterior o una eliminacion 

- git restore nombre_archivo 
- git restore --staged nombre_archivo ("Tiene como funcion para descartar los cambios que se hayan ido para el unstage <commit>")

# IMPORTANTE!
## Pasos para crear una version de nuestro codigo 

1. Agregar todos los archivos al commit

- git add . -> Agrega todo 
- git add \*js -> Agrega todos los que tengan la extension dada
- git add index.js -> Agrega el archivo nombrado 

2.  Crear uan nueva version (Tomar la foto del código)

- git commit -m "Nombre del commit"
- git commit -am "Sirve para hacer el add y commit juntos solo se puede hacer simpre y cuando haya un seguimiento antes"

3. Hacer push para subir al repositorio remoto 