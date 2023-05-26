-Abrir Visual Studio Code y dirigirse al apartado de Source Control

-Presionar el boton "Clone Repository"

-Insertar el siguiente link "https://github.com/gardeniaJS/Coneduca-PUCV-entry-test.git"

-Seleccionar una carpeta de destino vacia y presionar el boton " Select as: Repository Destination

-Click en el boton "Open"

-En una nueva terminal ejecutar el comando "composer install"

-Crear archivo .env en la root del proyecto y copiar el ejemplo de example.env al nuevo archivo .env

-Modificar la linea 14, debe quedar asi "DB_DATABASE=a1b2c3"

-Abrir el panel de control de XAMPP

-Presionar el boton "Start" en la fila Apache y MySQL 

-Dentro del panel de control de MySQL presionar en "Nueva"

-En el campo con placeholder "Nombre de la base de datos" ingresar "a1b2c3" y presionar el boton "Crear"

-En la terminar ejecutar el comando php artisan make:model Modelo -m

-Luego ejecutar el comando php artisan migrate

-En el navegador click en el boton "GENERATE APP KEY" 

Con eso el proyecto queda listo para usarse.
