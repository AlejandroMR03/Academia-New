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

 

	Ejecución de Pruebas
Hay dos maneras de ejecutar las pruebas, la primera entrando desde el directorio, así:
./vendor/bin/phpunit
Inmediatamente nos mostrara el resultado de la prueba
 
Otra manera de ejecutar las pruebas es con php artisan test
 

Esta opción nos da una prueba mas clara y estructurada

###Crear una Nueva Prueba
Para crear una nueva prueba se introduce el siguiente comando
Php artisan make:test nombreprueba
Inmediatamente nos creara la prueba asi:
 

Error de Prueba 
Una manera que nos salga un error en una prueba es no definir las variables
 

####Crear una Prueba Unitaria 
Php artisan make:test nombreprueba –unit
Inmediatamente se nos creara la prueba unitaria
 

####Interfaz de Usuario
Para extraer una interfaz de usuario insertamos el siguiente comando
Composer require laravel/ui
 

Para no usar una parte del fronted se usa el siguiente comando
Php artisan ui react—auth
 

####Instalar npm y ejecutarlo
Usamos el comando npm install &&npm run dev
Este comando instala npm y lo ejecuta
 
 
 

##Crear Base de Datos
Entramos a Mysql desde la terminal con el comando mysql
 

Creamos la base de datos con el comando
Créate database laravel_testing;
 
Seguido de esto, nos salimos de mysql con exit
 
###Configurar nuestra Base de Datos
Después de haber creado la base de datos, necesitamos configurar la base de datos con nuestro proyecto
 
Introducimos el nuevo nombre de la base de datos que acabamos de crear , el nombre de usuario y contraseña
##Migraciones de la base de datos
Por último, paso vamos a hacer la respectiva migración con el comando
Php artisan migrate