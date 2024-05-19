## Resumen de las órdenes git.

<div style="color : #71A3E6;">

### Configuración de herramientas

</div>

- Para establecer el nombre del usuario que hará los commits

``
$ git config --global user.name "[name]" 
``
- Para establecer el email del usuario que hará los commits

``
$ git config --global user.email "[email address]"
``

<div style="color : #71A3E6;">

### Creación de repositorios

</div>

- Crear repositorio

``
$ git init [project-name] 
``
- Descargar un proyecto y sus versiones

``
$ git clone [url]
``

<div style="color : #71A3E6;">

### Efectuar cambios

</div>

- Toma una instantánea del archivo para preparar la versión

``
$ git add [file]
``
- Registra las instantáneas del archivo permanentemente en el historial de versión

``
$ git commit -m "[descriptive message]"
``

<div style="color : #71A3E6;">

### Creación y manipulación de ramas

</div>

- Listar las ramas del repositorio actual

``
$ git branch
``
- Crear rama

``
$ git branch [branch-name]
``
- Cambiar de rama

``
$ git checkout [branch-name]
``
- Combinar ramas

``
$ git merge [branch]
``
- Eliminar rama especificada

``
$ git branch -d [branch-name]
``

<div style="color : #71A3E6;">

### Visualización

</div>

- Lista los archivos nuevos o modificados a confirmar

``
$ git status
``
- Muestra las diferencias de archivos que no se han enviado al área de espera

``
$ git diff
``
- Muestra las ramas de forma gráfica

``
$ git log --graph --all
``

