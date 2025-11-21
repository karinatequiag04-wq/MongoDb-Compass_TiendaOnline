### TIENDA ONLINE MONGODB ###

Este proyecto implementa una base de datos NoSQL utilizando MongoDB para una tienda en línea de ropa, calzado, skinni jeans etc.
Incluye:

Inserción de datos (más de 100 productos)

Consultas básicas (CRUD)

Consultas con filtros y operadores

Consultas de agregación para estadísticas

Diseño y documentación de la base de datos# MongoDb-Compass_TiendaOnline
Implementación de una base de datos NoSQL en MongoDB para una tienda en línea de ropa, calzado, accesorios y hogar. Incluye inserciones, consultas básicas, filtros, operaciones CRUD y consultas de agregación.


## ESTRUCTURA DEL PROYECTO ##

/data
    productos.json      → Lista de productos
    clientes.json       → Lista de clientes
    pedidos.json        → Registro de pedidos

/consultas
    operaciones_basicas.js
    filtros_operadores.js
    agregaciones.js

README.md               → Documentación del proyecto

## CARGA DE DATOS ##

. Carga de datos

Los archivos JSON utilizados como dataset se encuentran en la carpeta /data:

productos.json → contiene más de 100 productos de ropa, calzado y accesorios

clientes.json → lista de clientes registrados

pedidos.json → pedidos realizados por los clientes

## CONSULTAS BASICAS ##

2. Consultas básicas (CRUD)

Ubicadas en /consultas/operaciones_basicas.js.

Incluye:

Inserción de documentos

Actualización de stock

Eliminación de clientes

Búsquedas de productos por categoría
