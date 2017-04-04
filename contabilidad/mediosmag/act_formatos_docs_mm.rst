============================================================
Definición de formatos de exportación para medios magnéticos
============================================================

Ubicación
=========

:Módulo:
 Contabilidad

:Grupo:
 Medios Magneticos

:Descripción:
  Definición de formatos de exportación para medios magnéticos

Introducción
============

	Un esquema se refiere a las columnas elegidas para el formato del medio magnético. En esta interfaz podrá definir las columnas que irán en el esquema, esto significa que después de seleccionar alguno de los formatos de medio mágnetico que vienen predefinidos en el sistema, podrá elegir los datos que aparecerán en el documento.


 .. figure:: images/medios/a.png
     	:align: center


	Puede crear varios esquemas para uno de estos formatos y llamarlos diferente. Tenga en cuenta que mayoritariamente necesita un solo esquema de columnas para cada formato.

	Columnas estáticas o maestras
	-----------------------------

	Puede agregar al esquema las columnas referentes a los tipos de transacción, fechas o información acerca del tercero. Estas columnas se organizarán para proporcionar información relevante sobre las cifras contenidas en las columnas de valor. Ejemplo: Razón social del tercero, fecha, tipo de documento, etc.

	Columnas de valor
	-----------------

	Estas columnas representan los valores o el resultado de las operaciones con valores, hayados en las cuentas contables que están relacionadas con un concepto específico. Por ejemplo, una venta está relacionada a varias cuentas contables como retenciones, IVA, caja, etc. Una columna de valor puede representar estos valores sumados o de forma separada.

	Una columna de valor, al ser creada, puede definirse como un valor neto, o un valor base. 

Definir un esquema para para un formato de medio magnético
==========================================================
	
	- Ejecute la opción "Definición de formatos de exportación para medios magnéticos"
	- Elija el 'Formato de medios magnéticos'
	- Haga click en el botón |plus.bmp|

 			.. figure:: images/medios/a2.png
     			:align: center


	- El cursor se situará en el nuevo campo vacío 'Nombre del documento', escriba el nombre para el nuevo esquemaH
		- **Agregar columnnas estáticas:** En el panel izquierdo podrá ver las columnas que puede agregar arrastrandolas desde ese panel al de la derecha. El orden en el panel será el mismo orden de las columnas en el documento, puede subir cada elemento para ajustar el ordeb a sus necesidades.
			 .. figure:: images/medios/a3.png
		     	:align: center

		- **Agregar columnas de valor:** Sobre el panel derecho, presione el botón |plus.bmp| *Agregar columna de valor. En la ventana emergente indique los siguientes campos:
			- Nombre de la columna: Es importante nombrarla de manera clara y específica.
			- Valor Neteado o Valor Base: De acuerdo a sus necesidades, puede elegir si el valor de esta columna será neto o solo la base antes del impuesto.
			- Filtrar montos: El sistema le permite filtrar los valores de la columna para resumir algunos datos y filtrar con valores mínimos de monto.

			 .. figure:: images/medios/a4.png
			     	:align: center

	.. NOTE::

		ELija las fuentes contables de las cifras para las columnas de valor en la Interfaz "Formatos, conceptos & cuentas"

Editar un esquema para un formato de medio magnético
====================================================
	
	- Ejecute la opción "Definición de formatos de exportación para medios magnéticos"
	- Elija el 'Formato de medios magnéticos'
	- Escoja el esquema en la lista 'Nombre del documento'
	- Haga click en el botón |wzedit.bmp|
	- Se activarán los paneles para que pueda elegir las columnas estáticas del esquema, y las columnas de valor.

Eliminar un esquema para un formato de medio magnético
======================================================
	
	- Ejecute la opción "Definición de formatos de exportación para medios magnéticos"
	- Elija el 'Formato de medios magnéticos'
	- Escoja el esquema en la lista 'Nombre del documento'
	- Presione el botón |delete.bmp|
	- En la ventana de confirmación, pulse: 'Sí'.

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
