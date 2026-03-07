# Cosmodata: Sanyels
Mejorar ingreso y salida de productos. Costos fijos (arriendo, recibos servicios, salario personal). ingreso y egreso de capital.

## Entrada (inputs)
* Inventario
* Administrador@
* Numericos, textuales

## Procesos (Troughput)
* El sistema procesa los datos para registrar ventas,  actualizar el inventario y generar comprobantes 
* El sistema valida que los datos ingresados sean correctos y que haya suficiente stock disponible.
* el sistema calcula el total de la venta, impuestos y el cambio a devolver 
* El sistema almacena la informacion de productos, ventas y clientes 

## Salidas (Output)
*  El usuario obtiene un recibo de su compra.
* Genera el nombre del negocio por encima del producto, su precio, la fecha y hora en el que se vendió el producto.
* No permite permisos ya que viene una configuración predeterminada.

## Usuarios y Roles
* **Administrador:**
* **Usuarios:**

## Infomacion Manejada
* Ingreso de cada venta
* facturas de compra del inventario 
* facturas de los clientes para alguna garantía
Mejorar el ingreso y salida de productos. Control de costos fijos (arriendo, recibos de servicios, salario del personal) y registro del ingreso y egreso de capital.

---

# Arquitectura del Sistema: Sanyels

## Entradas (Inputs)
* Inventario
* Administrador
* Datos numéricos y textuales

## Procesos (Throughput)
* El sistema procesa los datos para registrar ventas, actualizar el inventario y generar comprobantes.
* El sistema valida que los datos ingresados sean correctos y que haya suficiente stock disponible.
* El sistema calcula el total de la venta, impuestos y el cambio a devolver.
* El sistema almacena la información de productos, ventas y clientes.

## Salidas (Outputs)
* El usuario obtiene un recibo de su compra.
* Se genera el nombre del negocio, el producto, su precio y la fecha y hora de venta.
* Reportes básicos de ventas e inventario.

## Usuarios y Roles
* **Administrador:** Gestiona productos, inventario y ventas del sistema.
* **Usuario:** Realiza compras y consulta información básica.

## Información Manejada
* Registro de cada venta
* Facturas de compra del inventario
* Facturas de clientes para garantías
