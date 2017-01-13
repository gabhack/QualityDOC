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
	- Haga click en el pie de la ventana en el botón |nuevo.bmp| *nuevo*

 			.. figure:: images/24.png
      			:align: center

	- Verá una ventana emergente con los siguientes campos:
		- *Resolución destinada para el almacén:* La resolución debe ir relacionada con un almacen (una por sucursal) o puede ser compartida (dos puntos de venta en la misma sucursal)
		- *No Resolución:* Entregado por la DIAN
		- *Fecha:* Fecha de expedición
		- *Vence:* De acuerdo a la ley, se suma a la fecha de expedición el tiempo correspondiente
		- *Prefijo:* Una empresa tiene una sola resolución, pero puede usar prefijos para distinguir la facturación de una sucursal a otra.
		- *Rango de Facturación:*
			- *Inicial:* Primer número de factura
			- *Final:* Último número de factura posible, habilitado por la DIAN
			- *Factura Actual:* El software empieza a facturar a partir de este número.
			- *Tipo:* Elegir según corresponda en la resolución.
		- *Esta resolución aplica como resolución manual:* Márquela si tiene un respaldo manual para el proceso de facturación. Idealmente se designa una resolución solo para ese talonario.
		- *Resolución Activa:* Márquela si está en actual uso.
		- *Mostrar ceros a la izquierda:* Márquela si desea que en la factura impresa aparezcan o no, los ceros a la izquierda.
		- Haga click en el botón |save.bmp| *guardar*

Eliminar una Resolución de facturación
======================================

	- Ejecute la opción "Administración de resoluciones de facturación"
	- Seleccione en la grilla haciendo click con el mouse sobre la Resolución que desea eliminar
	- Pulse sobre |delete.bmp| *eliminar* al pie de la ventana 
	- Pulse aceptar en la ventana de confirmación

	.. Note:

		No se pueden eliminar resoluciones que ya tengan un proceso de facturación iniciado, si desea dejarla de usar entonces desactivela. Para desactivarla desmarque la casilla 'Resolución activa' en la configuración de la resolución en `Modificar una Resolución de facturación`_

Modificar una Resolución de facturación
=======================================

	- Ejecute la opción "Administración de resoluciones de facturación"
	- Seleccione en la grilla haciendo click con el mouse sobre la Resolución que desea modificar
	- Pulse sobre |wzedit.bmp| *modificar* al pie de la ventana 
	- Cambie los campos que necesite y pulse |save.bmp| *guardar*

Auditoría de consecutivos de facturas
======================================

Use esta ventana para vigilar cualquier salto en la numeración de las facturas, ya sea por tener facturas anuladas o faltantes.

	- Ejecute la opción "Administración de resoluciones de facturación"
	- En el pie de la ventana, pulse el botón "Auditoría de consecutivos de facturas"
	- En la ventana emergente seleccione el centro de costo donde desea hace rel analisis
	- Seleccione la resolución en el cuadro superior marcando la casilla de verificación al principio de la fila.
	- Inicie el Analisis haciendo click en el botón 'Iniciar Analisis'
	- Podrá observar en la grilla los documentos faltantes o facturas anuladas, a que resolución pertenecen y alguna anotación. Puede filtrar los reusltados en la grilla como 'Anuladas', 'Inexistentes' o 'Todos'.

 .. figure:: images/25.png
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