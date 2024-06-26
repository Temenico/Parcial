# Sistema de Facturación 

De acuerdo con los siguientes requerimientos, diseñe el respectivo diagrama de clases, casos de uso y el de secuencias.

### Cliente:
+ El sistema, debe permitir gestionar clientes, incluyendo registro de (tipoDocumento, documento, nombre, correo). Modificar, eliminar y consultar clientes usando el documento como identificador.

### FacturaCliente:
+ El sistema de permitir gestionar facturas, incluyendo crear (numeroFactura, fecha, cliente), modificar, eliminar y consultar facturas usando el número de factura como identificador.

### DetalleFactura:
+ El sistema de permitir gestionar deetalles de factura, incluyendo agregar (cantidad, valorBruto, valorNeto, valorDescuento, valorTotal), modificar, eliminar y consultar detalles de facturas.

### Producto:
+ El sistema debe permitir gestionar productos incluyendo a registrar (código, nombre, descripción, categoría, valor), modificar, eliminar y consultar productos usando el código como identificador.

### Inventario:
+ El sistema de permitir gestionar inventario, incluyendo registrar la entrada, (código,stock, fechaIngreso, valorDescuento, porcentajeIVA) registrar salida (código, fechaSalida), modificar, eliminar y consultar inventario usando código usando el código como identificador.

## Diagrama de Clases
![Diagrama de Clases](Imagenes/Diagrama%20de%20Clases.png)

## Diagrama de Casos de Uso
![Diagrama de Casos](Imagenes/Diagrama%20de%20Casos%20de%20Uso.png)

## Diagrama de Secuencias
![Diagrama de Secuencias](Imagenes/Diagrama%20de%20Secuencias.png)