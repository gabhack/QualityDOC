===============================
Toma & aplicación de inventario
===============================

Ubicación
=========

:Módulo:
 Inventario

:Grupo:
 Operaciones

:Descripción:
Interfaz para facilitar la toma de inventarios

Introducción
============
*Toma y aplicación de inventario* es una interfaz del sistema que le facilitará la revisión, verificación y ajuste de su inventario en sistema. Evite llevar a cabo cálculos manuales y obtenga plantillas para la toma física del inventario.

	Esta opción le permitirá entre otras cosas:
		- Mostrar la diferencia entre las existencias físicas y las del sistema.
		- Realizar ajustes automáticos, haciendo entradas y salidas de inventario.
		- Imprimir en diferentes formatos reportes de las diferencias o de las existencias en sistema.
		- Separar las tomas de inventario por Líneas (categorías).

Crear una toma de inventario
============================

Pre-requisitos
--------------

Para crear una toma de inventario tenga en cuenta que:

	-	Debe existir por lo menos un centro de costo.
	- Debe existir al menos una línea, una sublínea y un producto.

Pasos para crear una toma de inventario
---------------------------------------
	
- Ejecute la opción *Toma y aplicación de inventario*
- El sistema desplegará una ventana donde visualizará una grilla con todas las tomas pendientes. 
- Seleccione un centro de costo para verificar las tomas ya creadas en él.
- Haga click en Nueva Toma |nuevo.bmp|.
	Entrará a una ventana donde elegirá las características para la nueva toma.
		- Elija el almacén donde hará la verificación del inventario.
		- Escriba una fecha para la toma.
		- Marque la opción "Incluir productos sin existencias" si desea listar también en la toma cualquier producto que tenga cantidad 0 según el sistema. Es probable que no haya existencia en el sistema pero físicamente sí.
		- Seguidamente, puede colocar una observación para describir la toma.
		- Encontrará un árbol con las líneas de productos que por defecto no están seleccionadas. Seleccione las categorías que quiera incluír en la toma. Si desea marcarlas o desmarcarlas todas, pulse el botón *Seleccionar o quitar todas las líneas de productos*
		- Ahora podrá elegir en el botón *Elegir un proveedor específico* si quiere incluir los productos que han sido entregados a su centro por un proveedor seleccionado. Si desea incluír todos los proveedores entonces ignore el botón.
		- Elija la `Modalidad de captura`_
		- Pulse Guardar Toma |save.bmp|

Modalidad de captura
^^^^^^^^^^^^^^^^^^^^

La modalidad de captura le permite facilitar el proceso mediante el cual usted digitará las cantidades que encunetre en su inventario físico. Cada una de las dos opciones ofrece una manera distinta de realizar el conteo.

			.. Reemplazar cantidad
			- **Reemplazar la cantidad previamente digitada por el nuevo valor digitado:** En este caso usted elige hacer el conteo de su producto en existencia física e incluir el total de lo que ha contado en la toma. Si vuelve a referirse a este producto (porque el total estaba errado, porque encontró más unidades de ese producto, o para verificar en un segundo conteo) entonces la suma anterior será sustituída por la nueva.

			.. Sumar cantidad
			- **Sumar la cantidad digitada al valor previamente digitado:** En este caso usted elije sumar un producto cada vez que lo encuentre. En esta ocasión usted no realiza un conteo de la totalidad de sus productos antes de ingresarlos a sistema, sino más bien cada vez que encuentre una unidad entonces la suma a la cuenta. Esta opción es útil cuando los productos están identificados con un código de barra, con solo pasar la unidad por el lector, se agregará uno a la cuenta.
		


Editar/Eliminar una toma de inventario
======================================

**Editar:** Si usted desea cambiar alguna de las características establecidas anteriormente, puede hacerlo dando doble-click en el código de la toma sobre la grilla principal. 

	.. Note:
	Recuerde que para que aparezca la toma en la grilla debe elegir el centro de costo donde la realizó.

**Eliminar:** Si desea eliminar la toma, sitúe el cursor sobre el código de la toma en la grilla principal y presione la tecla "supr".

Ingresar datos a la Toma
========================

 - Para ingresar datos a una *Toma de inventario*, seleccione la toma en la grilla principal y haga click en el botón 'Ir a la toma' |wzedit.bmp|.
 - Se desplegará una ventana donde deberá comenzar el ingreso de datos. Repita el siguiente ciclo de trabajo para agregar la información de su inventario físico al sistema:

 	1. **Agregando productos a la grilla:**   Encontrará ahora la casilla |buscar.bmp| buscar, donde podrá dar inicio a la inserción de productos. Si sabe el código del producto digítelo, ingréselo con el lector láser, o también oprima Enter y búsquelo en la lista de productos. Oprima Enter de nuevo.
 		 - Verá desplegada información acerca del producto como: Código, nombre, un campo llamado 'Sistema' que muestra la cantidad que se encuentra en el sistema. y un cuadro editable llamado "Físico" donde usted ingresará la cantidad que quiera sumar a la cuenta del inventario físico.
 	2. **Estableciendo cantidad** De acuerdo a la modalidad de captura que haya escogido, se encontrará con dos escenarios diferentes:
 		- Si eligió *Reemplazar la cantidad previamente digitada por el nuevo valor digitado:*  entonces verá seleccionado el monto en el campo físico, listo para ser sustituido para la nueva cantidad de su conteo. Ingrese la cantidad y presione Enter dos veces.
 			.. Note:
 			Ejemplo: Si usted tiene 5 cajas de gomitas en su inventario físico, ingrese '5'. Si luego descubre que en verdad eran '8' cajas de gomitas, deberá de nuevo buscar este producto como en el paso 1, y aparecerá seleccionado el 's' para ser sustituido por el '8'.

 		- Si eligió *Sumar la cantidad digitada al valor previamente digitado:* entonces verá en el campo el número '1', presione Enter dos veces para agregar una nueva unidad a la cuenta.
 			.. Note:
 			Ejemplo: Tome la caja de gomitas que tiene en la mano, y pásela por el lector, presione Enter y estará sumando una caja de gomitas a la cuenta. Si pasa otra caja de gomitas por el lector, y presiona Enter, entonces totalizará 2 cajas de gomitas. Así sucesivamente hasta haber sumado todas las cajas.
 	3. Regrese al paso 1 si aún tiene productos por agregar a la grilla.


Filtrar el listado en la grilla
===============================



Editar conteo de productos en toma de inventario
================================================

Aplicar una toma de inventario
==============================



.. |wznew.bmp| image:: /_images/generales/wznew.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp