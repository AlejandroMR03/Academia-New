#Resumen Video
##Términos Importantes
Pruebas Http
Nos ayuda hacer solicitudes simples

Autenticación y Respuestas
La aplicación se probará en autenticación y Autorización

Prueba de Regresión
Describe exactamente lo que el usuario puede hacer y de que la aplicación no se detenga

##Carpeta y archivos de Prueba
Cuando estemos en el editor de código, vamos abrir la carpeta storage e inmediatamente nos aparecerá la carpeta de pruebas
![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/1.png?raw=true)

	Ejecución de Pruebas
Hay dos maneras de ejecutar las pruebas, la primera entrando desde el directorio, así:
./vendor/bin/phpunit
Inmediatamente nos mostrara el resultado de la prueba

![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/2.png?raw=true)
 
Otra manera de ejecutar las pruebas es con php artisan test

![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/3.png?raw=true)

Esta opción nos da una prueba mas clara y estructurada

###Crear una Nueva Prueba
Para crear una nueva prueba se introduce el siguiente comando
Php artisan make:test nombreprueba
Inmediatamente nos creara la prueba asi:

![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/4.png?raw=true)

Error de Prueba 
Una manera que nos salga un error en una prueba es no definir las variables
 
![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/5.png?raw=true)

####Crear una Prueba Unitaria 
Php artisan make:test nombreprueba –unit
Inmediatamente se nos creara la prueba unitaria
 
 ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/6.png?raw=true)
 
####Interfaz de Usuario
Para extraer una interfaz de usuario insertamos el siguiente comando
Composer require laravel/ui
 
  ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/7.png?raw=true)

Para no usar una parte del fronted se usa el siguiente comando
Php artisan ui react—auth
 
   ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/8.png?raw=true)

####Instalar npm y ejecutarlo
Usamos el comando npm install &&npm run dev
Este comando instala npm y lo ejecuta

   ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/9.png?raw=true)
   ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/10.png?raw=true)
   ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/11.png?raw=true)

##Crear Base de Datos
Entramos a Mysql desde la terminal con el comando mysql
 
   ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/12.png?raw=true)

Creamos la base de datos con el comando
Créate database laravel_testing;

   ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/14.png?raw=true)
 
Seguido de esto, nos salimos de mysql con exit
 
   ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/15.png?raw=true)
 
###Configurar nuestra Base de Datos
Después de haber creado la base de datos, necesitamos configurar la base de datos con nuestro proyecto
 
   ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/16.png?raw=true)
 
Introducimos el nuevo nombre de la base de datos que acabamos de crear , el nombre de usuario y contraseña
##Migraciones de la base de datos
Por último, paso vamos a hacer la respectiva migración con el comando
Php artisan migrate
   ![](https://github.com/AlejandroMR03/Testlaravel/blob/main/Capturas.img/17.png?raw=true)