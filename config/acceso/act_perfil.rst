===================================
Administrador de perfiles de acceso
===================================

Ubicación
=========

:Módulo:
 Configuración

:Grupo:
 Parámetros

:Descripción:
  Administrador de perfiles de acceso

Introducción
============

	Use esta interfaz para crear perfiles de usuario que determinen la cantidad de permisos que tiene hacia las distintas opciones del sistema. Puede modificar estos perfiles cuando lo desee. 

		.. NOTE::

			Algunos procesos tienen un 'Clip' al final de la fila. Estos procesos pueden ser administrados para dar permisos específicos a las opciones que manejan internamente.

Crear un perfil de usuario
==========================

	Para crear un perfil realice los siguientes pasos:

		- Ejecute la opción *Administrador de perfiles de acceso*
		- Haga click en el botón |plus.bmp| para crear un nuevo perfil
		- Coloque el nombre del nuevo perfil en el campo de texto en la parte superior
		- En la lista de opciones del sistema, marque aquellas a las que el usuario podrá tener acceso. Si marca la casilla de verificación de un módulo (Almacén y control de inventarios, Facturación y ventas, etc) entonces se marcarán todos los procesos internos.

		.. NOTE::

			Algunas opciones como 'Entradas, salidas y transferencias' tienen permisos internos, por ejemplo, usted podría denegar el accesoa  hacer 'Salidas' si lo desea. Estos permisos internos no son relaizables desde esta interfaz, sino en la pantalla principal una vez el perfil ya ha sido creado. 

		- Haga click en |save.bmp| para guardar el perfil


Permisos específicos sobre un proceso amplio
============================================

	Para asignar permisos más específicos en procesos amplios, realice los siguientes pasos:

		- Ejecute la opción *Administrador de perfiles de acceso*
		- Seleccione el perfil en la parte superior de la ventana. Puede seleccionar el modulo si lo desea, si no, visiualiza todos en pantalla.
		- Algunos procesos tienen un 'Clip' al final de la fila. Estos procesos pueden ser administrados para dar permisos específicos a las opciones que manejan internamente. 

			.. NOTE::

			Ejemplo: En la opción 'Entradas, salidas y transferencias' puede permitir el acceso a la opción Entradas y negarlo para el resto.

		- Haga click en el 'Clip' del proceso que desea administrar. Verá una ventana con dos pestañas:

			- La primera pestaña 'Control de acceso' funciona para los procesos de los módulos y le permite autorizar o negar permisos internos de la operación
			- La segunda pestaña 'Campos obligatorios' se activa en los parámetros del módulo, y le permite especificar los campos que el usuario necesariamente debera rellenar en la creación de un parámetro.

		- Una vez asignados los permisos puede cerrar la ventana. 









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