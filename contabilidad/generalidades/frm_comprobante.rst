==============================
Administración de comprobantes
==============================

Ubicación
=========

:Módulo:
 Contabilidad

:Grupo:
 Parámetros

:Descripción:
  Actualización de comprobantes

Introducción
============

	A través de la interfaz *Actualización de comprobantes* usted podrá realizar asientos contables manuales, listar los que el sistema hace de manera automática, editarlos y eliminarlos.

Crear un comprobante contable
=============================

	- Ejecute la opción "Actualización de comprobantes"
	- Pulse el botón |wznew.bmp| *Nuevo*

		.. figure:: images/adcomprobantes/1.png
 			:align: center


	- Elija en la lista 'Centro' el centro de costo donde realizará el asiento
	- En la lista 'Fuente' escoja la acción 'comprobante de contabilidad'
	- En el siguiente campo, coloque el cursor y presione Enter para ver el listado de cuentas contables. Seleccione una haciendo click sobre ella y luego Enter

		.. figure:: images/adcomprobantes/2.png
 			:align: center

	- Se cargará automáticamente el nombre de la cuenta en el segundo campo
	- En el tercer campo digite el número de id del tercero
	- Escoja el centro de costo en el cuarto campo (lista)
	- Escriba el detalle del movimiento
	- Escriba el saldo en el campo débito o en el campo crédito de acuerdo al asiento. El cursor se pondrá en el campo correspondiente a la naturaleza de la cuenta.

		.. figure:: images/adcomprobantes/3.png
 			:align: center

	- Pulse |plus.bmp| y vea el asiento agregarse a la grilla
	- Puede crear varios asientos y mientras que la diferencia entre la partida del crédito y del débito sea 0, usted podrá guardar el comprobante haciendo click en |save.bmp| *Guardar*

Usar los filtros de cuentas
---------------------------

Si no desea ver todas las cuentas al momento de elegir, puede usar los filtros de la derecha.

		- Elija el filtro según la operación
		- Se desplegará una ventana "Configuración de filtros personalizados", en la grilla observará los filtros que funcionan sobre las celdas de la opción elegida
		- Si desea verlas todas, entonces quite todos los filtros haciendo click sobre ellos y luego presione suprimir
		- Si desea ver un número limitado de cuentas al hacer Enter sobre la celda, entonces haga click en la lista superior, allí verá todas las cuentas contables desde su clase hasta su auxiliar, seleccione la rama madre de las que desea ver luego en el listado, presione |plus.bmp|
			- *Ejemplo:* Si solo desea ver las cuentas contenidas en 'Pasivos' entonces seleccione el Item '2 PASIVO'. Estas serán las únicas cuentas visibles al cambiar una cuenta en la grilla (De la columna en la que se está aplicando el filtro)
		- Verá todos los filtros en la grilla, puede cerrar la ventana

Editar un comprobante
=====================

	- Ejecute la opción "Actualización de comprobantes"
	- Haga click en el botón *Buscar*

		.. figure:: images/adcomprobantes/4.png
 			:align: center

	- En la ventana emergente, seleccione los filtros que considere necesarios para encontra el asiento contable que busca
	- Haga doble click sobre el asiento
	- Vera ponerse el comprobante en la grilla, para modificarlo presione |wzedit.bmp| *Editar*
	- Puede eliminar las filas del asiento y agregar nuevas para modificarlo. También puede cambiar los montos en las filas ya existentes.
	- Cuando haya terminado la modificación del comprobante, haga click en |save.bmp| *Guardar*

Exportar/Imprimir un asiento
============================ 

	- Ejecute la opción "Actualización de comprobantes"
	- Haga click en el botón *Buscar*
	- En la ventana emergente, seleccione los filtros que considere necesarios para encontra el asiento contable que busca
	- Haga doble click sobre el asiento
	- Haga click en el botón |export1.gif| *Opciones*

		.. figure:: images/adcomprobantes/6.png
 			:align: center

	- Elija el medio por el cual desea dar salida al comprobante.

.. |export1.gif| image:: /_images/generales/export1.gif
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


	