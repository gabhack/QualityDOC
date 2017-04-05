=====================
Cuadre diario de caja
=====================

Ubicación
=========

:Módulo:
  Ventas

:Grupo:
 Procesos

:Descripción:
  Cuadre diario de caja


Introducción
============

	Con este proceso se lleva a cabo una comprobación de la cantidad de dinero (en cualquiera de sus modos: efectivo, cheque, tarjetas) comparándolo con las cantidades en sistema. 

	El proceso hace el cierre del día y hace la apertura hacia una fecha siguiente. No podrá hacer una nueva apertura hasta que no se haga el cierre de la última hecha.

	Se puede revertir un cuadre si la persona tiene los permisos adecuados

Pre-requisitos
==============

	- Un vendedor
	- Centro de Costo
	- Una caja


Cuadrar la caja
===============

	Para cuadrar la caja realice los siguientes pasos:

	- Ejecute la opción 'Cuadre diario de caja'
	- Seleccione en la cabecera el centro de costo donde desea cuadrar la caja
	- Seleccione la caja pertinente
	- Seleccione la fecha de cuadre (está elegida la última fecha de apertura por defecto) y presione enter para habilitar los campos.
	- En el campo "Efectivo" introduzca la cantidad de efectivo real.
	- En el campo "Tarjetas" introduzca el monto tramitado a través de tarjetas de débito o crédito.
	- En el campo "Cheques" introduzca el monto tramitado a través de cheques.
	- Una vez verificados los montos, presione el botón |btn_ok.bmp| *cerrar caja*
	- Se desplegará una ventana donde podrá hacer alguna anotación u observación acerca del cuadre. Presione F2 o pulse el botón |btn_ok.bmp| *aceptar*
	- Verá una ventana donde podrá seleccionar la fecha de la apertura siguiente, elíjala y presione |save.bmp| *procesar*
	- Se emitirá un comprobante de la transacción.

	Una vez haga el cierre de caja, podrá visualizar las transacciones desde la apertura de la caja, en pantalla. Si necesita modificar la observación puede hacerlo presionando el botón |wzedit.bmp|

   .. figure:: images/5.png
 	   :align: center

Opciones de salida
------------------

	- |pdf_logo.gif| PDF 
	- |printer_q.bmp| Reporte


Consultar un cuadre de caja
===========================

	- Ejecute la opción 'Cuadre diario de caja'
	- Seleccione en la cabecera el centro de costo 
	- Seleccione la caja pertinente
	- Seleccione la fecha del cuadre a consultar (está elegida la última fecha de apertura por defecto) y presione enter, verá desplegarse la información  acerca de la relación de ingresos y egresos.

   .. figure:: images/6.png
 	   :align: center

Revertir un cuadre de caja
==========================

.. NOTE::

Debe tener los permisos necesarios para realizar esta acción. Solo puede revertir el último cuadre de caja.
	
	- Siga los pasos para `Consultar un cuadre de caja`_ 
	- Haga click en el botón |descartar.bmp| *Deshacer*

   .. figure:: images/7.png
 	  :align: center

---------------------------------------------------------


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