===============
Recibos de caja
===============

Ubicación
=========

:Módulo:
 Tesoreria

:Grupo:
 Procesos

:Descripción:
  Recibos de caja


Introducción
============

	Use esta operación para registrar los ingresos en un centro de costo por motivo de *Recaudos de cartera* (Abono de venta a crédito) o *Recaudos por conceptos* (Anticipos de clientes, intereses, pago de prestamos a terceros, etc).

	Especifique además el tipo de pago (tarjetas, cheque, efectivo). Si el receptor es directamente una cuenta bancaria, el único medio que podrá escoger será efectivo.

	En los *recaudos de cartera*, podrá mezclar varios recaudos y agregar otros conceptos.


Pre-requisitos
==============

	Para hacer un recibo de caja por recaudos de cartera deberá:

		- Tener una hecha una venta a crédito a un cliente
		- Haber registrado un cliente
		- Haber configurado una caja
		- Haber configurado una cuenta bancaria


Crear un recibo de caja
=======================

Siga estos pasos antes de especificar de que tipo de recaudo se trata:

	- Ejecute la opción "Recibo de caja"
	- En la lista "Almacen" seleccione el centro de costo correspondiente
	- En la lista "Caja" escoja la caja o la cuenta bancaría en la que entrará el dinero.
	- Escoja el tipo de recaudo:
		- `Crear un recibo de caja por Recaudos de Cartera (Pago de venta a crédito)`_
		- `Crear un recibo de caja por Recaudos por conceptos (Anticipos de clientes, etc)`_

Crear un recibo de caja por Recaudos de Cartera (Pago de venta a crédito)
=========================================================================

			.. figure:: images/recibos/1.png
 				 :align: center 


	- Seleccione la pestaña "Recaudos de Cartera"
	- En el cuadro de texto "Cédula" Digite la cédula o presione Enter para buscarlo. Solo podrá visualizar clientes que hayan hecho una compra a crédito. Elija el cliente que realiza el abono.
	- Al reyenar el cuadro de texto "Abono" entonces se irá agregando esa cantidad a las facturas en el orden en el que aparecen en la grilla. Si seleccione las facturas en la grilla, el cuadro de abono se rellena automáticamente con el total del monto. **El campo Vr. Recibo es editable, aquí puede especificar manualmente el monto que va a ser pagado de cada factura**
	- Verá una grilla de menor tamaño donde puede agregar algún otro abono por otros conceptos, opcionalmente. Use esta opción si además del pago de la factura existe algun recargo o un anticipo.
	- En el campo de texto "Observación" agregue información que le pueda ser útil en un futuro.
	- Presione guardar y elija el (los) metodo(s) de pago. Si ha seleccionado ingresar el dinero a una cuenta bancaria, solo podrá seleccionar efectivo.
	- Presione F2 para procesar la transacción.

Crear un recibo de caja por Recaudos por conceptos (Anticipos de clientes, etc)
===============================================================================

			.. figure:: images/recibos/2.png
 				 :align: center 


	- Seleccione la pestaña "Recaudos por conceptos"
	- En el cuadro de texto "C.C. o NIT" Digite el NIT o presione Enter para buscarlo. Elija el cliente que realiza el abono.
	- Haga click en la primera casilla de la columna código en la grilla y presione Enter. Verá en una ventana algunos conceptos por los cuales un cliente podría estar haciendo un abono. Puede crear nuevos conceptos en "Administrador de conceptos de tesorería" del cual encontrará un acceso directo más abajo. Algunos conceptos requieren de la creación de un tercero; puede acceder a la "administración de terceros" más abajo.
	- Puede ingresar varios conceptos a la vez.
	- Presione |save.bmp| para elegir el metodo de pago. Verá desplegarse una ventana donde podrá elegir los metodos de pago correspondientes al abono. Si ha seleccionado ingresar el dinero a una cuenta bancaria, solo podrá seleccionar efectivo.
	- Presione F2 para procesar la transacción.



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