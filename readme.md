<img src="img/Git-Icon-1788C.png" width="100px" height="100px">

# Git 

Git es un sistema gestor de versiones de codigo. Este permite poder tener multiples versiones de tu codigo pudiendo regresar a una version anterior, ademas tambien facilita el trabajo en equipo atravez de sus ramas las cuales se crean y no afectan a la rama principal. 

### Configuracion de git 

Para poder usar git, necesitaremos configurarlo primero: 

* La primera configuracion sera asignar un nombre al usuario y se hace con el siguiente comando 

```bash
git config --global user.name "Enrique Gonzalez"

```
* La segunda sera introducir nuestro correo electronico y se hace con el siguiente comando

```bash
git config --global user.email gonherenrique@gmail.com 

```
* La tercera sera configurar el editor por defecto que  ocuparemos y se hace con el siguiente comando

```bash
git config --global core.editor "code --wait"
```

* Si queremos ver nuestra configuracion de lo que  llevamos, ocuparemos el siguiente comando 

```bash
git config --global -e
```

* Por ultima configuracion vamos a modificar los saltos de linea. Normalmente se manejan dos tipos **CRLF**(windows) y **LF**(linux/mac), esto lo tenemos que modificar por si llegamos a trabajar en equipo y cada uno de los integrantes tiene un sistema operativo diferente por lo tanto tendran una configuracion de salto de linea diferente.

Para windows es el siguiente comando:

```bash 
git config --global core.autocrlf true 
```

Para mac/linux es el siguiente comando:

```bash
git config --global core.autocrlf input 

```