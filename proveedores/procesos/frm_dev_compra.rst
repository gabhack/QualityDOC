=====================
Devolución de compras
=====================

Ubicación
=========

:Módulo:
 Proveedores

:Grupo:
 Procesos

:Descripción:
  Devolución de compras


Introducción
============

	En esta operación usted podrá registrar la devolución de mercancías a un proveedor en base a una compra (ya radicada) hecha anteriormente. A partir de allí podrá generar saldo a su favor o cruzar sus cuentas por pagar con una nota de crédito. 

 	 		.. figure:: images/devolucion/0.png
 			    :align: center

Pre-requisitos
==============

	Para hacer una devolución deberá:

	- Haber realizado una compra
	- Conocer algún dato que identifique la compra a la que se desea registrar una devolución

Casos de uso (Ejemplos)
=======================

Ejemplo caso 1:

Usted desea devolver un artículo parte de una compra a proveedor que realizó en efectivo hace algunos días (radicó e hizo el egreso). No devolverá la totalidad de la compra sino un artículo cuyo costo es 10.000 pesos. . Usted **no tiene** cuentas por pagar pendientes. Su compañía deberá registrar esta devolución siguiendo los pasos indicados en “Devolución de compras”.

Usted quedará con un saldo a favor de 10mil pesos.

Ejemplo caso 2:

Usted desea devolver un artículo parte de una compra que realizó en efectivo hace algunos días (radicó e hizo el egreso). No devolverá la totalidad de la compra sino un artículo cuyo costo es 10.000 pesos. Usted **tiene** cuentas por pagar pendientes por otras compras. Su compañía deberá registrar esta devolución siguiendo los pasos indicados en “Devolución de compras”.

En este caso, se procesa una nota crédito de manera automática por el valor del artículo devuelto (10.000). Se cruzarán los 10mil pesos con sus cuentas pendientes, haciendo una reducción de la deuda. 

Si su deuda es menor a 10mil pesos, se reconocerá la diferencia como anticipo a proveedor.

Ejemplo caso 3:

Usted desea devolver un artículo parte de una compra que realizó **A crédito** hace algunos días. No devolverá la totalidad de la compra sino un artículo cuyo costo es 10.000 pesos. Usted **no tiene** cuentas por pagar pendientes por otras compras. Su compañía deberá registrar esta devolución siguiendo los pasos indicados en “Devolución de compras”.

En este caso, se procesa una nota crédito de manera automática por el valor del artículo devuelto (10.000). Se restarán los 10mil pesos de su cuenta por pagar pendiente, haciendo una reducción del monto de la deuda. 


Devolver una compra
===================

	Para *devolver una compra* realice los siguientes pasos:

		- Ejecute la opción "Devolución de compras"
		- En el campo 'Almacén' seleccione el centro de costo donde realizó la compra
		- Elija el intervalo de fechas en el que se realizaron la compra que desea devolver
		- En el campo 'CC o NIT' presione Enter para elegir el proveedor al que realizará la devolución

 	 		.. figure:: images/devolucion/1.png
 			    :align: center

		- En la grilla aparecerán todas las ENTRADAS POR COMPRAS RADICADAS en el intervalo de fechas y centro que eligió
		- Haga doble click en la entrada donde se encuentran los productos que devolverá
		- En la grilla aparecerán los productos relacionados a la compra, marque los que desea devolver
		- En la columna 'Devolver' digite el número de unidades compradas que devolverá
		- Puede agregar un descuento o una retención a la mercancía devuelta, haciendo click en "Agregar otros conceptos"
		- Haga click en |save.bmp| *Guardar Nota*

		 	 .. figure:: images/devolucion/2.png
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