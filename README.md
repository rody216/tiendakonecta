# Sistema tienda Konecta
![php](./assets/img/fondo.png)
link de descarga: https://github.com/rody216/tiendakonecta
## Requerimientos
* PHP 7.2
* MySQL 5.7

## Instalación
1.  Clonar el repositorio y ubicar la carpeta en la carpeta www de
    wamp o en htdocs de xampp
2.  Levantar el servidor de phpmyadmin y los servicios de mysql o Mariadb
3.  Crear una base de datos en MySQL de nombre konecta
4.  Importar el Script de la base de datos incluido en el repositorio de
    nombre `konecta_bd.sql`
5.  Configurar el archivo `conexion.php` con los datos de la base de datos
    $host = "localhost";
    $user = "root";
    $clave = "";
    $bd = "konecta";
    Si en su servidor local maneja contraseña colocarla enmedio de las comillas de la variable $clave
6.  Abrir desde el navegador la Ruta http://localhost/tiendakonecta/ 
7.  Las Credenciales de Accesso son user: admin pass: admin para ingresar 
    con permisos de administrador, y user: conecta pass: conecta para ingresar como usuario con restricciones    
6.  Al ingresar al sistema la pantalla de inicio le muestra los filtros 
    indicandole cuales son los productos mas vendidos, los productos con stock minimo, cuantos usuarios hay registrados, cuantos clientes, cuantos productos y cuantas ventas se han realizado.
7.  En la parte superior derecha se encuentra el boton de cerrar sesion,
    el cual le permite cerrar la sesion y volver a la pantalla de login.
8.  En la parte superior izquierda se encuentra el boton de menu, el cual 
    le permite desplegar el menu de opciones del sistema.
9.  En la parte inferior izquierda se encuentra la información de       
    CopyRignt.
10. En la parte inferior derecha se encuentra las políticas de privacidad 
    los terminos y condiciones.
