# PRACTICA DISEÑO APLICACIONES DISTRIBUIDAS

## **Nombre de la aplicación web: **  
jimTEC administrator

## **Descripción ** 
Herramienta web para gestionar facturas y garantias. El usuario debe ser capaz de gestionar  una base de  
datos donde tenga almacenados todos los articulos que ha comprado con distintos campos.
Operaciones: Insercción y borrado (modificación no incluida)
Datos factura: Fecha, nombre, núm factura, archivo (pdf o jpg), fecha garantia(si procede)

### **Parte pública ** 
Pagina para loguerase y sección explicativa de la funcionalidad de la web.

### **Parte privada ** 
Herramientas de gestión para realizar las operaciones, una de inserción/borrado y otra de consulta

## **Entidades **  
factura   : entidad principales que tiene la información de la factura  
categoria : entidad que sirve para categorizar las facturas (ocio, compras, alimentación etc)  
archivo   : entidad que sirve de información complementario a los datos de la factura y que será almacenada junto a esta  
historial : entidad que gestiona el almacenamiento de las facturas  

## ** Descripción **  
Insercción: Sirve para guardar una factura en la base de datos  
Borrado: Sirve para eliminar una factura de la base de datos  
Consulta: Sirve para extraer una fractura de base de datos  
