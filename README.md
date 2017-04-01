# SISTEMA DE CONTROL PARA VENTAS #

Sistema de control de ventas basico con las siguientes caracteristicas:

1. Opcion de administrador y vendedor(diferenciarlo al hacer login)
2. Lista de clientes(Autocompletado en busqueda de clientes) 
3. Ventas con fecha y hora 
4. Facturacion con igv(que se vea vuelto) 
5. Ver stock 
6. Ingreso de mercaderia (administrador) 
7. Opcion de 3 precios (para cantidades de 1, 10, 20) 
8. Estadisticas para ver el producto mas vendido por mes y año (administrador) 
9. Estadisticas por cliente (Para ver que es lo que mas compro) (administrador) 
10. Cuanto se ha vendido con el precio 1,2 y 3. 

### REQUERIMIENTOS ###

Descargar Netbeans

https://netbeans.org/downloads/

Descargar MySQL Workbench

http://www.mysql.com/products/workbench/
Cuando se instala MySQL dejar por defecto el usuario: root
y colocar como contraseña: 1234

### PASOS PARA EL USO ###

1. Abrir el Workbench y crear una base de datos con nombre : ventas_isaac
2. Importar la base de datos "ventas_isaac_usuarios" dando click en "Data Import/Restore" en la seccion MANAGEMENT
3. Abrir el proyecto en netbeans y ejecutarlo.
4. (Administrador: dni:44162124, pass: 123)  (Vendedor: dni:44162123, pass: 456)

Updated requirements.

1. Agregar seccion RUC y que solo sea permitido guardar solo con nombre(Agregarlo a ventas dni y ruc para verlo) -- listo
2. La opcion de default no aparesca en la lista.(nota: el idCliente por defecto es 9) -- listo
3. y que aparesca por defecto en crear venta. -- listo
4. Estadistica Ventas por precios, agregar mes y año -- listo
5. Terminar lo de ver producto con imagen. 208x127 test
// Ya crea y actualiza con imagenes
// Lo que falta es mostrar correctamente y de forma rapida en la creacion de ventas
