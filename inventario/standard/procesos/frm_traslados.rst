===============================================
Transferencias de mercancías (Con confirmación)
===============================================
Ubicación
=========

:Módulo:
 Inventario

:Grupo:
 Operaciones

:Descripción:
<<<<<<< HEAD
 Traslado entre bodegas
=======
 Realiza traslados entre centro de costos
>>>>>>> 45baf35f0c086190d0a90a10a8779b7925e76ee5

Introducción
============

<<<<<<< HEAD
Use la opción de *Traslado entre bodegas* para hacer transferencias de mercancías desde un centro de costo a otros. En esta opción el destinatario necesita recibir y confirmar la mercancía entrante.

Pre-requisitos
==============

Para hacer un *Traslado entre bodegas*:
	- Deberá tener creados al menos dos centros de costo.
	- Debe contar con los permisos necesarios.
	- Deben existir productos en stock para incluir en el caso de hacer un envío.
	- En el caso de recepción debe haber una transferencia pendiente para poder visiualizar las opciones.
=======
En el esta operación usted podrá realizar traslado de mercancía desde un centro de costo a otro. También podrá realizar el recibimiento de mercancía entrante desde otro centro de costo.
>>>>>>> 45baf35f0c086190d0a90a10a8779b7925e76ee5

Como realizar un envío de mercancías
====================================

<<<<<<< HEAD
    .. Note:

    Es importante que considere que exite un máximo de traslados que usted puede realizar de un centro de costo a otro, a menos que su centro de costos esté autorizado para recibir entradas por compras.

    Si desea aumentar el límite de transacciones permitidas, puede hacerlo desde el módulo Contabilidad - Paramterización Contable - Inventarios - Transferencias en cola. Si no posee acceso a esta configuración, comuníquese con el administrador de sistema.

- Ejecute la opción 'Traslado entre bodegas'.
- En la nueva ventana, seleccione en la lista <<seleccione el almacén de origen>> el centro de costo de donde saldrá la mercancía.
- En la lista <<seleccione almacén destino>> seleccione el centro de costo al cual quiere que llegue la mercancía.
- En el campo de texto siguiente, puede digitar alguna observación oportuna.
- Ahora podrá buscar productos para ingresar en la grilla. Encontrará ahora la casilla |buscar.bmp| buscar, donde podrá dar inicio a la inserción de productos. Si sabe el código del producto digítelo, ingréselo con el lector láser, o también oprima Enter y búsquelo en la lista de productos. Oprima Enter de nuevo.
  - Verá como aparece información relacionada al producto:
   +------+------+----------+-----------+-----+--------+--------------+---------+
   |código|Nombre|referencia|cód. Rápido|Stock|cantidad|costo promedio|Plus.bmp||
   +------+------+----------+-----------+-----+--------+--------------+---------+
  - En el campo 'cantidad' ingrese la cantidad del producto que desea trasladar. Presione Enter dos veces.
  - Puede seguir agregando productos a la grilla presionando Enter de nuevo, o si ya ha terminado puede pulsar |save.bmp| 

  .. figure:: /_images/generales/placeholder.png
   :align: center

  Así es la ventana de envío de mercancías.

=======
Para Hacer un envío de mercancía realice las siguientes acciones:

  - Ejecute la opción *Traslado entre bodegas*
  - El sistema desplegará una ventana donde encontrará dos pestañas en la parte superior. Elija la pestaña *Envío de mercancías* (Esta pestaña también viene seleccionada por defecto)
  - En las listas seleccione un almacén de origen y un almacén de destino.
  - Opcionalmente podrá describir este traslado o colocar alguna observación en el campo 'Digite una observación'.
  - Encontrará ahora la casilla |buscar.bmp| buscar, donde podrá dar inicio a la inserción de productos a la grilla. Si sabe el código del producto digítelo, ingréselo con el lector láser, o también oprima Enter y búsquelo en la lista de productos. Oprima Enter de nuevo.
  - Verá información desplegarse acerca del producto:
   +------+------+----------+----------+-----+------------+-----+---------+----------+
   |código|Nombre|referencia|cód rápido|Stock|**cantidad**|costo promedio ||plus.bmp||
   +------+------+----------+----------+-----+------------+-----+---------+----------+
  - Ingrese en el campo 'cantidad' el número de unidades de este producto que desea trasladar. Presione enter 2 veces.
  - Cuando haya ingresado el total de productos a trasladarm compruebe las cantidades y seguidamente pulse el botón Guardar |save.bmp|  
  - Verá un mensaje de confirmación, si está seguro de la operación pulse 'Sí'.
  
>>>>>>> 45baf35f0c086190d0a90a10a8779b7925e76ee5

Como realizar recepción de mercancías
=====================================

  	.. Note:

  	Solo visualizará las opciones si hay alguna transferencia pendiente.

    La transferencia no dejará de ser una operación pendiente hasta que el valor de la casilla 'Saldo' de todos los productos en la grilla llegue a 0. Este valor disminuye al recibir o devolver productos.

    Si usted está recibiendo una devolución, solo podrá dar ingreso a los productos y no podrá regresarlos nuevamente.

- Ejecute la opción 'Traslado entre bodegas'.
- En la ventana desplegada, vaya a la pestaña 'Recepción de mercancía' en la parte superior.
- En la lista <<seleccione almacén destino>> elija el centro de costo que va a recibir la mercancía.
- En la lista <<seleccione almacén origen>> elija el centro de costo que envió la mercancía.
- Seleccione en la lista de traslados, aquel que desea recibir. Puede distinguir el traslado por la fecha o por la observación.
- En el siguiente campo puede insertar un valor de flete, si aplica.
- Verá los productos listados en la grilla. Coloque en la casilla de la columna 'procesar' la cantidad de unidades de cada producto que recibirá.

  .. figure:: /_images/generales/placeholder.png
   :align: center

  Así verá la casilla procesar.

- Marquelos en la fila del producto en el check de la última columna. 
- Una vez seleccionados los productos que desea recibir, podrá pulsar |save.bmp| y así realizar el ingreso. 
    - Solo los productos marcados se tomarán en cuenta, y entrarán las cantidades digitadas en la casilla 'procesar'.
    - Despues de pulsar el botón se procederá internamente al ingreso de las unidades y no verá más la grilla.
    - Si quedaron productos por ingresar o devolver, debe volver al paso 2 de esta misma sección.

  .. figure:: /_images/generales/placeholder.png
   :align: center

  Así es la ventana de recepción de mercancías.

Como realizar devolución de mercancias
======================================

<<<<<<< HEAD
  	.. Note:

  	Si un producto no coincide o por cualquier otra razón no desea recibirlo, puede devolverlo.

    La transferencia no dejará de ser una operación pendiente hasta que el valor de la casilla 'Saldo' de todos los productos en la grilla llegue a 0. Este valor disminuye al recibir o devolver productos.

- Ejecute la opción 'Traslado entre bodegas'.
- En la ventana desplegada, vaya a la pestaña 'Recepción de mercancía' en la parte superior.
- En la lista <<seleccione almacén destino>> elija el centro de costo que va a recibir la mercancía.
- En la lista <<seleccione almacén origen>> elija el centro de costo que envió la mercancía.
- Seleccione en la lista de traslados, aquel que desea recibir. Puede distinguir el traslado por la fecha o por la observación.
- Deje vacío el campo Flete.
- Verá los productos listados en la grilla. Coloque en la casilla de la columna 'procesar' la cantidad de unidades de cada producto que devolverá.

  .. figure:: /_images/generales/placeholder.png
   :align: center

  Así verá la casilla procesar.


- Marquelos en la fila del producto en el check de la última columna. 
- Una vez seleccionados los productos que desea devolverr, podrá pulsar |descartar.bmp| y así realizar la devolución.
    - Solo los productos marcados se tomarán en cuenta, y se devolverán las cantidades digitadas en la casilla 'procesar'. 
    - Despues de pulsar el botón se desplegará una ventana para que indique un motivo. Haga click en 'Ok'. 
    - Se procederá internamente a la devolución de las unidades y no verá más la grilla. 
    - Si quedaron productos por ingresar o devolver, debe volver al paso 2 de esta misma sección. 
=======
>>>>>>> 45baf35f0c086190d0a90a10a8779b7925e76ee5



.. |plus.bmp| image:: /_images/generales/plus.bmp
.. |wznew.bmp| image:: /_images/generales/wznew.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp