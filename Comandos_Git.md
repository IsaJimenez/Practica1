# GIT
## Configuración básica
Nombre del administrador:

`git config --global user.name "Antonio M.Durán Rosal"`

Correo electronico:

`git config --global user.email udaran@uco.es`

Editor de texto:

`git config --global core.editor "gedit"`

Color de interfaz:

`git config --global color.ui true`

Listado de la configuración:

`git config --list`

![Los tres estados de Git](http://1.bp.blogspot.com/-0ESPAhDYGQ4/ThMfRvj9FGI/AAAAAAAAAMM/Gifzuv9wwEA/s1600/git%2Blocal%2Boperations.jpg)

## Comandos basicos I

Iniciar repositorio en un directorio:

`git init`

Agregar cambios del area de *standing*:

`git add`

Validar cambios en el repositorio:

`git commit -m "Mensaje"`

Hacer los dos pasos anteriores en uno:

`git commit -am "Mensaje"`

Historial de commits:

`git log`
