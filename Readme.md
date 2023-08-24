# Comandos utiles de Git

1.- git init                     --> inicia el proyecto (crea la carpeta oculta '.git' con la configuracion del repositorio)
2.- git add .                    --> toma todos los archivos que uno tiene del ultimo commit y tomara una foto del repositorio
                                 --> clasifica los cambios que se realizan el repositorio (new file, delete file,             --> modified, untrack (sin clasificacion))
3.- git reset                    --> revierte el comando "git add", en caso de haberse equivocado
4.- git commit -m "comentario"   --> saca la fotografia del respositorio
5.- git checkout -- .            --> devuelve añ ultimo commit que se hizo, en caso de perdidas
6.- git log                      --> muestra el listado de todos los commits realizados con su   respectivo identificador asi
                                     uno puede.
7.- git commit --amend           --> Permite editar el commint y asi poder realizar los cambios (i: para editar y esc wq! para 
                                     grabar)
8.- git checkout -b nombre_rama  --> Crea una nueva rama (-b = branch) 
9.- git branch                   --> Me indica en que rama estoy