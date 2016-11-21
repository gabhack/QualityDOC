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
 Traslado entre bodegas

Introducción
============

Use la opción de *Traslado entre bodegas* para hacer transferencias de mercancías desde un centro de costo a otros. En esta opción el destinatario necesita recibir y confirmar la mercancía entrante.

Pre-requisitos
==============

Para hacer un *Traslado entre bodegas*:
	- Deberá tener creados al menos dos centros de costo.
	- Debe contar con los permisos necesarios.
	- Deben existir productos en stock para incluir en el caso de hacer un envío.
	- En el caso de recepción debe haber una transferencia pendiente para poder visiualizar las opciones.

Como realizar un envío de mercancías
====================================

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


Como realizar recepción de mercancías
=====================================

	-- Note:

	Solo visualizará las opciones si hay alguna transferencia pendiente.

- Ejecute la opción 'Traslado entre bodegas'.
- En la ventana desplegada, vaya a la pestaña 'Recepción de mercancía' en la parte superior.
- En la lista <<seleccione almacén destino>> elija el centro de costo que va a recibir la mercancía.
- En la lista <<seleccione almacén origen>> elija el centro de costo que envió la mercancía.
- Seleccione en la lista de traslados, aquel que desea recibir. Puede distinguir el traslado por la fecha o por la observación.
- En el siguiente campo puede insertar un valor de flete, si aplica.
- Verá los productos listados en la grilla. Chequee que cada producto en la grilla coincida con los que han llegado a su centro de costo, si coinciden marquelos en la fila del producto en el check de la última columna.
- Una vez seleccionados los productos que desea recibir, podrá pulsar |save.bmp| y así aceptar la transferencia.

  .. figure:: /_images/generales/placeholder.png
  :align: center

  Así es la ventana de recepción de mercancías.

Como realizar devolución de mercancias
======================================

	.. Note:
	Si un producto no coincide o por cualquier otra razón no desea recibirlo, puede devolverlo.

- Ejecute la opción 'Traslado entre bodegas'.
- En la ventana desplegada, vaya a la pestaña 'Recepción de mercancía' en la parte superior.
- En la lista <<seleccione almacén destino>> elija el centro de costo que va a recibir la mercancía.
- En la lista <<seleccione almacén origen>> elija el centro de costo que envió la mercancía.
- Seleccione en la lista de traslados, aquel que desea recibir. Puede distinguir el traslado por la fecha o por la observación.
- Deje vacío el campo Flete.
- Verá los productos listados en la grilla. 
Para devolver un producto, márquelo en el check de la última columna en la fila del artículo y haga click en |descartar.bmp| para regresarlo. 
- Se desplegará una ventana para que indique un motivo. Haga click en 'Ok'.


.. |plus.bmp| image:: /_images/generales/plus.bmp
.. |wznew.bmp| image:: /_images/generales/wznew.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp