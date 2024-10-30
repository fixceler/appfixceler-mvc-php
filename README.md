# APPFixceler - Proyecto completo de Administración de Citas para Taller Automotriz y taller de latoneria y Pintura.

El proyecto APP Fixceler es una solución completa de administración de citas diseñada específicamente para Taller. Ofrece herramientas de gestión y administración privada que permiten controlar las citas de los clientes y agregar nuevos servicios al rubro de la mecanica, electronica, pintura y latoneria automotriz. La aplicación cuenta con funcionalidades de inicio de sesión, creación de cuentas y recuperación de cuentas para garantizar la seguridad y accesibilidad de los usuarios.
Construido con HTML, SASS, JavaScript Vanilla, y PHP 8 bajo el patrón de diseño MVC, APP Fixceler proporciona una base sólida y eficiente para la gestión de citas y servicios en el entorno del taller automotriz. Esta aplicación es ideal para propietarios y administradores de Taller de mecanica automotriz ,taller de latoneria y pintura, que buscan una solución integral para organizar y supervisar las citas y servicios ofrecidos en su establecimiento.

## Tech Stack

Tech Stack: POO PHP 8 MVC, HTML SASS Gulp, JavaScript Vanilla.

## Screenshots

[![ ]()]()
[![ ]()]()

## Installation

Recuerden realizar el `npm install`, para reconstruir los módulos de node e instalar gulp de manera global y composer:

```En la terminal escribir:
npm i sass@1.77.6 --save-exact : linea de codigo opcional 
npm i
npm i -g gulp
npm run gulp
composer install --ignore-platform-reqs : linea de codigo opcional 

En una nueva terminal 

composer i
```

Luego ` gulp` para ejecutar la aplicación y para el localhost:

```
cd public
php -S localhost:3000
```
```
luego ejecutar en un nueva terminal lo siguiente: 

composer require phpmailer/phpmailer

para consultar :https://github.com/PHPMailer/PHPMailer
```
para la que funcione la anterior linea de codigo se tiene que realizar lo siguiente: 

Editar php.ini eliminar el punto y coma ';' antes de extension=zip y de extension=gd
para mayor inforacion consultar;

https://stackoverflow.com/questions/39384644/extension-gd-is-missing-from-your-system-laravel-composer-update
https://stackoverflow.com/questions/39384644/extension-gd-is-missing-from-your-system-laravel-composer-update

```
Una vez ejecutado composer require phpmailer/phpmailer en la terminal escribir el siguiente comando:

composer update

## Acknowledgements

- [Cesar Perez](https://fixceler.com/)

## Authors

- [Cesar Perez](https://www.github.com/fixceler)
