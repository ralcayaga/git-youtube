# Comandos utiles de Git

01. git init                     --> inicia el proyecto (crea la carpeta oculta '.git' con la configuracion del repositorio)
02. git add .                    --> toma todos los archivos que uno tiene del ultimo commit y tomara una foto del repositorio
                                --> clasifica los cambios que se realizan el repositorio (new file, delete file,             --> modified, untrack (sin clasificacion))
03. git reset                    --> revierte el comando "git add", en caso de haberse equivocado
04. git commit -m "comentario"   --> saca la fotografia del respositorio
                                 --> -am evitamos tener hacer el git add . y despues el git commit -m
05. git checkout -- .            --> devuelve añ ultimo commit que se hizo, en caso de perdidas
06. git log                      --> muestra el listado de todos los commits realizados con su   respectivo identificador asi
                                    uno puede.
07. git commit --amend           --> Permite editar el commint y asi poder realizar los cambios (i: para editar y esc wq! para 
                                    grabar)
08. git checkout -b nombre_rama  --> Crea una nueva rama (-b = branch) 
09. git branch                   --> Me indica en que rama estoy
10. git merge nombre_rama        --> Fusiona la rama donde uno esta parado con la rama que puso en el comando 
11. git branch -d nombre_rama    --> Elimina la rama creada (Uno debe estar en otra rama, al parecer?)
12. git push                     --> Carga el  contenido del repositorio local a un repositorio remoto