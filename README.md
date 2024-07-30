# Fase III
## Taller de Productividad basada en herramientas tecnológicas


# Fase IV
## Índice
### Despcrición del proyecto

Sietema de punto de venta de una tienda de abarrotes, creado con el lenguaje de programación Java y para la base de datos SQL. El sistema se encarga de recolectar la información de los productos que se venden dentro de la tienda, alojandolos en la base de datos. Tiene la capacidad de generar una lista diaria del total de ventas realizadas. 

### Problema identificado

* Registro manual de ventas.
  - Actualmente, las ventas se registran manualmente, lo que puede llevar a errores y perdidas de la información. 

* Tiempo de espera.
  - Lo clientes frecuentemente enfrentan tiempos de espera de 5 a 10 minutos, lo que provoca impaciencia y perdida de ventas. 

* Competencia.
  - La competencia ofrece un servicio mas rápido, atrayendo a si a clientes que buscan una mejor conveniencia.

### Tabla de Contenido

* [build](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/build.xml)
  - [Img](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src/Img)
  - [Modelo](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src/Modelo)
  - [Reportes](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src/Reportes)
  - [Vista](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src/Vista)
  - [sistemaventa](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src/sistemaventa)
* [librerias](https://github.com/2608995/Fase-III/tree/519d3ec3f00c383243a3a556618b517a2140671e/librerias)
  - [AbsoluteLayout.jar](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/librerias/AbsoluteLayout.jar)
  - [itextpdf](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/librerias/itextpdf-5.5.1.jar)
  - [Jcalendar.jar](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/librerias/jcalendar-1.4.jar)
  - [Jcommon.jar](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/librerias/jcommon-1.0.23.jar)
  - [FreeChart.jar](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/librerias/jfreechart-1.0.19.jar)
  - [MySQL-Conector](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/librerias/mysql-connector-java-8.0.19.jar)
* [nbproject](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/nbproject)
  - [build-impl.xml](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/nbproject/build-impl.xml)
  - [genfiles.properties](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/nbproject/genfiles.properties)
  - [project.properties](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/nbproject/project.properties)
  - [project.xml](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/nbproject/project.xml)
* [src](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src)
  - [Img](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src/Img)
  - [Modelo](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src/Modelo)
  - [Reportes](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src/Reportes)
  - [Vista](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src/Vista)
  - [sistemaventa](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/src/sistemaventa)
* [test](https://github.com/2608995/Fase-III/tree/056042a90ff9a7c393753e472d6326bbf900dfdb/test)
  - [JUnitTest](https://github.com/2608995/Fase-III/blob/056042a90ff9a7c393753e472d6326bbf900dfdb/test/NewEmptyJUnitTest.java)

### Requerimientos 
* Se debe de tener instalado en su computador:
  - Java
  - SQL (base de datos)
  - Sistema JC Punto de venta
  - Apache
* Descargar las conexiones de base de datos MySQL.

### Instalación 
* Descargar el proyecto del repositorio
* Descomprimir el archivo para obtener la carpeta
* Abrir la carpeta del proyecto
* Ejecutar el proyecto

### Configuración 
* Asegurate que el servidor tenga suficiente capacidad de procesamiento
* Instalar MySQL y configurar el acceso remoto (si es necesario).
* Asegura que tu IDE este configurado con tu servidor.
* Configura la conexion a la base de datos en tu IDE para facilitar el desarrollo. 

### Uso
El sistema punto de venta, es un software de interfaz amigable, permitiendo a los empleados gestionar las ventas, el inventario y los proveedores de manera eficiente.
* Inicio de sesion
  - los empleados abren la aplicacion e ingresan sus credenciales en la panatalla de inicio
  - El sistema verifica el acceso.
* Gestion de ventas.
 - El sistema genera recibos de venta y los almacena en la base de datos.
 - Se registran las ventas.
* Gestion de Inventario
  - los empleados pueden revisar el stock que se tiene en la tienda.
  - El sistema puede actualizar la informacion de los productos existentes.
  - El sistema muestra alertas cuando algun producto este por agotarse.
* Proveedores
  - Los empleados pueden registrar nuevos proveedores y actualizar la informacion de los provedores existentes.
  - El sistema permite consultar los datos de contacto y las ordenes de compra relacionadas con cada proveedor
* Facturas
  - El sistema genera facturas automaticamente. 

### Conribución 

* Dar click en el siguiente link https://github.com/2608995/Fase-III.git
* Abrir el repositorio en el branch master.
* Dar click en code.
* Descargar la opcion en "descargar el archivo zipcode". 

### Roadmap

* Para asegurar la evolución continua y la mejora del sistema 'Abarrotes El Semillas', se han identificado varios requerimientos que se implementarán en el futuro. Estos requerimientos están diseñados para aumentar la funcionalidad del sistema, mejorar la experiencia del usuario y optimizar las operaciones de la tienda. A continuación se presenta el roadmap de implementación:
  - Integracion con metodos de pagos digitales.
  - integracion con proveedores.
  - Mejorar la seguridad y autenticacion
  - Crear un modulo que permita gestionar promociones. 







