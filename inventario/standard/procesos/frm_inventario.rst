==================================================
Entradas, salidas & transferencias de mercancías
==================================================

Ubicación
=========

:Módulo:
 Inventario

:Grupo:
 Operaciones

:Descripción:
 Entradas, salidas y transferencia de mercancías

Introducción
============
 
En la opción *Entradas, salidas & transferencias de mercancías* usted podrá manejar la ubicación, la entrada o la salida de los insumos o productos que actualmente están registrados en el sistema.

La opción Entradas, salidas & transferencias de mercancías le permitirá entre otras cosas.

  - Dar entrada a productos al inventario
  - Dar salida a productos del inventario
  - Trasladar productos de un centro de costos.  
  
Entradas de mercancías
======================

Introducción
------------

Las entradas de mercancías se refieren a todo aquel producto que llegue al centro de costo y deba ser registrado en el sistema, sea cual sea la razón de su llegada, a continuación podrá leer sobre los tipos de entradas existentes.

 .. NOTE::

   En *Generalidades del Módulo de Inventario - Definición de Transacciones de Inventario* Aprendió a crear nuevos tipos de entradas que ahora aparecerán a la hora de ingresar mercancía.

Tipos de entradas
-----------------

Existen diferentes motivos por los cuales se da ingreso a un producto en el centro de costo, es importante conocer el motivo por el cual un producto ha sido ingresado a sistema.

  - Entradas de almacén por compras.
  - Entradas por otros conceptos  
 
Antes de comenzar (Pre-requisitos para realizar una *Entrada por compra a proveedores*)
---------------------------------------------------------------------------------------

Para comenzar es importante saber que se necesita la creación de algunos parámetros para realizar cierto tipo de entradas:

  - Crear un centro de costo. ref
  - Crear un Proveedor.
  - Habilitar el almacén para recibir mercancía por compras.
  
Cualquier entrada a inventario deberá tener un *número de remisión* que puede ser una factura de compra, un número de remisión, un documento, etc...

Entradas por compras a proveedores
----------------------------------

Usted realiza una Entrada por compras a proveedores, cuando los insumos/productos que desea ingresar han sido comprados por la empresa a un proveedor específico. 

	  .. Note::    
     Para habilitar esta entrada, deberá permitir al almacén recibir mercancías por compras y además tener al menos un proveedor creado.
    

Para realizar una *Entrada por compras al proveedor* al sistema siga los siguientes pasos:

  - Ejecute la opción Entradas, salidas & transferencias de mercancías
  - El sistema desplegará una ventana donde encontrará una lista de opciones con la pregunta *¿Qué proceso desea realizar?*
  - Escoja el proceso *Entradas*
  - Escoja el *Centro de costo* donde ingresará la mercancía
  - Seleccione el concepto *Entrada de almacén por compras'
  - Usted verá como aparecen dos nuevos campos en pantalla: Proveedor y tipo de compra.
  -Seleccione el Proveedor al cual se le ha comprado la mercancía entrante.
  -Seleccione el tipo de compra. Existen dos tipos de compra:
    - Factura: Se habla de factura cuando los productos deben incluir algún tipo de impuesto.
    - Remisión: Use esta opción para realizar una entrada de mercancía que no reflejará impuesto alguno.
  - Agregue alguna observación apropiada para describir este proceso de entrada.
  - Especifique el *Remisión No* - Puede indicar aquí cualquier control pertinente indicado en el documento físico de la factura o la remisión.
  - Puede introducir un monto para los fletes que será distribuido entre el costo de los insumos de la compra. 
  
	 .. NOTE::  
	   Esta opción viene deshabilitada por defecto. Para activarla comuníquese con el administrador de sistema. ref

  - Encontrará ahora la casilla |buscar.bmp| buscar, donde podrá dar inicio a la inserción de insumos/productos. Si sabe el código del producto digítelo, ingréselo con el lector láser, o también oprima Enter y búsquelo en la lista de productos. Oprima Enter de nuevo.
  - Verá como aparece información relacionada al producto:
   |Nombre|referencia|IVA%|Stock|cantidad|costo|descuento|+|
  - En el campo *cantidad* introduzca la cantidad de productos que han llegado al centro de costo. Presione Enter.
  - En el campo *costo* ingrese el precio del producto que aparece en la factura (sin IVA). Presione Enter.
  - En el campo *descuento* ingrese el porcentaje del descuento en caso de ser necesario. Presione Enter.
  - Presione Enter de Nuevo para agregar el producto a la lista.
  - Una vez el producto aparezca en la lista, podrá ingresar otro producto presionando Enter.
  - Si no hay más productos para agregar, revise que el listado, los costos, IVA, fletes y descuentos sean correctos y presione F2 o el ícono |save.bmp| Guardar.
  - El sistema pedirá que confirme el procedimiento, seleccione *sí*.
  - Visualizará en un documento un comprobante de ingreso de mercancía por compra a proveedor. Puede imprimirlo para respaldo físico. Podrá reimprimir este comprobante en la opción *reimpresión de transacciones de inventario* de este mismo apartado.  
  
	 .. NOTE:: 
	   El campo IVA sólo estará presente en la entrada de *mercancía por compras a proveedor* y además si está permitido en las características del producto.

Antes de comenzar (Pre-requisitos para realizar una *Entrada por otros conceptos*)
-----------------------------------------------------------------------------------

  - Crear un centro de costo

Entradas por otros conceptos
----------------------------

Algunas de las entradas por otros conceptos que pueden existir son:

  - Saldos iniciales de inventarios: Use esta entrada cuando está abriendo el centro de costo contable y administrativamente y tiene un inventario inicial.
  - Entrada de almacén por ajuste débito: Entrada de mercancía a través de una nota de débito.

Para realizar una *Entrada* por cualquiera de estos u otros conceptos, siga los siguientes pasos:

  - Ejecute la opción Entradas, salidas & transferencias de mercancías
  - El sistema desplegará una ventana donde encontrará una lista de opciones con la pregunta *¿Qué proceso desea realizar?*
  - Escoja el proceso *Entradas*
  - Escoja el *Centro de costo* donde ingresará la mercancía
  - Seleccione el concepto apropiado
  - Agregue alguna observación apropiada para describir este proceso de entrada.
  - Especifique el *Remisión No* - Puede indicar aquí cualquier control pertinente indicado en el documento físico de la factura o la remisión.
  - Puede introducir un monto para los fletes que será distribuido entre el costo de los productos de la compra. 
  
	 .. NOTE:: 
        Esta opción viene deshabilitada por defecto. Para activarla comuníquese con el administrador de sistema. ref

- Encontrará ahora la casilla |buscar.bmp| buscar, donde podrá dar inicio a la inserción de insumos/productos. Si sabe el código del producto digítelo, ingréselo con el lector láser, o también oprima Enter y búsquelo en la lista de productos. Oprima Enter de nuevo.
  - Verá como aparece información relacionada al producto:
   |Nombre|referencia|IVA%|Stock|cantidad|costo|descuento|+|
  - En el campo *cantidad* introduzca la cantidad de productos que han llegado al centro de costo. Presione Enter.
  - En el campo *costo* ingrese el precio del producto que aparece en la remisión. Presione Enter.
  - En el campo *descuento* ingrese el monto del descuento en caso de ser necesario. Presione Enter.
  - Presione Enter de Nuevo para agregar el producto a la lista.
  - Una vez el producto aparezca en la lista, podrá ingresar otro producto presionando Enter.
  - Si no hay más productos para agregar, revise que el listado, los costos, fletes y descuentos sean correctos y presione F2 o el ícono |save.bmp| Guardar.
  - El sistema pedirá que confirme el procedimiento, seleccione *sí*.
  - Visualizará en un documento PDF un comprobante de entrada. Puede imprimirlo para respaldo físico. Podrá reimprimir este comprobante en la opción *reimpresión de transacciones de inventario* de este mismo apartado.

Fletes
------

El campo flete en las entradas de mercancía de cualquier tipo, afecta el costo total de la factura y de cada producto, distribuyendo el flete entre cada uno de los productos ingresados. Esto podrá observarlo al generar el comprobante. 

Salidas de mercancias
=====================

Introducción
------------

Las *salidas de mercancías* se refieren al registro de toda salida de un producto del centro de costo. Esta salida puede darse por un concepto predefinido por el usuario o por un proceso administrativo del sistema, tal como: Factura de venta, devolución al proveedor, etc...

 .. NOTE::
   En *Generalidades del Módulo de Inventario - Definición de Transacciones de Inventario* Aprendió a crear nuevos tipos de salidas que ahora aparecerán a la hora de dar salida a la mercancía.    
    
Salidas de mercancías por conceptos
-----------------------------------

Para dar salida a un producto o conjunto de productos del centro de costo, siga los siguientes pasos:

  - Ejecute la opción Entradas, salidas & transferencias de mercancías
  - El sistema desplegará una ventana donde encontrará una lista de opciones con la pregunta *¿Qué proceso desea realizar?*
  - Escoja el proceso *Salidas*
  - Escoja el *Centro de costo* de donde saldrá la mercancía
  - Seleccione el concepto apropiado
  - Agregue alguna observación apropiada para describir este proceso de salida.
  - Encontrará ahora la casilla |buscar.bmp| buscar, donde podrá dar inicio a la inserción de insumos/productos a los que quiere dar salida. Si sabe el código del producto digítelo, ingréselo con el lector láser, o también oprima Enter y búsquelo en la lista de productos. Oprima enter de nuevo.
  - Verá como aparece información relacionada al producto:
   |Nombre|referencia|IVA%|Stock|cantidad|costo|descuento|+|
  - En el campo *cantidad* introduzca la cantidad de productos que saldrán del centro de costo. Presione Enter.
  
     .. Note::
     En el caso de una salida de mercancía del centro de costo por este medio, no se podrá especificar: descuento, IVA, flete ni costo. Solo la cantidad. Si desea hacer una salida especificando todos o alguno de estos campos, deberá crear una Factura a cliente, en el apartado *Ventas*.
  
  - Presione Enter de Nuevo para agregar el producto a la lista.
  - Una vez el producto aparezca en la lista, podrá ingresar otro producto presionando Enter.
  - Si no hay más productos para agregar, revise que el listado sea el correcto y presione F2 o el ícono |save.bmp| Guardar.
  - El sistema pedirá que confirme el procedimiento, seleccione *sí*.
  - Visualizará en un documento PDF un comprobante de salida. Puede imprimirlo para respaldo físico. 
  
      .. Note::
        
      Podrá reimprimir este comprobante en la opción *reimpresión de transacciones de inventario* de este mismo apartado.

Transferencias de mercancías
============================
Introducción
------------
Puede usar la opción de *traslado entre bodegas* para llevar mercancía desde un centro de costo a otro. De esta manera puede intercambiar productos en sus centros de costo y siempre mantenerlos actualizados.

Antes de comenzar (pre-requisitos para realizar un *traslado entre bodegas*
---------------------------------------------------------------------------
 Para realizar un *traslado entre bodegas* primero deberá:
   - Tener al menos dos centros de costos creados.
   - Poseer al menos un producto en el centro de costo de origen.
   - Tener los permisos correspondientes. Si no los tiene, comuníquese con su administrador de sistema.
   
Para realizar Transferencias de mercancías
------------------------------------------

Para realizar una transferencia de mercancías de un centro de costo a  otro, siga los siguientes pasos:

  - Ejecute la opción Entradas, salidas & transferencias de mercancías
  - El sistema desplegará una ventana donde encontrará una lista de opciones con la pregunta *¿Qué proceso desea realizar?*.
  - Escoja el proceso *Traslado entre bodegas*.
  - Escoja el *centro de costo* de donde saldrá la mercancía.
  - Escoja el *centro de costo* a donde llegará la mercancía.
  - Escriba una observación de ser necesario.
  - Encontrará ahora la casilla |buscar.bmp| buscar, donde podrá dar inicio a la inserción de insumos/productos a los que quiere dar salida. Si sabe el código del producto digítelo, ingréselo con el lector láser, o también oprima Enter y búsquelo en la lista de productos. Oprima enter de nuevo.
  - Verá como aparece información relacionada al producto:
   |Nombre|referencia|IVA%|Stock|cantidad|costo|descuento|+|
  - En el campo *cantidad* introduzca la cantidad de productos de este tipo que saldrán del centro de costo. Presione Enter.           
       
     .. Note::
     En el caso de un traslado entre centros de costo, no se podrá especificar: descuento, IVA, flete ni costo. Solo la cantidad.
        
  - Presione Enter de Nuevo para agregar el producto a la lista.
  - Una vez el producto aparezca en la lista, podrá ingresar otro producto presionando Enter.
  - Si no hay más productos para agregar, revise que el listado sea el correcto y presione F2 o el ícono |save.bmp| Guardar.
  - El sistema pedirá que confirme el procedimiento, seleccione *sí*.
  - Visualizará en un documento PDF un comprobante de salida. Puede imprimirlo para respaldo físico. 
  - Ahora podrá consultar ambas bodegas y ver los cambios en las cantidades de producto. Para consultar, consulte en el manual acerca de este mismo módulo en el apartado *consultas*.
  
  	 .. Note::        
     Podrá reimprimir este comprobante en la opción *reimpresión de transacciones de inventario* de este mismo apartado.


Ordenes de compra
=================
Introducción
------------

La orden de compra es un documento mediante el cual usted puede hacer un pedido detallado al proveedor. Puede registrar estas ordenes en el sistema y luego comparar con el pedido que llega.

Antes de comenzar (Pre-requisitos para realizar una *Entrada por orden de compra a proveedores*)
------------------------------------------------------------------------------------------------

Para comenzar es importante saber que se necesita la creación de algunos parámetros para realizar una orden de compra:

  - Crear un centro de costo. ref
  - Crear un Proveedor.
  - Habilitar el almacén para recibir mercancía por compras.
  
Para crear orden de compra
--------------------------
Para realizar una *Orden de compra* al sistema siga los siguientes pasos:

  - Ejecute la opción Entradas, salidas & transferencias de mercancías.
  - El sistema desplegará una ventana donde encontrará una lista de opciones con la pregunta *¿Qué proceso desea realizar?*.
  - Escoja el proceso *Orden de compra*.
  - Escoja el *centro de costo* donde ingresará la mercancía una vez el proveedor la envíe.
  - Usted verá como aparecen dos nuevos campos en pantalla: Proveedor y tipo de compra.
  -Seleccione el Proveedor al cual se le comprará la mercancía entrante.
  -Seleccione el tipo de orden de compra. Existen dos tipos orden de compra:
    - Factura: Se habla de factura cuando los productos deben incluir algún tipo de impuesto.
    - Remisión: Use esta opción para realizar una orden de compra que no reflejará impuesto alguno.
  - Agregue alguna observación apropiada para describir este proceso de entrada.
  - Puede introducir un monto para los fletes que será distribuido entre el costo de los productos de la compra.
    
  	 .. Note::
  		Esta opción viene deshabilitada por defecto. Para activarla comuníquese con el administrador de sistema. ref

  - Encontrará ahora la casilla |buscar.bmp| buscar, donde podrá dar inicio a la inserción de insumos/productos. Si sabe el código del producto digítelo, ingréselo con el lector láser, o también oprima Enter y búsquelo en la lista de productos. Oprima Enter de nuevo.
  - Verá como aparece información relacionada al producto:
   |Nombre|referencia|IVA%|Stock|cantidad|costo|descuento|+|
  - En el campo *cantidad* introduzca la cantidad de productos de este tipo que pedirá al proveedor. Presione Enter.
  - En el campo *costo* ingrese el costo del producto que aparece en la remisión. Presione Enter.
  - Presione Enter de Nuevo para agregar el producto a la lista.
  - Una vez el producto aparezca en la lista, podrá ingresar otro producto presionando Enter.
  - Si no hay más productos para agregar, revise que el listado, los costos y fletes sean correctos y presione F2 o el ícono |save.bmp| Guardar.
  - El sistema pedirá que confirme el procedimiento, seleccione *sí*.
  - Visualizará en un documento PDF un comprobante de orden de compra. Puede imprimirlo para respaldo físico. 
  		
 	 .. Note::
   	   Podrá reimprimir este comprobante en la opción *reimpresión de transacciones de inventario* de este mismo apartado.
  
Eliminar orden de compra
------------------------

Para eliminar una orden de compra siga estos pasos:

 - Ejecute la opción Entradas, salidas & transferencias de mercancías
 - Pulse el botón *Ingreso de mercancías por orden de compra*
 - En la lista de la derecha donde puede seleccionar la orden de compra, seleccione la que desea eliminar y presione la tecla 'Supr'.
 - Vera un mensaje de confirmación donde deberá pulsar 'Sí' si está seguro de eliminarla.

Entrada de mercancías por medio de orden de compra existente
------------------------------------------------------------

Introducción
------------

Puede realizar una entrada de mercancía a partir de una orden de compra hecha anterioremente. No tendrá que elegir los productos de nuevo sino, más bien, verificar la cantidad de productos que entrarán con respecto a la orden que realizó.

Antes de comenzar (Pre-requisitos para realizar una *Entrada por compra a proveedores*)
----------------------------------------------------------------------------------------

Para comenzar es importante saber que se necesita la creación de algunos parámetros para realizar una entrada de mercancía por orden de compra:

  - Crear un centro de costo. ref
  - Crear un Proveedor.
  - Habilitar el almacén para recibir mercancía por compras.
  - Haber creado una **orden de compra** con anterioridad.
 
Para crear una entrada de mercancías por medio de orden de compra existente
----------------------------------------------------------------------------
 
Para realizar una *Entrada de mercancía por orden de compra* al sistema siga los siguientes pasos:

	- Ejecute la opción Entradas, salidas & transferencias de mercancías
	- Pulse el botón *Ingreso de mercancías por orden de compra*
	- Aparecerá una ventana flotante donde deberá seleccionar primeramente el centro de costo al que ingresará la mercancía.
	- Seleccione el proveedor al que realizó con anterioridad la orden de compra.
	- Verá aparecer una lista desplegable a la derecha donde podrá seleccionar la *orden de compra* a la que quiere dar entrada.
	- Cuando seleccione la *orden de compra* entonces verá en la lista de abajo todos los productos que aparecían en la orden.
	- Haga check en los productos que llegaron a su centro de costo.
	- Podrá modificar el campo *recibir* puede escribir la cantidad del producto que llegó realmente. 
	- Pulse aceptar cuando haya seleccionado los productos y las cantidades correctas.
	- Agregue alguna observación apropiada para describir este proceso de entrada de mercancía por orden de compra.
	 - Especifique el *Remisión No* - Puede indicar aquí cualquier control pertinente indicado en el documento físico de la factura o la remisión.
	 - Puede introducir un monto para los fletes que será distribuido entre el costo de los insumos de la compra. 
  
   	 .. Note::
   	    Esta opción viene deshabilitada por defecto. Para activarla comuníquese con el administrador de sistema. ref


  	- Verá como aparece información relacionada a cada producto en la lista.
  	- En la columna *costo* ingrese el precio del producto que aparece en la factura (sin IVA).
  	- En la columna *descuento* ingrese el porcentaje del descuento en caso de ser necesario.
  	- Revise que el listado, los costos, IVA, fletes y descuentos sean correctos y presione F2 o el ícono |save.bmp| Guardar.
 	- El sistema pedirá que confirme el procedimiento, seleccione *sí*.
 	- Visualizará en un documento un comprobante de ingreso de mercancía por compra a proveedor. Puede imprimirlo para respaldo físico. Podrá reimprimir este comprobante en la opción *reimpresión de transacciones de inventario* de este mismo apartado.
  

 
.. |wznew.bmp| image:: /_images/generales/wznew.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp