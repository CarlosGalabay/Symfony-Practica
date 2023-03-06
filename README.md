# Sistema de suscripción a cursos en línea
## Este sistema permite a los usuarios suscribirse a cursos en línea, con las siguientes 

Este sistema permite a los usuarios suscribirse a cursos en línea, con las siguientes características:

## Solo existe un usuario administrador, con las siguientes credenciales:

1. Email: admin@admin.com
2. Contraseña: 12345678


Los usuarios creadores solo pueden tener un máximo de dos cursos activos en línea.

Los usuarios consumidores pueden acceder a una cantidad ilimitada de cursos, pero solo pueden acceder a un curso a la vez de cada creador.

El usuario administrador es el encargado de dar de alta a los usuarios creadores.

## Los cursos pueden tener los siguientes estados:

1.En construcción
2. Activo
3. Inactivo


## La información de los usuarios creadores y consumidores incluye los siguientes datos:

1. Nombres y apellidos
2. Email
3. Contraseña
4. Tipo Usuario

# Instalación
## Para utilizar el sistema, se requiere tener instalado:

1. Instalar Xampp
2. Composer
3. Symphony

## Para instalar el sistema, seguir los siguientes pasos:
1. Clonar el repositorio en la carpeta raíz del servidor web:

```
git clone https://github.com/tuusuario/turepositorio.git

```
2. Una vez clonado el proyecto accedemos a el desde la terminal a la carpeta del proyecto ./cursos-online
3. Ya en la carpeta cursos-online se necesitan instalar todos los recursos del proyecto. Esto se logra escribiendo "composer install" en la consola
4. Una vez realizado los pasos anteriores abrimos el panel de control de Xampp y iniciamos el server para Php y MySql
5. Finalmente podemos acceder al proyecto desde el navegador escribiendo en la barra de busqueda loscalhost/... seguido de la ruta en donde tiene el proyecto
