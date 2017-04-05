======================================
Saldos iniciales de cuentas por cobrar
======================================

Ubicación
=========

:Módulo:
 Cartera

:Grupo:
 Procesos

:Descripción:
  Saldos iniciales de cuentas por cobrar


Introducción
============

	Use esta operación para registrar los saldos de clientes en cartera que tiene su organización hasta el momento en que empieza a usar el sistema Quality. 

	Es importante tener en cuenta que aunque se use la referencia de una factura, si el cliente ya ha abonado parte del monto, el saldo actual es el saldo inicial en cartera para ese cliente.

	Debe incluir a un cliente tantas veces como faturas por pagar él tenga. Puede entrar a esta pantalla siempre que sea necesario para decretar una cuenta por cobrar inicial a un cliente.

	Esta interfaz le permite elegir las cuentas que afectarán estos saldos iniciales, incluyendo la contrapartida. 

	**En la parte de abajo de la ventana, podrá visualizar una grilla resumen, donde verá de manera no detallada los totales en deuda por cliente.**

		.. figure:: images/saldos.png
 			:align: center

Pre-requisitos
==============

	Para hacer una nota deberá:

		- Tener un cliente, al menos.
		- Tener la información necesaria para los datos acerca de la cuenta por cobrar: monto, documento, fecha de corte, etc.
		- Tener las cuentas contables necesarias creadas



Ingresar un saldo inicial por cobrar a cliente
==============================================

Realice los siguientes pasos:

	- Ejecute la opción "Saldos iniciales de cuentas por cobrar"
	- Elija el Centro de costo
	- Elija la cuenta de cartera que se verá afectada en la lista 'cta cartera'
	- Seleccione la cuenta de contrapartida por defecto, para todos los movimientos ingresados, en la lista 'contrapartida'
	- Ahora podrá iniciar la inserción de saldos a la grilla
		- Haga click en la primera casilla de la columna 'código' y presione Enter. Ahora podrá seleccionar alguno de los clientes en la lista.
		- El siguiente campo {_FC, _ND} indica el tipo de cuenta por cobrar, si se refiere a una factura a crédito o a una nota débito.
		- Introduzca ahora el número o la referencia del documento que respalda la deuda del cliente
		- Introduzca la fecha en que fue adquirida la deuda (se generó la factura o la nota) y luego la feha de corte para pagarla.
		- Elija una cuenta contable específica a afectar como contrapartida. Si no lo hace, tomará la elegida en el paso 4.
		- Elija al vendedor que realizo la factura, si lo desea
		- Ingrese el monto de la cuenta por cobrar
		- Presione Enter. Ahora puede elegir introducir otra cuenta por cobrar de otro cliente o de este mismo. Si no tiene más cuentas por cobrar entonces pulse el botón |save.bmp| 'Guardar Facturas'



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