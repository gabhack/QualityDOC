========================
Devolución de mercancías
========================

Ubicación
=========

:Módulo:
  Ventas

:Grupo:
 Procesos

:Descripción:
  Devolución de mercancías


Introducción
============

En esta operación usted podrá registrar la devolución de mercancías por parte del cliente en base a una venta hecha anteriormente. A partir de allí podrá generar saldo a favor del cliente o cruzar sus cuentas por pagar con una nota de crédito. 

* Los combos y presentaciones se regresan completos y no separando los productos que les conforman.



Pre-requisitos
==============

	- Haber realizado una venta
	- Conocer algún dato que identifique la venta a la que se desea registrar una devolución

Casos de uso (Ejemplos)
=======================

Ejemplo caso 1:

ClienteEjemplo desea devolver un artículo parte de una compra que realizó en efectivo hace algunos días. No devolverá la totalidad de la compra sino un artículo cuyo costo es 10.000 pesos. ClienteEjemplo **no tiene** cuentas por pagar pendientes. Su compañía deberá registrar esta devolución siguiendo los pasos indicados en “Devolución de mercancías”.

El cliente quedará con un saldo a favor de 10mil pesos.

Ejemplo caso 2:

ClienteEjemplo desea devolver un artículo parte de una compra que realizó en efectivo hace algunos días. No devolverá la totalidad de la compra sino un artículo cuyo costo es 10.000 pesos. ClienteEjemplo **tiene** cuentas por pagar pendientes por otras compras. Su compañía deberá registrar esta devolución siguiendo los pasos indicados en “Devolución de mercancías”.

En este caso, se procesa una nota crédito de manera automática por el valor del artículo devuelto (10.000). Se cruzarán los 10mil pesos con sus cuentas pendientes, haciendo una reducción de la deuda. 

Si la deuda de ClienteEjemplo es menor a 10mil pesos, se reconocerá la diferencia como saldo a favor por devoluciones. 

Ejemplo caso 3:

ClienteEjemplo desea devolver un artículo parte de una compra que realizó **A crédito** hace algunos días. No devolverá la totalidad de la compra sino un artículo cuyo costo es 10.000 pesos. ClienteEjemplo **no tiene** cuentas por pagar pendientes por otras compras. Su compañía deberá registrar esta devolución siguiendo los pasos indicados en “Devolución de mercancías”.

En este caso, se procesa una nota crédito de manera automática por el valor del artículo devuelto (10.000). Se restarán los 10mil pesos de su cuenta pendiente, haciendo una reducción del monto de la deuda. 


Procesar una devolución de mercancía
====================================

Para procesar una devolución realice los siguientes pasos:

	- Ejecute la opción *Devolución de mercancías*
	- Seleccione el centro de costo en el que realizó la venta 
	- Presione el botón  |buscar.bmp| *buscar*

	** Se desplegará una ventana que le permitirá buscar la factura en la que estará basada la devolución **

	   		.. figure:: images/devoluciones/1.png
 			      :align: center


	- En la ventana desplegada aparecerán varias opciones marcables que le ayudarán a encontrar la factura que desea:

		- Número de factura
		- Nombre del cliente/cédula/NIT
		- fecha de la Factura
		- Nombre del producto/código/referencia/cód de barras
		- Código rápido
		- Precio de venta

	- Seleccione cualquiera para desplegar un cuadro de texto y digitar la información requerida
	- Presione  |buscar.bmp| *buscar factura*
	- Aparecerán todas las facturas relacionadas a sus terminos de búsqueda en pantalla.
	- Marque la factura que desea, y haga click en  |btn_ok.bmp| *seleccionar factura*

		   .. figure:: images/devoluciones/2.png
	 	        :align: center


	**Volverá a la pantalla inicial de devolución** 

	- Verá los productos relacionados a la factura en el grid. Seleccione los que fueron devueltos por el cliente. 
		   .. figure:: images/devoluciones/3.png
 			    :align: center

	- Verifique los montos y presione |save.bmp| *guardar*

		   .. figure:: images/devoluciones/4.png
 			   :align: center


	- Si el cliente adjudicado en la factura es 'Cuantías menores', el sistema le pedirá otro cliente como responsable por la devolución, en caso de agregar saldo a favor o cruzar con alguna deuda, se hará con el nuevo cliente seleccionado.
	- En una ventana emergente podrá escribir una jutificación o una observación relacionada a la devolución. Presione F2 o pulse el botón |btn_ok.bmp| *aceptar*


	.. Note:

	Si el cliente tiene cuentas por pagar, verá una ventana de confirmación con los saldos por factura y la posibilidad de marcarlos para abonar el monto de la devolución a la deuda.

		 .. figure:: images/devoluciones/5.png
 			   :align: center
-----------------------------------------





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