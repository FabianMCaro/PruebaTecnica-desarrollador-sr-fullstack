Configuracion del proyecto 
-intalar XAMPP control panel
-intalar composer

En el directorio raíz de xampp, en la carpeta htdocs “C:\xampp\htdocs” desacargar el proyecto 

La base de datos la puede descargra e importar a una de mysql, que es en ente ontorno en el cual fue creado.

En la directorio PruebaTecnica/.env se encutra la conexión a la base de datos con usuario:root y contraseña: toor


En la estructura de proyecto en PruebaTecnica/app/Http/Controllers/controler.php se encuentra el controlador del proyecto y es el archivo en donde se encutra la lógica del programa del CRUD para realizar las consultas de los libros y las actualización de los mismos
En la estructura de proyecto en PruebaTecnica/app/Http/Controllers/Model.php, en este archivo se encuentra el modelo principal que utiliza el controlador y es el que da la estructura para realizar las consultas contra la base de datos
En PruebaTecnica/routes/web.php se hace la referencia del controlador para la implementación

Y en el directorio PruebaTecnica/views se encuentras los archivos en donde se pordra realizar las consultas de los libros
