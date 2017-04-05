=============================
Impresión de código de barras
=============================

Ubicación
=========

:Módulo:
 Inventario

:Grupo:
 Procesos

:Descripción:
 Impresión de código de barras


Introducción
============

Usted podrá usar esta opción para imprimir etiquetas de código de barras para manejo interno del inventario. Esta opción es exclusiva para aquellos productos cuyo empaque no tenga un código previamente marcado. Si su producto ya tiene código de barras y desea registrarlo en sistema, puede hacerlo en el momento de `crear o editar el producto <../generalidades/act_maestroinsumos.html#productos-servicios>`_

Pre-Requisitos
==============

Para imprimir las etiquetas de código de barras:

	- El producto debe existir en el catalogo de productos. `Crear un producto <../generalidades/act_maestroinsumos.html#productos-servicios>`_


Para Imprimir las etiquetas de código de barras
===============================================

	- Ejecute la opción *impresión de código de barras* 

		  .. figure:: images/50.png
      		   :align: center

	- En la ventana que se desplega, elija el centro de costo donde se encuentran los productos que desea marcar con las etiquetas.
	- Ahora puede proceder a insertar los artículos que desea marcar:
		- Haga click en la cabezera de la columna 'Código' en la grilla.
		- Se crea un nueva linea en la grilla, y el foco se ubicará en la columna código. Presione Enter.
		- Se desplegará una ventana con la lista de productos y usted podrá hacer click en cualquiera y presionar Enter para seleccionarlo.
		- Verá el producto que seleccionó en la grilla. 
		- La casilla en la columna 'Cantidad' es modificable. Digite allí el número de etiquetas para este producto que desea imprimir.

					  .. figure:: images/51.png
      						:align: center

		- La casilla en la columna 'Valor' es modificable. Digite allí el precio de este producto.

			.. Note:

			No es obligatorio colocar el precio en la columna 'Valor' si no eleigió mostrar el precio del producto en la eqtiqueta. Vea `Configuración de Stickers`_

			En cualquier caso, el precio que coloque en la columna 'Valor', siempre modificará el valor en la 'Lista de precios "1"', vea `Configuración de listas de precio por defecto <>`_

		-Puede insertar los productos que quiera a la grilla. Para insertar de nuevo un producto, sitúese en la fila del último producto de la grilla y presione la tecla direccional 'abajo' ↓ dos veces.

					  .. figure:: images/52.png
      						:align: center

	- Bajo la grilla encontrará una lista donde podrá cambiar la configuración del Sticker. Si desea crear una nueva configuración de sticker, entonces presione el botón |wzedit.bmp| y vea `Configuración de Stickers`_
	- Luego, encontrará otra lista donde debe seleccionar el formato de impresión.
	- Puede configurar la impresión, a modo de que muestre una vista previa o imprima de una vez, en el ícono |gear.bmp| a la izquierda.
	- Para imprimir las etiquetas de los productos en la grilla, según lo que indicó en la columna *Cantidad* y *Valor*, presione F2 o haga click en |printer_q.bmp| a la derecha.

		.. Note:

		También puede acceder desde el *catalogo de productos y servicios*

		- Ejecute la opción *Catálogo de productos y servicios*
  		- Haga click en |codbar.png| *impresión de código de barras* en la cabecera de la ventana.

Configuración de Stickers
=========================

Puede acceder a la configuración de Stickers en la opción *Impresión de código de barras* bajo la grilla. 

		  .. figure:: images/53.png
      		   :align: center


Para configurar un modelo de Sticker:
	
	- Verá una lista titulada *Nombre del diseño de código de barras*, allí podrá seleccionar un diseño ya creado para modificarlo o visualizarlo.
		- Si desea modificar un diseño, seleccionelo en la lista y haga click en el botón |wzedit.bmp|
		- Si desea crear un nuevo, haga click en el botón |plus.bmp|
		- Si dese eliminar un diseño, seleccionelo en la lista y haga click en el botón |delete.bmp|
	- La etiqueta está conformada por un encabezado y un cuerpo. Usted dispone de 2 espacios en el encabezado y 8 en el cuerpo (divididos en grupos de 2).
	- Usted puede elegir entre 15 características de producto para mostrar en la etiqueta. 
	- Para agregar un valor/característica a la etiqueta:
		- Verá 4 cajas vacías en la derecha, dos para el encabezado y 3 para el cuerpo. 
		- Arrastre los elementos desde la lista en la izquierda hacia las cajas de la derecha. En cada caja caben dos elementos. Necesitará mínimo 1 elemento en el cuerpo para poder guardar los cambios.
		- Si le interesa subir o bajar un elemento en el cuerpo o el encabezado, haga click sobre él y manténgalo presionado, luego deslicelo sin soltar el botón del mouse hacia donde lo necesita.

	.. figure:: images/54.png
     		:align: center

	- Para eliminar un elemento de las cajas, haga click sobre él y presione la tecla Supr.
	- Si está modificando o creando una etiqueta nueva, presione |save.bmp| para guardar los cambios o el nuevo diseño.





.. |pdf_logo.gif| image:: /_images/generales/pdf_logo.gif
.. |excel.bmp| image:: /_images/generales/excel.bmp
.. |codbar.png| image:: /_images/generales/codbar.png
.. |printer_q.bmp| image:: /_images/generales/printer_q.bmp
.. |calendaricon.gif| image:: /_images/generales/calendaricon.gif
.. |gear.bmp| image:: /_images/generales/gear.bmp
.. |openfolder.bmp| image:: /_images/generales/openfold.bmp
.. |library_listview.bmp| image:: /_images/generales/library_listview.png
.. |plus.bmp| image:: /_images/generales/plus.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp
.. |wznew.bmp| image:: /_images/generales/wznew.bmp