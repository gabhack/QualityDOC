======================
Facturación a clientes
======================

Ubicación
=========

:Módulo:
  Ventas

:Grupo:
 Procesos

:Descripción:
 Facturación a clientes


Introducción
============

En esta operación usted podrá realizar facturas de ventas a clientes.

- La fecha de la factura se establece automáticamente de acuerdo a la configuración del centro de costo.



Pre-requisitos
==============

	- `Crear Resolución de facturación DIAN <../../generalidades/act_resoluciones.html#crear-una-resolucion-de-facturacion>`_
	- `Crear un Vendedor <../../generalidades/act_vendedores.html#crear-un-vendedor>`_
	- `Crear un producto o un servicio <../../../inventario/generalidades/act_maestroinsumos.html#productos-servicios>`_
	- `Crear o configurar una lista de precios <../../generalidades/frm_listas_precios_post.html#crear-una-lista-de-precios>`_
	- `Crear una caja <../../../tesoreria/generalidades/act_cajas.html#crear-caja-general>`_

  

Crear una factura / Procesar una venta
======================================

   .. figure:: images/1.png
 	:align: center

Para procesar una *venta* realice los siguientes pasos:

	- Ejecute la opción *Facturación a clientes*
	- Si no lo ha hecho anteriormente, entonces debe `Configurar resolución de facturación y Caja`_
	- Seleccione el centro de costo que realiza la venta
	- Introduzca la identificación del comprador y presione enter o búsquelo |buscar.bmp|. Si el cliente no está creado, verá una ventana de confirmación preguntando si desea crearlo, presione 'Sí' y proceda a llenar los datos necesarios del nuevo comprador. `Crear un cliente <../../generalidades/act_clientes_pos.html#crear-un-cliente>`_
	- Si el comprador tiene cotizaciones o remisiones pendientes puede verlas en el botón |buscar.bmp|
	- En la lista 'Vendedor', elija el vendedor pertinente. Esta configuración solo se hace la primera vez aunque luego podrá cambiarlo.
	- En la lista 'Precios', eija la lista de precios en la cual estarán basados los montos de la factura.
	- Encontrará un campo de texto vacio, destinado a la búsqueda de productos. Use el lector laser, introduzca manualmente el código del producto, el codigo de acceso rápido o presione enter para buscarlo en la lista. El lector laser puede estar configurado para realizar un Enter automático después de encontrar el producto, si no es así, presione Enter.
	- Verá información detallada del producto:

+--------+--------------+-----+------------+------------+--------------+---------------+-----------+----------+
| Nombre | cód. Sistema | IVA | Existencia |**cantidad**|Valor Unitario|Valor Descuento|% descuento||plus.bmp||
+--------+--------------+-----+------------+------------+--------------+---------------+-----------+----------+

    - En el campo 'cantidad' introduzca el número de unidades que venderá o de veces que ha prestado un servicio.
    - Agregue el producto a la grilla presionando el botón |plus.bmp|
    - Después de agregar el producto en la grilla, podrá modificar la casilla en la columna 'cantidad' siempre que lo considere necesario. Si no hay suficientes productos en existencia el sistema se lo hará saber.
    - En la esquina inferior derecha, podrá ver información relacionada a la facturación (Sub Total, impuestos, descuentos, retenciones y total)
    - Una vez esté seguro del total de la venta y los productos agregados, presione F2 si será cancelada estrictamente efectivo o F3 si será pagada a través de otro medio o en una combinación de ellos (cheque, tarjeta, crédito, efectivo, notas de crédito, etc).
    Si hay notas de crédito pendientes, podrá elegirlas de la lista de metodos de pago.


		.. figure:: images/3.png
 		  :align: center

    - Se desplegará una ventana de confirmación para imprimir o no el recibo/reporte de la venta.



Configurar resolución de facturación y Caja
===========================================

	- Ejecute la opción *Facturación a clientes*
	- Haga click en la flecha de la esquina superior derecha
	- Allí verá la opción desplegable "Configurar Resolución y caja", haga click en ella.
	- Seleccione en la lista de opciones la Resolución que quiera usar para facturar
	- Seleccione la Caja a la que se adjudicarán los montos de las ventas y los egresos por devolución.
	- Oprima 'Actualizar' |save.bmp|

   .. figure:: images/2.png
 	:align: center


Accesos rápidos de teclado
==========================

	- |F5.png|  Presione la tecla F5 para ubicar el cursor en la casilla de observación
	- |F6.png| Presione la tecla F6 para habilitar la venta de productos a precio de costo. En adelante, todos los productos se incluirán en la factura con su costo promedio. Si no tiene los permisos para esta función, comuníquese con el encargado de sistema.
	- |F7.png| Presione la tecla F7 para abrir el cajón monedero.
	- |F8.png| Presione la tecla F8 para ubicar el cursor en la casilla de búsqueda de productos.
	- |F9.png| Presione la tecla F9 para facturar a "Cuantías menores", saltando así el proceso de registro del cliente.
	- |F10.png| Presione la tecla F10 para imprimir la última factura emitida.
	- |ESC.png| Presione la tecla ESC para salir de esta pantalla





.. |F5.png| image:: /_images/generales/F5.png
.. |F6.png| image:: /_images/generales/F6.png
.. |F7.png| image:: /_images/generales/F7.png
.. |F8.png| image:: /_images/generales/F8.png
.. |F9.png| image:: /_images/generales/F9.png
.. |F10.png| image:: /_images/generales/F10.png
.. |ESC.png| image:: /_images/generales/ESC.png



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
