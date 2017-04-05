==================================
Administrador de pedidos de ventas
==================================

Ubicación
=========

:Módulo:
  Ventas

:Grupo:
 Procesos

:Descripción:
  Administrador de pedidos de ventas


Introducción
============

	En este proceso puede crear un pedido a un cliente según sus necesidades. Este proceso no genera una salida del inventario. Cuando el pedido haya llegado y desee darle salida, deberá ir a la opción `Remisiones de pedidos <../../../inventario/standard/procesos/frm_remisiones.html>`_


Pre-requisitos
==============

	- Tener al menos un producto/servicio creado
	- Haber configurado una Lista de precios
	- Un cliente
	- Un vendedor
	- Un centro de costo


Visualizar los pedidos existentes
=================================

	- Ejecute la opción "Administrador de pedidos de ventas"
	- En la cabecera de la ventana selecciones el centro de costo correspondiente a la consulta
	- Seleccione en la lista al cliente, o búsquelo presionando el botón |buscar.bmp|
	- Seleccione si desea que la consulta muestre los 'Pedidos vigentes' o mostrarlos por fechas seleccionando 'Por periodo'. En el segundo caso, establezca el rango de fechas en los cuadros de texto
	- Presione el botón |btn_ok.bmp| para realizar la consulta
	- Verá en el cuerpo de la ventana toda la información pertinente a los pedidos que coincidan con la búsqueda
	- Cada pedido que aparece, es modificable o reimprimible haciendo click en el botón al final de la fila.

 .. figure:: images/11.png
 	   :align: center


Editar/Imprimir/Eliminar un pedido
==================================

	- Visualice los pedidos siguiendo los pasos del título `Visualizar los pedidos existentes`_
	- Haga click en el botón |export1.gif| al final de la fila del producto, allí podrá elegir Modificar, Anular o Imprimir el pedido
		- Si elige Modificar, verá una pantalla similar a la de creación, elija los campos que desee cambiar y en la grilla los productos que desea quitar o aquellos en los que necesita cambiar las cantidades
		- Si elige Anular entonces se desplegará una ventana para que indique un motivo y luego confirme haciendo click en |btn_ok.bmp| 
		- Si elige Imprimir 


 .. figure:: images/12.png
 	   :align: center

Crear un pedido
===============

Para crear un *Pedido* realice los siguientes pasos:

	- Ejecute la opción 'Administrador de pedidos de ventas'
	- Seleccione el centro de costo 
	- Seleccione un cliente de la lista, puede también buscarlo haciendo click en |buscar.bmp| o crearlo haciendo click en el botón |plus.bmp| `Crear un cliente <../../generalidades/act_clientes_pos.html#crear-un-cliente>`_
	- Seleccione un vendedor de la lista, puede también buscarlo haciendo click en |buscar.bmp| o crearlo haciendo click en el botón |plus.bmp| 
	- En la lista 'Precios', eija la lista de precios en la cual estarán basados los montos de la factura.
	- Encontrará un campo de texto vacio, destinado a la búsqueda de productos. Use el lector laser, introduzca manualmente el código del producto, el codigo de acceso rápido o presione enter para buscarlo en la lista. El lector laser puede estar configurado para realizar un Enter automático después de encontrar el producto, si no es así, presione Enter.
	- Verá información detallada del producto:

+--------+--------------+-----+------------+------------+--------------+---------------+-----------+--------+
| Nombre | cód. Sistema | IVA | Existencia |**cantidad**|Valor Unitario|Valor Descuento|% descuento|plus.bmp|
+--------+--------------+-----+------------+------------+--------------+---------------+-----------+--------+

    - En el campo 'cantidad' introduzca el número de unidades que venderá o de veces que ha prestado un servicio.
    - En el campo 'precio de venta' podrá establecer otro precio distinto al ya marcado inicialmente por la lista de precios.
    - Agregue el producto a la grilla presionando el botón |plus.bmp|
    - Después de agregar el producto en la grilla, podrá modificar la casilla en la columna 'cantidad' siempre que lo considere necesario. Si no hay suficientes productos en existencia el sistema se lo hará saber.
    - En la esquina inferior derecha, podrá ver información relacionada a la facturación (Sub Total, impuestos, descuentos, retenciones y total)
    - Existe un campo bajo la grilla donde podrá escribir alguna nota/observación sobre el pedido
    - Una vez verifique los montos, haga click en el botón |save.bmp| *guardar*
    - Haga click en 'Sí' en la ventana de confirmación 


 .. figure:: images/13.png
 	    :align: center

---------------------------------------------------------

.. |export1.gif| image:: /_images/generales/export1.gif
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