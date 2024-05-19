## Resumen de las órdene git.

### Configuración de herramientas

- Para establecer el nombre del usuario que hará los commits

``
$ git config --global user.name "[name]" 
``
- Para establecer el email del usuario que hará los commits

``
$ git config --global user.email "[email address]" 
``
### Creación de repositorios

- Crear repositorio

``
$ git init [project-name] 
``
- Descargar un proyecto y sus versiones

``
$ git clone [url]
``
### Efectuar cambios

- Toma una instantánea del archivo para preparar la versión

``
$ git add [file]
``
- Registra las instantáneas del archivo permanentemente en el historial de versión

``
$ git commit -m "[descriptive message]"
``
### Creación y manipulación de ramas

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
### Visualización

- Lista los archivos nuevos o modificados a confirmar

``
$ git status
``
- Muestra las diferencias de archivos que no se han enviado al área de espera.

``
$ git diff
``
- Muestra las ramas de forma gráfica

``
$ git log --graph --all
``