===============================
Toma & aplicación de inventario
===============================

Ubicación
=========

:Módulo:
 Inventario

:Grupo:
 Procesos

:Descripción:
Toma y aplicación de inventario

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
 	.. figure:: images/26.png
   		:align: center

- El sistema desplegará una ventana donde visualizará una grilla con todas las tomas pendientes.
- Seleccione un centro de costo para verificar las tomas ya creadas en él.
- Haga click en Nueva Toma |wznew.bmp|.
	Entrará a una ventana donde elegirá las características para la nueva toma.

	.. figure:: images/27.png
   		:align: center

   	.. figure:: images/28.png
   		:align: center

  Configuración nueva toma

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

  Selección de la modalidad

La modalidad de captura le permite facilitar el proceso mediante el cual usted digitará las cantidades que encunetre en su inventario físico. Cada una de las dos opciones ofrece una manera distinta de realizar el conteo.

			.. Reemplazar cantidad
			- **Modalidad de Reemplazo:** En este caso usted elige hacer el conteo de su producto en existencia física e incluir el total de lo que ha contado en la toma. Si vuelve a referirse a este producto (porque el total estaba errado, porque encontró más unidades de ese producto, o para verificar en un segundo conteo) entonces la suma anterior será sustituída por la nueva.

			.. Sumar cantidad
			- **Modalidad de suma:** En este caso usted elije sumar un producto cada vez que lo encuentre. En esta ocasión usted no realiza un conteo de la totalidad de sus productos antes de ingresarlos a sistema, sino más bien cada vez que encuentre una unidad entonces la suma a la cuenta. Esta opción es útil cuando los productos están identificados con un código de barra, con solo pasar la unidad por el lector, se agregará uno a la cuenta.



Editar/Eliminar una toma de inventario
======================================

**Editar:** Si usted desea cambiar alguna de las características establecidas anteriormente, puede hacerlo dando doble-click en el código de la toma sobre la grilla principal.

	.. Note:
	Recuerde que para que aparezca la toma en la grilla debe elegir el centro de costo donde la realizó.

**Eliminar:** Si desea eliminar la toma, sitúe el cursor sobre el código de la toma en la grilla principal y presione la tecla "supr".

Ingresar datos a la Toma
========================

 - Para ingresar datos a una *Toma de inventario*, seleccione la toma en la grilla principal y haga click en el botón |wzedit.bmp| *Ir a la toma*

	.. figure:: images/33.png
   		:align: center

 - Se desplegará una ventana donde deberá comenzar el ingreso de datos. Repita el siguiente ciclo de trabajo para agregar la información de su inventario físico al sistema:

 	1. **Elegir un producto para incorporar a la toma:**  Encontrará ahora la casilla |buscar.bmp| buscar, donde podrá dar inicio a la inserción de productos. Si sabe el código del producto digítelo, ingréselo con el lector láser, o también, situado sobre la casilla, oprima Enter para abrir la lista de productos y buscarlo. Oprima enter si ya lo ha encontrado o ha digitado el código.
 		 - Verá desplegada información acerca del producto como: Código, nombre, un campo llamado 'Sistema' que muestra la cantidad que se encuentra en el sistema. y un cuadro editable llamado 'Físico' donde usted ingresará la cantidad que quiera sumar a la cuenta del inventario físico.

			.. figure:: images/29.png
  			 	:align: center

 	2. **Establecer cantidad** De acuerdo a la modalidad de captura que haya escogido, se encontrará con dos escenarios diferentes:
 		- Si eligió *Modalidad de Reemplazo:*  entonces verá seleccionado el monto en el campo físico, listo para ser sustituido para la nueva cantidad de su conteo. Ingrese la cantidad y presione Enter dos veces.
 			.. Note:
 			Ejemplo: Si usted tiene 5 cajas de gomitas en su inventario físico, ingrese '5'. Si luego descubre que en verdad eran '8' cajas de gomitas, deberá de nuevo buscar este producto como en el paso 1, y aparecerá seleccionado el '5' para ser sustituido por el '8'.

 		- Si eligió *Modalidad de suma:* entonces verá en el campo el número '1', presione Enter dos veces para agregar una nueva unidad a la cuenta.
 			.. Note:
 			Ejemplo: Tome la caja de gomitas que tiene en la mano, y pásela por el lector, presione Enter y estará sumando una caja de gomitas a la cuenta. Si pasa otra caja de gomitas por el lector, y presiona Enter, entonces totalizará 2 cajas de gomitas. Así sucesivamente hasta haber sumado todas las cajas.

 .. figure:: images/30.png
  	:align: center



 	3. Regrese al paso 1 si aún tiene productos por agregar a la grilla.


Filtrar el listado en la grilla
===============================

Puede filtrar el contenido de la grilla para visualizar solo los productos que le interesan, de esa manera podrá localizarlos para verificarlos o modificarlos. ** IMPORTANTE: Los filtros tienen efectos sobre la grilla en pantalla, más no sobre lo que se imprime.** Los filtros aplicables son:

	- **Líneas:** En la cabecera encontrará una lista de las líneas disponibles.
	- **Mostrar únicamente productos con diferencias:** De los productos que ya ha ingresado en la grilla puede filtrar para que aparezcan aquellos cuya existencia en sistema y física son diferentes.
	- **Filtrar:** Filtrar es un campo de texto donde podrá hacer búsqueda de un producto en específico o de varios con alguna referencia similar. Busque por ejemplo, todos los productos cuyo código empiece por 10 o cuyo nombre tenga la letra Z.

	.. figure:: images/31.png
  			:align: center


Editar conteo de productos en toma de inventario
================================================

Para editar el número de unidades de un producto en su inventario físico, proceda de la siguiente manera:

- Busque el producto en la grilla usando el campo 'filtrar', vea `Filtrar el listado en la grilla`_
- Diríjase a la columna editable 'físico' y sustituya el valor ahí marcado por la nueva suma recolectada.

	.. figure:: images/32.png
  		:align: center

Aplicar una toma de inventario
==============================


	.. figure:: images/34.png
  		:align: center


Cuando usted aplica una toma de inventario, el sistema soluciona las diferencias entre el inventario real y el de sistema creando entradas y salidas automáticas. Es importante que sepa que estas entradas y salidas irán a su registro contable SI y SOLO SI usted realiza la configuración pertinente, agregando los conceptos adecuados a este proceso automatizado, en la pestaña *Inventario* de la opción `Parametrización Contable`_, si no la realiza entonces no estará afectando la contabilidad.

	.. figure:: images/35.png
  		:align: center

  Así es la ventana de parametrización contable.

Para *Aplicar una toma de inventario* pulse el botón  |btn_ok.bmp| *aplicar* y diga 'sí' en el mensaje de confirmación. Haga click en OK cuando el sistema confirme la aplicación. Será enviado de nuevo a la grilla principal.

Consultar una Toma que ya ha sido aplicada
==========================================

En la grilla principal del proceso *Toma y aplicación de inventario*, para consultar una toma realice los siguientes pasos:

	- Indique en la cabecera el centro de costo correspondiente a la toma. Automáticamente se actualizará la grilla mostrando las tomas que han sido aplicadas y las que aún no.
	- Seleccione la toma que ya ha sido aplicada (marcada con un check al final de la fila en la grilla) y pulse en la cabecera el botón |btn_ok.bmp| *consultar*.

Se desplegará una ventana donde usted podrá visualizar:

	- Número de referencia/documento de las entradas y/o salidas realizadas automáticamente.
	- Quién realizó la aplicación.
	- En que estación se realizó la aplicación.
	- Fecha de la aplicación.

		.. figure:: images/36.png
  		  :align: center

  Ejemplo del resultado de una toma aplicada.

**Es importante recordar que la información que se muestra en la grilla fue la de la toma, en el momento de la aplicación, y no refleja el estado actual del inventario**


.. |wznew.bmp| image:: /_images/generales/wznew.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp
