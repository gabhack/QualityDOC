======================
Facturación a clientes
======================

Ubicación
=========

:Módulo:
  Ventas

:Grupo:
 Operaciones

:Descripción:
 Facturación a clientes


Introducción
============

En esta operación usted podrá realizar facturas de ventas a clientes. 

- La fecha de la factura se establece automáticamente de acuerdo a la configuración del centro de costo.



Pre-requisitos
==============

	- `Crear Resolución de facturación - DIAN<>`_
	- `Crear un Vendedor<>`_
	- `Crear un producto o un servicio<>`_
	- `Crear/configurar una lista de precios<>`_
	- `Permitir las ventas en el centro de costos <>`_
	- `Crear una caja`_



Crear una factura / Procesar una venta
======================================

Para procesar una venta realice los siguientes pasos:

	- Ejecute la opción *Facturación a clientes*
	- Si no lo ha hecho anteriormente, entonces debe `Configurar resolución de facturación y Caja`_
	- Seleccione el centro de costo que realiza la venta
	- Introduzca la identificación del comprador y presione enter o búsquelo |buscar.bmp|. Si el cliente no está creado, verá una ventana de confirmación preguntando si desea crearlo, presione 'Sí' y proceda a llenar los datos necesarios del nuevo comprador. `Crear un cliente<>`_
	- En la lista 'Vendedor', elija el vendedor pertinente. Esta configuración solo se hace la primera vez aunque luego podrá cambiarlo.
	- En la lista 'Precios', eija la lista de precios en la cual estarán basados los montos de la factura.
	- Encontrará un campo de texto vacio, destinado a la búsqueda de productos. Use el lector laser, introduzca manualmente el código del producto, el codigo de acceso rápido o presione enter para buscarlo en la lista. El lector laser puede estar configurado para realizar un Enter automático después de encontrar el producto, si no es así, presione Enter.
	- Verá información detallada del producto:

	+------+------------+-----+-----------+------------+--------------+---------------+-----------+--------+
    |Nombre|cód. Sistema|% IVA| Existencia|**cantidad**|Valor Unitario|Valor Descuento|% descuento|plus.bmp|
    +------+------------+-----+-----------+------------+--------------+---------------+-----------+--------+

    - En el campo 'cantidad' introduzca el número de unidades que venderá o de veces que ha prestado un servicio.
    - Agregue el producto a la grilla presionando el botón |plus.bmp|
    - Después de agregar el producto en la grilla, podrá modificar la casilla en la columna 'cantidad' siempre que lo considere necesario. Si no hay suficientes productos en existencia el sistema se lo hará saber.
    - En la esquina inferior derecha, podrá ver información relacionada a la facturación (Sub Total, impuestos, descuentos, retenciones y total)
    - Una vez esté seguro del total de la venta y los productos agregados, presione F2 si será cancelada en efectivo o F3 si será pagada con otros medios (cheque, tarjeta, crédito). 
    - Se desplegará una ventana de confirmación para imprimir o no el recibo/reporte de la venta.

Configurar resolución de facturación y Caja
===========================================

	- Ejecute la opción *Facturación a clientes*
	- Haga click en la flecha de la esquina superior derecha
	- Allí verá la opción desplegable "Configurar Resolución y caja", haga click en ella.
	- Seleccione en la lista de opciones la Resolución que quiera usar para facturar
	- Seleccione la Caja a la que se adjudicarán los montos de las ventas y los egresos por devolución.
	- Oprima 'Actualizar' |save.bmp|








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