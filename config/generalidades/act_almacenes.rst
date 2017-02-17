=====================================
Estructura de almacenes de la empresa
=====================================

Ubicación
=========

:Módulo:
 Configuración

:Grupo:
 Parámetros

:Descripción:
  Estructura de almacenes de la empresa

Introducción
============

En *Estructura de almacenes de la empresa* puede configurar y crear las **Regiones** y ***centros de costo** de su compañía. Una **Región** es la agrupación de varios *Centros de costo* según su ubicación. Un *centro de costo* es el punto o los puntos de control de ingreso o egresos por conceptos, ventas, recibos, comprobantes, notas, etc. Un *Centro de costo* puede ser tratado además, como un almacén o bodega.

Crear una Región
================

Para crear una región realice los siguientes pasos:

	- Ejecute la opción *Estructura de almacenes de la empresa*
	- En 'Configuración general de la empresa' en el árbol, haga click derecho.
	- Haga click en 'Crear nueva Región'
	- Vera aparecer una nueva carpeta en la rama principal del arbol, escriba el nombre de la Región. Si por algún motivo ya no está editable el nombre de la nueva Región, haga click derecho sobre ella y elija |wzedit.bmp| 'Cambiar nombre a '

Eliminar una Región
===================

	- Ejecute la opción *Estructura de almacenes de la empresa*
	- Encuentre la Región a eliminar en la rama principal del árbol. Haga click derecho sobre ella. Escoja la opción |delete.bmp| 'Eliminar region'
	- Oprima 'Sí' en el mensaje de confirmación

Cambiar Nombre a una Región
===========================

	- Ejecute la opción *Estructura de almacenes de la empresa*
	- Encuentre la Región en la rama principal del árbol. Haga click derecho sobre ella y elija |wzedit.bmp| 'Cambiar nombre a '

Crear un Centro de costo
========================

Para crear un *Centro de costo* realice los siguientes pasos:

	
	- Ejecute la opción *Estructura de almacenes de la empresa*
	- Encuentre la región en el árbol dentro de la cual creará el centro de costo. Haga click derecho sobre ella. Escoja la opción |wznew.bmp| 'Crear nuevo centro de costo'
	- Verá en la rama de la Región un nuevo Centro con el nombre editable. Si por algún motivo ya no está editable el nombre del nuevo centro, haga click derecho sobre él y elija |wzedit.bmp| 'Cambiar nombre a '

Eliminar un centro de costo
===========================

   .. NOTE::

	  No podrá eliminar un centro de costo sobre el cual se haya hecho alguna operación

	- Ejecute la opción *Estructura de almacenes de la empresa*
	- Haga click en la Región donde está el *Centro de costo* 
	- Elija el *centro de costo* a eliminar en la rama principal del árbol. Haga click derecho sobre él. Escoja la opción |delete.bmp| 'Eliminar Centro de costo'
	- Oprima 'Sí' en el mensaje de confirmación

Cambiar Nombre a un Centro de costo
===================================

	- Ejecute la opción *Estructura de almacenes de la empresa*
	- Haga click en la Región donde está el *Centro de costo* 
	- Encuentre el *Centro de Costo* y haga click derecho sobre él y elija |wzedit.bmp| 'Cambiar nombre a '

Propiedades de un Centro de Costo
=================================

Para ver y modificar las propiedades de un *Centro de costo* realice los siguientes pasos:

	- Ejecute la opción *Estructura de almacenes de la empresa*
	- Haga click en la Región donde está el *Centro de costo* 
	- Encuentre el *Centro de Costo* y haga click derecho sobre él y elija |wzedit.bmp| 'Modificar propiedades de'
	- Verá una despegarse una ventana con las siguientes pestañas:

Datos Básicos
-------------

**Nombre del almacén:** Este será el nombre con el que se mostrará el *Centro de costo* en el sistema.

**Nombre comercial:** Este será el nombre del *Centro de costo* reflejado en el sistema.

**Nombre abreviado:** Este será el nombre que se refleje en algunas consultas con el fin de ahorrar espacio y facilitar las comparaciones con otros centros.

**Mostrar ventana para calculo de cambio:** Seleccione cuando quiere ver una calculadora asistente para que el cajero sepa cuanto debe dar de vuelta.



**reteICA:** Marque esta opción si este centro de costo cumple las condiciones de este impuesto. Esta condición se da según la ubicación del centro.

**Factura IVA:** Esta configuración es prioridad a la hora de realizar una entrada a almacén por compras. Si el producto tiene IVA pero esta opción está desmarcada, no se aplicará el impuesto sobre la compra. El valor del IVA sí depende específicamente de las propiedades del producto.

**Precios de factura impresa:** En esta opción puede definir la manera como los precios se muestran en la factura impresa.

**Leyenda:** Puede configurar un pie de página para la factura con información relevante. Por ejemplo: terminos de devolución, garantía, etc.

**Observación:** Información fija a la hora de facturar

**Posición de cursor:**

Control de fechas para las transacciones 
****************************************

 En esta opción podrá escoger la fecha que será marcada en las transacciones realizadas en este centro. Si escoge "Controlada por almacén" entonces las transacciones llevarán la última fecha de apertura de la caja. Al cambio, si escoge "Del sistema local" la operación tomará la fecha de su computador.

Este almacén realiza compras
****************************

 Determina si este Centro recibe mercancía por compras a proveedores. Por lo general las compras son centralizadas y luego se distribuyen a los *centros de costo* restantes.

Reportes
--------

Aquí se definen los parametros necesarios para la impresion y visualización de los reportes. Sólo un administrador de sistema capacitado debería hacer uso de esta opción.

Inventario
----------

**Responsable de Almacén:** Cualquier tercero puede ser responsable de un centro de costo

**Control de Traslado de Mercancías:** Centros que pueden ser destinos de transferencia de este *centro de costo*

**Centros de costos que funcionan como bodegas para este centro:** Seleccione de la lista los centros de costo que sirven como bodegas/almacenes para este *Centro de costo*. En el momento de facturar a un cliente podrá elegir su *Centro de costo* o el *Centro de costo -> Bodega*, en este caso, todas las operaciones de cartera son adjudicadas al *Centro de costo* pero las salidas de mercancía se reflejan en el inventario de la *bodega*.

**LLevar el IVA al costo:** Marque esta opción si los costos de su mercancía incluyen IVA (incluirlo en el momento de la compra), esta opción no es necesaria para empresas de régimen simplificado.



Ventas
------

**Razón Social:** En cada centro de costo puede elegir la Razón Social que encabeza la facturación. Por defecto el Centro tendrá la razón social de la configuración general de la empresa.

**Ingreso automático de productos a la factura de venta:** Para agilizar la facturación, usted puede marcar esta opción, de tal manera que cuando esté creando una factura de costo puede ahorrarse un par de Enter.

**Modalidad de selección del Vendedor:** Depende de la relevancia que tenga la persona que ejecute la venta.

**Permitir repetir productos en la facturación a clientes:** Si desea ingresar un mismo producto varias veces, probablemente por diferencia de precios, entonces marque esta opción.










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