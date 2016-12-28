===================================
Administración de Listas de Precios
===================================

Ubicación
=========

:Módulo:
 Ventas

:Grupo:
 Parámetros

:Descripción:
  Administración de Listas de Precios

Introducción
============

Consulte aquí cómo crear, modificar y eliminar *Listas de precios*. Puede tener cuantas listas de precio desee a su conveniencia, organizadas por Centro de costo. También podrá consultar cómo etiquetar productos para clasificarlos.

Verá los productos ordenados para mostrar primeramente los que aún no tienen precio de venta, y luego los que ya lo tienen, en orden alfabético.

El costo que muestra un 'combo o presentación' está determinado por la suma de los costos de los productos que forman parte de él.


Pre-requisitos
==============

	- Solo verá productos en la *Lista de Precios* que hayan sido creados anterioremente y además hayan entrado al centro de costo (deben tener un precio de costo).
	- Podrá ver los servicios que hayan sido creados anteriormente, sin condición alguna.

Crear una Lista de Precios
==========================

Para crear una *Lista de Precios* realice los siguientes pasos:

	- Ejecute la opción *Administración de Lista de precios*

 			.. figure:: images/4.png
   				:align: center

	- En la cabecera elija el centro de costos al que irá relacionada la *Lista de Precios*
	- Haga click en el botón  |plus.bmp| *Crear una lista de precios*
	- En la ventana emergente introduzca el nombre de la nueva *Lista de precios* y presione *aceptar*

 		.. figure:: images/5.png
   			:align: center

   		.. figure:: images/6.png
  			 :align: center

	- Verá una nueva lista con todos los productos marcados en rojo (Los productos en rojo reflejan una utilidad negrativa)


		De ahora en adelante usted podrá realizar cambios en los precios de los productos reflejados en la grilla directamente en la columna **Precio de venta** y **Precio mínimo**. Estos precios se verán reflejados en en el momento de realizar la factura si ha elegido esta *Lista de Precios*

			 .. figure:: images/7.png
			   :align: center

		El **Margen de Utilidad** (%Uti - Casilla naranja) será una manera automática de establecer el precio del producto de acuerdo a un porcentaje sobre el costo.


		Aplique un **% de descuento** a los productos en la casilla de la columna '%desc'. Este descuento se basará siempre en el **precio de venta** (no en el precio mínimo).


Establecer una Lista de Precios a partir de una transacción (Documento)
=======================================================================

Podrá buscar los productos que pertenezcan a una transacción específica colocando la especificación del documento en la barra de búsqueda inteligente de la siguiente manera:

	(Tipo de documento):(Código de centro de costo):(Número de documento)

	Ejemplo:

		- **_EC:001:21400587**

 .. figure:: images/8.png
   :align: center



Establecer formas de pago a una Lista de precios
================================================

Podrá establecer formas de pago permitidas a la hora de realizar una venta usando cierta *Lista de precios*

	- Haga click en el botón |gear.bmp| *Configurar formas de pago permitidas*

		 .. figure:: images/9.png
		   :align: center

	- En la cabecera de la venta emergente seleccione la *Lista de precios*
	- Chequee las opciones que le parezcan pertinentes

		 .. figure:: images/10.png
		   :align: center

	- Haga click en 'Guardar' |save.bmp| 

Asociar un usuario del sistema a una *Lista de Precios*
=======================================================

Podrá establecer acceso seguro a las *Lista de Precios* dando permisos únicos a usuarios, o negándoles el acceso.

	- Haga click en el botón  |gear.bmp| *Configurar formas de pago permitidas*

		 .. figure:: images/9.png
		   :align: center

	- En la cabecera de la venta emergente seleccione la *Lista de precios*
	- Diríjase a la pestaña 'usuarios'
	- Ahora puede proceder a chequear los usuarios que tendrán acceso a esta lista o que serán vetados.
	- En el pie de la ventana, seleccione si desea restringir u otorgar el acceso

		 .. figure:: images/11.png
		   :align: center

	- Haga click en |save.bmp| *guardar*

Otras configuraciones de Listas de Precios
==========================================

Acceda a otros ajustes que le permitirán parametrizar y hacer más amena la facturación en ventas:

	- Haga click en el botón  |gear.bmp| *Configurar formas de pago permitidas*

		 .. figure:: images/9.png
		   :align: center

	- En la cabecera de la venta emergente seleccione la *Lista de precios*
	- Diríjase a la pestaña 'otros'
	-Luego encontrará un combo con 3 opciones:
		- Mostrar precio sin descuento (precio de venta)
		- Mostrar precio con descuento (precio mínimo)
		- Mostrar precio sin descuento y aplicar descuento automáticamente (muestra ambos)
	- Marque 'Permitir cambiar precio de venta en factura' si desea habilitar esta opción al cajero.
	- Marque 'Mostrar leyenda y precio mínimo' si desea que el cajero vea en pantalla el precio mínimo de venta.
	- Marque 'Lista de precios pública' si la lista puede ser aplicada a cualquier cliente y no a uno específico. Para asociar una lista a un cliente diríjase a `Crear o modificar un cliente <>`_
	- Marque 'No permitir precios de venta inferiores al costo' si dese inhabilitar esta posibilidad al cajero.

		 .. figure:: images/12.png
		   :align: center

Cambiar nombre a una Lista de Precios
=====================================

	- Ejecute la opción *Administración de Lista de precios*
	- En la cabecera elija el centro de costos relacionado a la *Lista de Precios*
	- Elija la *Lista de Precios*
	- Haga click en el botón |wzedit.bmp| *cambiar nombre de esta lista de precios*
	- En la ventana emergente introduzca el nuevo nombre y haga click en 'aceptar'
 

 .. figure:: images/13.png
	   :align: center

Eliminar una Lista de precios
=============================

	- Ejecute la opción *Administración de Lista de precios*
	- En la cabecera elija el centro de costos al que irá relacionada la *Lista de Precios*
	- Haga click en el botón  |delete.bmp| *Eliminar lista de precios seleccionada*
	- Haga click en 'Sí' para confirmar la eliminación

 .. figure:: images/14.png
   :align: center


Exportar información de una Lista de precios
============================================

Usted podrá dar salida a la *Lista de Precios* en dos formas:

- Lista general ordenada alfabéticamente
- Lista clasificada por líneas y sub-líneas

en los siguientes formatos:

	- |pdf_logo.gif| PDF 
	- |excel.bmp| Excel
	- |printer_q.bmp| Impresión

 .. figure:: images/15.png
   :align: center

Log de cambios en precios de venta
==================================

Por seguridad, cada cambio en los precios de su centro de costo de una lista determinada es guardada con información pertinente del usuario, producto y fecha.

	- Ejecute la opción *Administración de Lista de precios*
	- En la cabecera elija el centro de costos al que irá relacionada la *Lista de Precios* 
	- Haga click en el botón |library_listview.bmp| *Log de cambios en precios de ventas*

		 .. figure:: images/16.png
		   :align: center

	- Se desplegará una ventana donde podrá ver los cambios en todos los productos. También podrá verlos en una rango de fechas determinado. 
	- En la barra de búsqueda inteligente podrá poner información acerca del producto (nombre, parte del nombre, código, parte del código)
	- En el Combo podrá seleccionar que columnas de precios desea mostrar en la grilla.

 .. figure:: images/17.png
   :align: center

Etiquetar productos
===================

Puede remarcar productos con algún color de su preferencia si es necesario. Puede marcar un artículo o servicio como 'importante', 'en oferta', 'pendiente de revisión', etc.

Para etiquetar/desetiquetar un producto:

	- Elija el producto en la grilla marcandolo en la casilla de la última columna (puede elegir varios)
	- Presione el botón  |label.bmp| *Etiquetar productos*
	- Elija la etiqueta de que desea, o elija 'Remover TAG de los productos seleccionados' para desetiquetar.

 .. figure:: images/18.png
   :align: center


--------------------------------------------

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