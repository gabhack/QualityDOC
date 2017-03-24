=============================================
Administración de Cajas, Bancos y Franquicias
=============================================

Ubicación
=========

:Módulo:
 Tesorería

:Grupo:
 Parámetros

:Descripción:
  Administración de Cajas, Bancos y Franquicias

Introducción
============

En *Administración de Cajas, Bancos y Franquicias* podrá modificar todos los parámetros necesarios para la agilización de los procesos de Tesorería. 

---------------------------------------------------------------------------

Las **Cajas generales** son creadas y configuradas desde aquí. Una caja general recibe los ingresos y provee los gastos en un centro de costos. Es necesaria para poder facturar a un cliente y poder pagar los servicios o abonar a los proveedores. Es muy importante estar al tanto del cierre y de la apertura de una caja, ya que muchos procesos en el area administrativa giran alrededor de estos parametros.

---------------------------------------------------------------------------

Las **Cajas menores** son creadas y configuradas desde aquí. Una caja menor se configura para tener un cupo limitado de dinero y poder dar salida a pequeños gastos (aseo, vigilancia, alcantarillado) de manera más sencilla. Puede referirise a gastos de menor responsabilidad.


Puede cerrar una caja menor cuando lo desee, y para abrirla de nuevo deberá recargar su saldo en un egreso a terceros del módulo "Tesorería"

---------------------------------------------------------------------------

Agregue, y administre los **bancos y cuentas bancarias** desde este formulario. Las cuentas bancarias son necesarias para recibir ingresos en efectivo o en tarjetas, por lo tanto deben asociarse, como se explicará en los siguientes títulos, a los bancos y a las franquicias. 

Los **Bancos**, además, deben estar relacionados a una persona jurídica como cualquier otra compañía, esto lo podrá ver aquí y en la adiminstración de terceros en el módulo de *Contabilidad*.

Encontrará un listado de *Bancos* precargados a los que deberá asociar un tercero para poder usar las cuentas bancarias relacionadas, las franquicias relacionadas a las cuentas, y manejar cheques internos y de terceros. Las cuentas bancarias se crean a partir de un banco. 

---------------------------------------------------------------------------

Las **franquicias**, son todas aquellas empresas que prestan servicios para la banca automatizada a través de tarjetas. Para poder recibir pagos a través de las franquicias debe haberlas configurado anteriormente y haberlas relacionado a una cuenta bancaria.


Crear Caja General
==================

Pre-requisitos
--------------

	- Haber creado un centro de costo anteriormente.

Para crear una Caja General
---------------------------

Para crear una Caja General realice los siguientes pasos:

	- Ejecute la opción *Administración de Cajas, Bancos y Franquicias* 

		 .. figure:: images/cajasybancos/0.png
 			:align: center

	- En el árbol verá la opción 'Caja General', haga click en el signo '+' del lado izquierdo.


		 .. figure:: images/cajasybancos/cajageneral/2.png
 			:align: center

	- En los Centros desplegados, elija aquel donde desea crear la *Caja general*. Haga click a la izquierda del centro en el símbolo '+'.
	- Elija el centro de costo donde irá la *Caja General* y haga click derecho sobre él.
	- En las opciones desplegadas, haga click en "Crear nueva caja general"

Configurar una Caja General
===========================

Para entrar a la configuración de la Caja General, haga click derecho sobre ella en el árbol y elija 'Modificar propiedades de #Nombrecajageneral'.

	.. Note:
		Los permisos no están dados por defecto para los usuarios nuevos, deberá configurarlos. Ejemplo: Si una cuenta bancaria es creada antes que un nuevo usuario del sistema, este no tendrá acceso hasta que sea establecido en la configuración de la cuenta.

 .. figure:: images/cajasybancos/cajageneral/3.png
 	:align: center


Datos de caja
-------------

La primera pestaña de la configuración de la caja es 'Datos de caja', en esta pestaña podrá digitar el nombre de la caja y además asignar un responsable.

 .. figure:: images/cajasybancos/cajageneral/a.png
 	:align: center

Usuarios
--------

En la pestaña 'Usuarios' podrá escojer los administradores de sistema que pueden realizar transacciones sobre los fondos y ver información de esta caja. 

Verá dos columnas a la derecha, identificadas por una 'A' de 'acceso' y una 'S' de 'saldo'. Marcar la 'A' permite al usuario ver el dinero en caja y al marcar la 'S' le permite realizar transacciones.

 .. figure:: images/cajasybancos/cajageneral/b.png
 	:align: center

Transferencia de Fondos
-----------------------

En la pestaña 'Transferencia de fondos' podrá escojer los administradores de sistema que pueden realizar transferencias desde esta caja. Esta opción funciona de manera similar a la pestaña 'Usuarios', pero solo permite transferencias de fondos.

Verá dos columnas a la derecha, identificadas por una 'A' de 'acceso' y una 'S' de 'saldo'. Marcar la 'A' permite al usuario ver el dinero en caja y al marcar la 'S' le permite realizar transferencias.

 .. figure:: images/cajasybancos/cajageneral/c.png
 	:align: center

Contabilidad
------------

Elija en la pestaña 'Contabilidad' las cuentas que serán afectadas en la entrada de dinero por tarjetas, efectivo o cheque.

 .. figure:: images/cajasybancos/cajageneral/d.png
 	:align: center

Otros datos
-----------

En 'Otros datos' podrá elegir:

	- **La caja se debe cerrar a diario:** Marque la caja de verificación, si lo desea así.
	- **Ajustar automáticamente saldo al cerrar:** Si la situación lo requiere, como por ejemplo: El que maneja la caja es el mismo auditor, entonces puede ajustar automáticamente el saldo de la caja generando un recibo de caja o un comprobante de egreso.
	- **Visualizar conceptos de gastos al cerrar la caja:** Seleccione los datos que el usuario podrá ver en pantalla al cerrar la caja, entre ellos: egresos y transfernecias. Esta es una opción de Seguridad.
	- **Detalle de impresión de para cuadre de caja:** Elija aquí el nivel de detalle que quiere sobre la impresión.

 .. figure:: images/cajasybancos/cajageneral/e.png
 	:align: center

Crear Caja Menor
================

Pre-requisitos
--------------

	- Haber creado un centro de costo anteriormente.

Para crear una Caja Menor
---------------------------

Para crear una Caja Menor realice los siguientes pasos:

	- Ejecute la opción *Administración de Cajas, Bancos y Franquicias* 

		.. figure:: images/cajasybancos/0.png
 			:align: center

	- En el árbol verá la opción 'Caja Menor', haga click en el signo '+' del lado izquierdo.

		.. figure:: images/cajasybancos/cajamenor/1.png
 				:align: center

	- En los Centros desplegados, elija aquel donde desea crear la *Caja Menor*. Haga click a la izquierda del centro en el símbolo '+'.
	- Elija el centro de costo donde irá la *Caja Menor* y haga click derecho sobre él.
	- En las opciones desplegadas, haga click en "Crear nueva caja menor"

		 .. figure:: images/cajasybancos/cajamenor/2.png
 				:align: center


Configurar una Caja Menor
===========================

Para entrar a la configuración de la Caja Menor, haga click derecho sobre ella en el árbol y elija 'Modificar Modificar propiedades de #NombreCajaMenor'. Las configuraciones de Caja Menor son similares a las de una General, pero con muchas más limitaciones.

	 .. figure:: images/cajasybancos/cajamenor/3.png
 			:align: center

Datos de caja
-------------

La primera pestaña de la configuración de la caja es 'Datos de caja', en esta pestaña podrá digitar el nombre de la caja y además asignar un responsable.

	 .. figure:: images/cajasybancos/cajamenor/a.png
 			:align: center

Contabilidad
------------

Elija en la pestaña 'Contabilidad' la cuenta que será afectada al recargar el saldo de la caja. 

	 .. figure:: images/cajasybancos/cajamenor/b.png
 		:align: center

Crear un Banco
==============

Aunque hay una lista de la mayoría de los bancos del país creados, es posible que quiera crear uno nuevo.

Para crear un Banco
-------------------

Para crear un Banco realice los siguientes pasos:

	- Ejecute la opción *Administración de Cajas, Bancos y Franquicias* 

		 .. figure:: images/cajasybancos/0.png
 				:align: center
	- En la carpeta 'Bancos' haga click derecho
	- En las opciones desplegadas, haga click en "Crear nuevo banco"

		.. figure:: images/cajasybancos/bancos/2.png
 			:align: center

Activar un Banco - Asociarlo a un tercero
-----------------------------------------

Un *Banco* solo podrá ser parte de sus operaciones cuando lo haya asociado a un tercero. Para esto, haga click derecho sobre el Banco al que desea asociar el tercero y luego click sobre 'Modificar propiedades de #NombreBanco', allí verá una ventana con la única opción de seleccionar un tercero de la lista en el botón |wzedit.bmp|

		 .. figure:: images/cajasybancos/bancos/3.png
 				:align: center

 	- Nueva Ventana:

 		.. figure:: images/cajasybancos/bancos/4.png
 			:align: center



Haga click aquí para ver cómo crear un tercero. ref

Crear una Cuenta Bancaria
=========================

	- Ejecute la opción *Administración de Cajas, Bancos y Franquicias* 
	- En la carpeta 'Bancos' haga click
	- Elija el Banco relacionado con la cuenta y haga click derecho sobre él
	- En las opciones desplegadas, haga click en "Crear cuenta bancaria"
	- Se desplegará una ventana para llenar la información de la cuenta. En la pestaña *Cuenta Bancaria:*
		- Tipo de cuenta
		- Número de Cuenta
		- Referencia
		- Cuenta contable - Seleccione también si desea que esta cuenta se cree automáticamente o elegir una existente.
		- Moneda
		- Saldo Actual
	- En la pestaña *Usuarios:* podrá escojer los administradores de sistema que pueden realizar transacciones sobre los fondos y ver información de esta caja.  

		- Verá dos columnas a la derecha, identificadas por una 'A' de 'acceso' y una 'S' de 'saldo'. Marcar la 'A' permite al usuario ver el dinero en caja y al marcar la 'S' le permite realizar transacciones. Estas opciones no vienen marcadas por defecto.

	- En la pestaña 'Transferencia de fondos' podrá escojer los administradores de sistema que pueden realizar transferencias desde esta cuenta. Esta opción funciona de manera similar a la pestaña 'Usuarios', pero solo permite transferencias de fondos. 

		- Verá dos columnas a la derecha, identificadas por una 'A' de 'acceso' y una 'S' de 'saldo'. Marcar la 'A' permite al usuario ver el dinero en cuenta y al marcar la 'S' le permite realizar transferencias.


Crear una Franquicia
====================

Aunque hay una lista de la mayoría de las franquicias del país creadas, es posible que quiera crear una nueva.

Para crear una franquicia
-------------------------

Para crear una franquicia realice los siguientes pasos:

	- Ejecute la opción *Administración de Cajas, Bancos y Franquicias*

		.. figure:: images/cajasybancos/0.png
 			:align: center

	- En la carpeta 'Franquicia' haga click derecho
	- En las opciones desplegadas, haga click en "Crear nueva franquicia"

		.. figure:: images/cajasybancos/franquicias/2.png
 			:align: center

Activar una franquicia - Relacionarla a una cuenta bancaria
-----------------------------------------------------------

Para aceptar pagos en tarjetas y otras transacciones relacionadas, deberá primero asociar obligatoriamente una cuenta a la franquicia que quiera recurrir según el metodo de pago, por ejemplo: si desea recibir pagos por tarjeta de débito, por lo menos una de las franquicias pertinentes a este tipo de pago debe estar relacionada a una cuenta bancaria. Para relacionar una franquicia a una cuenta bancaria, realice los siguientes pasos:

	- Haga click derecho sobre la franquicia a la que desea relacionar una cuenta. Recuerde que esta cuenta debe estar configurada y el banco de la cuenta debe estar configurado, y listos para usarse. Vea `Activar un Banco - Asociarlo a un tercero`_
	- Haga click en la opción 'Modificar propiedades de #NombreFranquicia'

		.. figure:: images/cajasybancos/franquicias/3.png
 			 :align: center

	- Elija una 'Aplicación' para la franquicia que determinará el centro de costo donde puede ser usada. También puede seleccionar una 'Aplicación General'
	- Seleccione la 'Cuenta Bancaria' pertinente en la lista.
	- Podrá cambiar el nombre de la franquicia, y más abajo elegir si se trata de una de 'débito' o de 'crédito'
	- Elija en 'Cuenta Comisiones' la cuenta contable que será afectada con las comisiones.
	- En adelante, podrá elegir los valores de comisiones, impuestos o retenciones que produce el uso de esta franquicia como parte de pago. Haga uso del simulador para comprobar si son correctos los valores digitados.
	- Haga click en |save.bmp| *Guardar*. Los valores guardados no incluyen los introducidos y generados por el simulador.

			.. figure:: images/cajasybancos/franquicias/4.png
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