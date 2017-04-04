========================
Parametrización contable
========================

Ubicación
=========

:Módulo:
 Contabilidad

:Grupo:
 Parámetros

:Descripción:
  Parametrización contable

Introducción
============

Esta opción le permitirá alinear la contabilidad con los procesos administrativos. Encuentre en cada pestaña la configuración de los parametros que le permitirán llevar una contabilidad sana y al día. 

Aquí podrá: 

	- Ajustar el plan de cuentas
	- Relacionar los procesos a las fuentes contables creadas
	- Ajustar los parametros necesarios para las transacciones automáticas del inventario
	- Alinear las cuentas contables a los procesos de ventas y devoluciones de ventas
	- Alinear las cuentas contables a las cajas y cuentas bancarias
	- Alinear las cuentas contables con los procesos de ventas, de cuadre de cajas y de utilidad
	- Alinear las cuentas contables a las cuentas por pagar en cualquiera de sus conceptos
	- Alinear las cuentas contables relacionadas a nómina
	- Configurar los parametros relacionados al pago de la nómina, la salud y beneficios al trabajador
	- Aplican otras configuraciones generales referentes al funcionamiento del sistema 

Contabilidad
============

Ajustar el plan único de cuentas (PUC)
--------------------------------------

	- Ejecute la opción "Parametrización contable"
	- Haga click en la pestaña 'Contabilidad'
	- En la lista '¿qué parámetros desea configurar?' seleccione la opción 'Plan único de cuentas PUC'
	- Siga las instrucciones contenidas en `PUC <../generalidades/act_cuentas_gen.html>`_

		.. figure:: images/parametrizacion/1/1.png
 			:align: center

Asignar fuentes contables a procesos
------------------------------------

	- Ejecute la opción "Parametrización contable"
	- Haga click en la pestaña 'Contabilidad'
	- En la lista '¿qué parámetros desea configurar?' seleccione la opción 'Fuentes contables'
	- A la izquierda obervará el listado de procesos del sistema y a la derecha las fuentes contables que puede asignar


		.. figure:: images/parametrizacion/1/2.png
 			:align: center

*Si necesita crear una nueva fuente contable, puede hacerlo dando click al botón 'Administrador de fuentes contables' en la parte inferior de la ventana*

Inventario
==========

Parametros generales de inventarios
-----------------------------------
	
	- Ejecute la opción "Parametrización contable"
	- Haga click en la pestaña 'Inventario'
	- En la lista '¿qué parámetros desea configurar?' seleccione la opción 'Parámetros generales'


		.. figure:: images/parametrizacion/2/1.png
 			:align: center

	- Haga click en |wzedit.bmp| *Modificar parámetros*
	- En esta opción encontrará:
		- Transferencias en cola: Cuando realiza transferencias con confirmación se crea una cola de espera hasta que el centro de costo haga el proceso de recibimiento de los productos. En esta opción, puede indicar el número de transacciones que puede haber en cola.
		- Controlar variación de costo: Posiblemente quiera establecer un valor máximo de aumento en el costo para enviar una señal de alerta y no pasar este incremento desapercibido
		- Conceptos para la aplicación de toma de inventario: Quality le permite a hacer tomar de inventario y ajustarlo de acuerdo a los resultados. Estos ajustes requieren de ingresos o egresos de mercancía automáticos según las diferencias entre el inventario físico y la toma. Especifique aquí los conceptos que se tomarán para esos ingresos y egreso de artículos
	- Una vez modificadas las cuentas, haga click en |save.bmp| *Guardar parámetros*

Parametros de Ventas
--------------------

	- Ejecute la opción "Parametrización contable"
	- Haga click en la pestaña 'Inventario'
	- En la lista '¿qué parámetros desea configurar?' seleccione la opción 'Parámetros de Ventas'


		.. figure:: images/parametrizacion/2/2.png
 			:align: center

	- Verá una grilla con una fila por cada línea de productos en su catalogo, ejemplo de una tienda por departamentos: computación, juguetes, papelería. Verá tres columnas al final de la fila que indican la cuenta relacionada a: Ingreso, costo x ventas e inventarios
	- Si quiere agregar/cambiar una cuenta haga click en el botón:|wzedit.bmp| *Modificar* parámetros para que las celdas se vuelvan modificables
	- ELija, según la fila y la columna, la cuenta que desea agregar/modificar haciendo click, borrando el valor actual (si lo tiene) y presionando Enter.
	- Verá un listado de las cuentas contables en su PUC, seleccione cualquiera haciendo click sobre ella y luego Enter
	- Una vez modificadas las cuentas, haga click en |save.bmp| *Guardar parámetros*

	Usar filtros al elegir cuentas
	******************************

	Si no desea ver todas las cuentas al momento de elegir, puede usar los filtros de la derecha.

		- Elija el filtro según la columna de cuentas (Ingresos,costos o inventario) haciendo click en el botón correspondiente.
		- Se desplegará una ventana "Configuración de filtros personalizados", en la grilla observará los filtros que funcionan sobre las celdas de la columna elegida
		- Si desea verlas todas, entonces quite todos los filtros haciendo click sobre ellos y luego presione suprimir
		- Si desea ver un número limitado de cuentas al hacer Enter sobre la celda, entonces haga click en la lista superior, allí verá todas las cuentas contables desde su clase hasta su auxiliar, seleccione la rama madre de las que desea ver luego en el listado, presione |plus.bmp|
			- *Ejemplo:* Si solo desea ver las cuentas contenidas en 'Pasivos' entonces seleccione el Item '2 PASIVO'. Estas serán las únicas cuentas visibles al cambiar una cuenta en la grilla (De la columna en la que se está aplicando el filtro)
		- Verá todos los filtros en la grilla, puede cerrar la ventana


		.. figure:: images/parametrizacion/filtros.png
 			:align: center


Parametros de devolución de ventas
----------------------------------


	- Ejecute la opción "Parametrización contable"
	- Haga click en la pestaña 'Inventario'
	- En la lista '¿qué parámetros desea configurar?' seleccione la opción 'Parámetros de devolución de Ventas'


		.. figure:: images/parametrizacion/2/3.png
 			:align: center

	- Verá una grilla con una fila por cada línea de productos en su catalogo, ejemplo de una tienda por departamentos: computación, juguetes, papelería. Verá tres columnas al final de la fila que indican la cuenta relacionada a: Devolución, costo x ventas e inventarios
	- Si quiere agregar/cambiar una cuenta haga click en el botón:|wzedit.bmp| *Modificar parámetros* para que las celdas se vuelvan modificables
	- ELija, según la fila y la columna, la cuenta que desea agregar/modificar haciendo click, borrando el valor actual (si lo tiene) y presionando Enter.
	- Verá un listado de las cuentas contables en su PUC, seleccione cualquiera haciendo click sobre ella y luego Enter
	- Una vez modificadas las cuentas, haga click en |save.bmp| *Guardar parámetros*

	Usar filtros al elegir cuentas
	******************************

	Si no desea ver todas las cuentas al momento de elegir, puede usar los filtros de la derecha.

		- Elija el filtro según la columna de cuentas (Devoluciones,costos o inventario) haciendo click en el botón correspondiente
		- Se desplegará una ventana "Configuración de filtros personalizados", en la grilla observará los filtros que funcionan sobre las celdas de la columna elegida
		- Si desea verlas todas, entonces quite todos los filtros haciendo click sobre ellos y luego presione suprimir.
		- Si desea ver un número limitado de cuentas al hacer Enter sobre la celda, entonces haga click en la lista superior, allí verá todas las cuentas contables desde su clase hasta su auxiliar, seleccione la rama madre de las que desea ver luego en el listado, presione |plus.bmp|
			- *Ejemplo:* Si solo desea ver las cuentas contenidas en 'Pasivos' entonces seleccione el Item '2 PASIVO'. Estas serán las únicas cuentas visibles al cambiar una cuenta en la grilla (De la columna en la que se está aplicando el filtro)
		- Verá todos los filtros en la grilla, puede cerrar la ventana.

			.. figure:: images/parametrizacion/filtros.png
 			   :align: center

Tesorería
=========

	- En esta interfaz podrá decidir:
		- Pedir documento físico para: Comprobantes de egresos y recibos de caja.
		- Usar la caja menor sólo desde su propio módulo
		- Permitir cruzar saldos a favor (notas credito, anticipos) de un centro de costo en otro

		     .. figure:: images/parametrizacion/3/1.png
 			     :align: center

Cuenta de cajas
---------------

	- Ejecute la opción "Parametrización contable"
	- Haga click en la pestaña 'Tesorería'
	- En la lista '¿qué parámetros desea configurar?' seleccione la opción 'Cuenta de cajas'
	- Verá una grilla con una fila por cada Caja en su centro de costo. Verá tres columnas al final de la fila que indican la cuenta relacionada a: efectivo, tarjetas, cheques.
	- Si quiere agregar/cambiar una cuenta haga click en el botón:|wzedit.bmp| *Modificar parámetros* para que las celdas se vuelvan modificables
	- ELija, según la fila y la columna, la cuenta que desea agregar/modificar haciendo click, borrando el valor actual (si lo tiene) y presionando Enter.
	- Verá un listado de las cuentas contables en su PUC, seleccione cualquiera haciendo click sobre ella y luego Enter.
	- Una vez modificadas las cuentas, haga click en |save.bmp| *Guardar parámetros*

	Usar filtros al elegir cuentas
	******************************

	Si no desea ver todas las cuentas al momento de elegir, puede usar los filtros de la derecha

		- Elija el filtro según la columna de cuentas (efectivo, tarjetas, cheques) haciendo click en el botón correspondiente
		- Se desplegará una ventana "Configuración de filtros personalizados", en la grilla observará los filtros que funcionan sobre las celdas de la columna elegida
		- Si desea verlas todas, entonces quite todos los filtros haciendo click sobre ellos y luego presione suprimir.
		- Si desea ver un número limitado de cuentas al hacer Enter sobre la celda, entonces haga click en la lista superior, allí verá todas las cuentas contables desde su clase hasta su auxiliar, seleccione la rama madre de las que desea ver luego en el listado, presione |plus.bmp|
			- *Ejemplo:* Si solo desea ver las cuentas contenidas en 'Pasivos' entonces seleccione el Item '2 PASIVO'. Estas serán las únicas cuentas visibles al cambiar una cuenta en la grilla (De la columna en la que se está aplicando el filtro)
		- Verá todos los filtros en la grilla, puede cerrar la ventana

			.. figure:: images/parametrizacion/filtros.png
 			   :align: center

Cuentas bancarias
-----------------

	- Ejecute la opción "Parametrización contable"
	- Haga click en la pestaña 'Tesorería'
	- En la lista '¿qué parámetros desea configurar?' seleccione la opción 'Cuentas bancarias'

		.. figure:: images/parametrizacion/3/2.png
 			:align: center

	- Seleccione el centro de costo
	- Verá una grilla con una fila por cada cuenta bancaria en su centro de costo. 
	+------------+---+------+----+----------------+--------+------+---+
	|nombre banco|nit|código|tipo|número de cuenta|Contable|activa|   |
	+------------+---+------+----+----------------+--------+------+---+
	- Marque la casilla 'Activa' si desea que la cuenta bancaria esté disponible para el centro de costo elegido anteriormente.

Ventas
======

	En la pestaña "Ventas" podrá modificar los siguientes parametros, haciendo click en |wzedit.bmp|:

	- Cliente de contado: Seleccione el cliente que no necesita especificaciones y facilita la venta de contado.
	- Impuesto por defecto a las ventas
	- Cuentas contables para:
		- Cuenta crédito
		- Cuenta de anticipos de clientes
		- Cuenta de nota de crédito por devoluciones
		- Cuenta de ReteICA para ventas
		- Cuenta de Utilidad
		- Cuenta de perdida
		- Cuenta de ajuste al peso (favor)
		- Cuenta de ajuste al peso (contra)
	-Conceptos para:
		- Recibo para cuadre 
		- Egreso para cuadre 
		- Prestamos a empleados
		- Prestamos a terceros 
		- Nota débito por devolución de cheques
	- Otras opciones:
		- Actualizar lista de precios automáticamente al comprar y transferir productos
		- Requerir cupo de crédito para ventas a crédito
		- Permitir repetir Serial/IMEI/DOT al realizar una factura 
		- Permitir devoluciones a un centro de costo diferente a donde se generó la venta
		- Contabilizar retenciones en tarjetas de manera automática
		- Hacer coincidir fecha de transacciones con la fecha del servidor
		- Redondear decimales en factura de venta

		.. figure:: images/parametrizacion/4/1.png
 			:align: center

Cuentas por pagar (CxP)
=======================

	En esta pestaña puede modificar haciendo click en el botón |wzedit.bmp| *Modificar parámetros*, las cuentas relacionadas a los procesos administrativos de las compras:

		- ReteICA para compras
		- Cuentas por pagar (Compras)
		- Cuentas por pagar (causación)
		- Cuentas de anticipos a proveedores
		- Cuenta de fletes en compras
		- Cuenta de ICO para compras
		- Concepto de retención de IVA por compras al régimen simplificado

Elija tambien si desea realizar una auditoría de saldos de cuentas por pagar después de cada transacción

		.. figure:: images/parametrizacion/5/1.png
 			:align: center

Nómina
======

En esta pestaña podrá modificar haciendo click en el botón |wzedit.bmp| *Modificar parámetros* las cuentas contables y otras opciones relacionadas a la nómina:

	- El centro de costo donde se hace el gasto de nómina
	- Cuenta contable por pagar a empleados
	- Cuenta de prestamos a empleados
	- Cuenta de vacaciones por pagar
	- Cuenta de primas por pagar



Generales
=========

	En la pestaña "Generales" encontrará las opciones correspondientes a:

		- Numerar menú principal
		- Forzar digitación de la base de IVAS & RETENCIONES
		- Simplifitcar creación de productos asumiendo mismo IVA para compras y ventas
		- Manejar inventario por tallas
		- Utilizar acumuladores para almacenar saldos de cuentas contables
		- Patrones para estadisticas:
			-Basar las estadisticas que impliquen vendedores en:
				- Vendedor registrado en el cliente
				- El Vendedor registrado en el documento
			- Basar las estadisticas que impliquen zonas en:
				- Zona registrada en el vendedor
				- Zona registrada en el cliente
				- Zona registrada en el documento
		- Fecha mínima para el control de transacciones (Por defecto la de instalación del sistema)
		- Al realizar una transacción de caja o banco: Registrar el tercero que realiza a transacción o registrar el NIT de la empresa.
		- Configuración de consolidación:
			- No
			- Siempre
			- Preguntar
		- Interfaces operativas:
			- Implementar interfaces para la facturación basada en AIU
			- Impleentar interfaces de propiedad horizontal
			- Implementar interfaces de producción
		- Actualización: Actualizar siempre que haya una nueva versión













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

