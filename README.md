# Educación
Apartado de educación de la web aula2030.es. Almacén de cursos y recursos.

Es una aplicación realizada con [CMS Grav](https://getgrav.org), destinada a ser un centro de recursos para profesores, organizados en cursos-capítulos-temas-secciones.


## Instalación desde GitHub

Clonar Grav desde el repositorio de GitHub y luego ejecutar un script de instalación de dependencia simple:

* Clone el repositorio Grav de GitHub a una carpeta en la raíz web de su servidor, por ejemplo ~/webroot/grav. Inicie una terminal o consola y navegue hasta la carpeta webroot:

    cd ~/webroot
    git clone -b master https://github.com/getgrav/grav.git

* Instale las dependencias del proveedor a través del compositor :

    cd ~/webroot/grav
    composer install --no-dev -o
   

* Instale el complemento y las dependencias del tema mediante la aplicación CLI de Grav bin/grav :

    cd ~/webroot/grav
    bin/grav installCopiar


    Esto automáticamente clonar las dependencias necesarias desde GitHub directamente en esta instalación Grav.


! Importante: **Instalar un nuevo tema Grav**

# Instalación

Nuestro método de instalación GPM (Grav Package Manager) le permite instalar rápida y fácilmente el tema con un simple
comando de terminal.

La forma más sencilla de instalar este tema es a través de Grav Package Manager (GPM) a través de la Terminal de su sistema(también llamada línea de comando). Desde la raíz de su tipo de instalación de Grav:

    bin/gpm install learn2

Esto instalará el tema Learn2 en su /user/themesdirectorio dentro de Grav. Sus archivos se pueden encontrar en /your/site/grav/user/themes/learn2.

# Actualización

A medida que continúa el desarrollo del tema Learn2, pueden estar disponibles nuevas versiones que agregan características y funcionalidades adicionales, mejoran la compatibilidad con las versiones más recientes de Grav y, en general, brindan una mejor experiencia de usuario. Actualizar Learn2 es fácil y se puede realizar a través del sistema GPM de Grav.

## Actualización de GPM 

La forma más sencilla de actualizar este tema es mediante Grav Package Manager (GPM) . Puede hacer esto con esto navegando al directorio raíz de su instalación de Grav usando la Terminal de su sistema (también llamada línea de comando) y escribiendo lo siguiente:

        bin/gpm update learn2




















