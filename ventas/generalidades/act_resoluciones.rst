=============================================
Administración de resoluciones de facturación
=============================================

Ubicación
=========

:Módulo:
 Ventas

:Grupo:
 Parámetros

:Descripción:
   Administración de resoluciones de facturación

Introducción
============

En *Administración de resoluciones de facturación* podrá dar inicio a una resolución obtenida a través de la DIAN que le permite facturar en un rango determinado de números de factura.

Puede marcar la opción en la cabecera 'Mostrar únicamente resoluciones vigentes' para que en la grilla solo aparezcan las resoluciones que no están vencidas o cuyo rango de facturación no se ha acabado.

Visualizar resoluciones creadas
===============================

	- Ejecute la opción "Administración de resoluciones de facturación"
	- Seleccione en la cabecera de la ventana el centro de costo 
	- Verá en la grilla las *resoluciones* que se encuentran asociadas a este centro. La casilla de verificación indica si la resolución está o no en uso.

Crear una Resolución de facturación
===================================

	- Ejecute la opción "Administración de resoluciones de facturación"
	- Haga click en el pie de la ventana en el botón 'Nuevo' |nuevo.bmp|
	- Verá una ventana emergente con los siguientes campos:
		- *Resolución destinada para el almacén:* La resolución debe ir relacionada con un almacen (una por sucursal) o puede ser compartida (dos puntos de venta en la misma sucursal)
		- *No Resolución:* Entregado por la DIAN
		- *Fecha:* Fecha de expedición
		- *Vende:* De acuerdo a la ley, se suma a la fecha de expedición el tiempo correspondiente
		- *Prefijo:* Una empresa tiene una sola resolución, pero puede usar prefijos para distinguir la facturación de una sucursal a otra.
		- *Rango de Facturación:*
			- *Inicial:* Primer número de factura
			- *Final:* Último número de factura posible, habilitado por la DIAN
			- *Factura Actual:* El software empieza a facturar a partir de este número.
			- *Tipo:* Elegir según corresponda en la resolución.
		- *Esta resolución aplica como resolución manual:* Márquela si tiene un respaldo manual para el proceso de facturación. Idealmente se designa una resolución solo para ese talonario.
		- *Resolución Activa:* Márquela si está en actual uso.
		- *Mostrar ceros a la izquierda:* Márquela si desea que en la factura impresa aparezcan o no, los ceros a la izquierda.
		- Haga click en el botón 'Guardar' |save.bmp|

Eliminar una Resolución de facturación
======================================

	- Ejecute la opción "Administración de resoluciones de facturación"
	- Seleccione en la grilla haciendo click con el mouse sobre la Resolución que desea eliminar
	- Pulse sobre 'eliminar' al pie de la ventana |delete.bmp|
	- Pulse aceptar en la ventana de confirmación

	.. Note:

		No se pueden eliminar resoluciones que ya tengan un proceso de facturación iniciado, si desea dejarla de usar entonces desactivela. Para desactivarla desmarque la casilla 'Resolución activa' en la configuración de la resolución en `Modificar una Resolución de facturación`_

Modificar una Resolución de facturación
=======================================

	- Ejecute la opción "Administración de resoluciones de facturación"
	- Seleccione en la grilla haciendo click con el mouse sobre la Resolución que desea modificar
	- Pulse sobre 'modificar' al pie de la ventana |wzedit.bmp|	
	- Cambie los campos que necesite y pulse 'guardar' |save.bmp|


































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