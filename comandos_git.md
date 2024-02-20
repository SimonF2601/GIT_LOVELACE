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

- git config --global user.name "Your name"
- git config --global user.email "Your email"

## Comandos para editar o ver la configuracion de Git

- git config --global --edit 
- git config --global --list (Este ayuda a listar) 

PD: Para salir del edit si es VIM es Esc y :wq . Si es NANO es con ctrl + O y ctrl + X

## Como uniciar git en un directorio

- git init 

Hara aparecer el archivo  .git que es la conexion de entre el proyecto y el directorio remoto.

- git config --global init.defaultBranch main 
Este comando ayuda a nombrar la rama main por defecto 

## Pasos para crear una version de nuestro codigo 

1. Agregar todos los archivos al commit

- git add . -> Agrega todo 
- git add *js -> Agrega todos los que tengan la extension dada
- git add index.js -> Agrega el archivo nombrado 

