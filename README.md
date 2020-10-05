# Introducción
Apartado de educación de la web aula2030.es. Almacén de cursos y recursos.

Es una aplicación realizada con [CMS Grav](https://getgrav.org), destinada a ser un centro de recursos para profesores, organizados en cursos-capítulos-temas-secciones.


# Clonación del repositorio

Se puede realizar de las siguientes maneras:
	
    - 	Mediante “SSHH o HTTPS”.
    - 	Archivo Zip.

##### Opción 1 : “SSHH o HTTPS”

1. Accede a la página principal del repositorio 
1. Copiar la dirección del repositorio "SSH o HTTPS" desde la lista de archivos (Code).
1. Desde una  línea de comando o Git Bash situando sobre el directorio raíz, ejecutar  el comando  git clone seguido de la URL.

-	$ cd (Ruta al directorio)	
-	$ Git clone https://github.com/usuario/Nombre_de_repositorio.git


##### Opción 2  : Instalación con el paquete ZIP 

1. 	Descarga el repositorio .zip 


# **GRAV**

## Instalación de GRAV

1. Abre un Terminal o GIT BASH  y navega a la carpeta de tu directorio raíz.
1. Ejecutar el comando: 
    -  php bin/grav install
1. Para más información sobre la instalación de GRAV consulte este [enlace](https://learn.getgrav.org/16/basics/installation#option-3-install-from-github).

# **TEMAS**

## Instalación del TEMA LEARN2

1.  Abre un Terminal o GIT BASH  y navega a la carpeta de tu directorio raíz.
1.	Ejecutar el comando:
    -  bin/gpm install learn2
1.	Para más información sobre la instalación de temas consulte este [enlace](https://getgrav.org/downloads/themes).


### Actualización del temas Learn2

A medida que continúa el desarrollo del tema Learn2, pueden estar disponibles nuevas versiones que agregan características y funcionalidades adicionales, mejoran la compatibilidad con las versiones más recientes de Grav y, en general, brindan una mejor experiencia de usuario. 

Desde una  línea de comando o Git Bash situando sobre el directorio raíz, ejecutar  el comando: 
    - bin/gpm update learn2


# **PLUGINS**

## Plugin de inicio de sesión.

Plugin de inicio de sesión está diseñado para proporcionar una forma de proteger el contenido del sitio web.
Permite  tanto iniciar sesión como registro de usuarios utilizando  la ayuda de los plugins de **correo electrónico** y **formulario**.

- **Correo electrónico** sirve para  recuperar una contraseña por correo electrónico en caso de que el usuario no recuerda dicha contraseña.
-**formulario** para generar los formularios necesarios.

### Instalación :
1.  Abre un Terminal o GIT BASH  y navega a la carpeta de tu directorio raíz.
1.	Ejecutar el comando:
    - bin/gpm install login










