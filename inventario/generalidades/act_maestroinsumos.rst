=================================
Catálogo de Productos & Servicios
=================================

Ubicación
=========

:Módulo:
 Inventario

:Grupo:
 Parámetros

:Descripción:
 Catálogo de productos & servicios

Introducción
============

El catálogo de productos/servicios es el origen de los procesos de inventario; en él se administra toda la información referente a los productos/servicios que son comercializados por la empresa.

El catálogo de productos/servicios le permitirá entre otras cosas:

- Crear/editar/eliminar líneas/categorías de productos/servicios
- Crear/editar/eliminar sub lineas/sub categorías de productos/servicios
- Crear/editar/eliminar productos/servicios
- Buscar productos/servicios
- Entre otras

En el catálogo de productos podrá crear las siguientes clases de items:

:Productos:
  Manejan inventario

:Servicios:
  No manejan inventario

:Presentaciones:
  No manejan inventario y hacen referencia a una cantidad especifica de productos

Cada tipo de item está representado por una carpeta en el árbol de productos, como se muestra en la siguiente imagen

.. figure:: /_images/generales/placeholder.png
   :align: center

   Tipos de items

Adicionalmente podemos indicarle al sistema cuales de estos tipos de items deseamos manejar en el catálogo, de manera que si por ejemplo, no queremos manejar servicios, podemos remover la carpeta de servicios para que no nos aparezca en el catálogo de productos.

A continuación se detallan los componentes básicos del catálogo de productos/servicios

Líneas de Productos/Servicios
=============================

Introducción
------------

Las líneas de productos/servicios son el primer nivel de clasificación de la mercancía, el sistema clasifica todos los productos/servicios que se crean en una categoría/línea.

.. figure:: /_images/generales/placeholder.png
   :align: center

   En esta imagen podemos apreciar algunas líneas de productos, por ejemplo : Línea 1, Línea 2, Línea 3, Etc...

Crear una Línea
---------------

Para crear una línea de productos/servicios siga los siguientes pasos:

- Haga click-derecho sobre la carpeta correspondiente al tipo de item (productos, servicios, presentaciones) para desplegar el menu contextual
- Seleccione la opción |wznew.bmp| *Nueva Línea*
- El sistema creará una carpeta con el siguiente texto : *Digite el nombre de la línea*
- Reemplace el texto: *Digite el nombre de la línea* con el nombre de la línea correspondiente y confirme presionando la tecla ENTER

Editar una Línea
-------------------

Para editar una línea de productos/servicios siga los siguientes pasos:

- Ubique en el árbol la línea que quiere editar y selecciónela haciendo click sobre ella
- Haga click-derecho sobre la línea seleccionada para desplegar el menú contextual
- Seleccione la opción |wzedit.bmp| *Modificar línea*
- El nombre de la línea se marcará en azul, indicando que puede editar el texto
- Edite el nombre de la línea haciendo los cambios necesarios y confirme con ENTER

Eliminar una Línea
---------------------

Para eliminar una línea de productos/servicios siga los siguientes pasos:

- Ubique en el árbol la línea que quiere eliminar y selecciónela haciendo click sobre ella
- Haga click-dereho sobre la línea seleccionada para desplegar el menú contextual
- Seleccione la opción |delete.bmp| *Eliminar línea*
- El sistema le pedirá que confirme su intención de eliminar la línea
- Confirme la solicitud de eliminación

.. NOTE::
   No podrá eliminar líneas que contengan sub líneas, en estos casos la opción : *Eliminar línea*, aparecerá desactivada

Sub Lineas de Productos/Servicios
=================================

Introducción
------------

Las sub líneas de productos/servicios son el segundo nivel de clasificación de la mercancía, las sub líneas se alojan dentro de las líneas y son las sub líneas las que alojan a los productos/servicios.

.. figure:: /_images/generales/placeholder.png
   :align: center

   En esta imagen podemos apreciar que la línea *PC'S DE ESCRITORIO* contiene las sub líneas *Board*, *Procesador*, *RAM*, *Disco Duro*, *Monitor*, etc..

Crear una Sub Línea
-------------------

Para crear una sub línea de productos/servicios siga los siguientes pasos:

- Ubique en el árbol la línea en la cual desea crear la nueva sub línea y selecciónela haciendo click sobre ella
- Haga click-dereho sobre la línea seleccionada para desplegar el menú contextual
- Seleccione la opción |wznew.bmp| *Nueva sub línea*
- El sistema creará una carpeta con el siguiente texto : *Digite el nombre de la sub línea*
- Reemplace el texto: *Digite el nombre de la sub línea* con el nombre de la sub línea correspondiente y confirme presionando la tecla ENTER

Editar una Sub Línea
--------------------

Para editar una sub línea de productos/servicios siga los siguientes pasos:

- Ubique en el árbol la sub línea que desea editar y selecciónela haciendo click sobre ella
- Haga click-derecho sobre la sub línea seleccionada para desplegar el menú contextual
- Seleccione la opción |wzedit.bmp| *Modificar sub línea*
- El nombre de la sub línea se marcará en azul, indicando que puede editar el texto
- Edite el nombre de la sub línea haciendo los cambios necesarios y confirme con ENTER

Eliminar una Sub Línea
----------------------

- Ubique en el árbol la sub línea que desea eliminar y selecciónela haciendo click sobre ella
- Haga click-derecho sobre la sub línea seleccionada para desplegar el menú contextual
- Seleccione la opción |delete.bmp| *Eliminar sub línea*
- El sistema le pedirá que confirme su intención de eliminar la sub línea
- Confirme la solicitud de eliminación

.. NOTE::
   No podrá eliminar sub líneas que contengan productos/servicios, en estos casos la opción : *Eliminar sub línea*, aparecerá desactivada

Productos & Servicios
=====================

Introducción
------------

Los productos/servicios son el último nivel en el árbol, contienen la información necesaria para facilitar su compra/venta.

.. figure:: /_images/generales/placeholder.png
   :align: center

   En esta imagen podemos apreciar el producto x, que se encuentra dentro de la línea z y la sub línea t

Entre las principales características de los productos/servicios podemos encontrar:

:Código:
  Código único del producto/servicio en el sistema (Generado por el sistema)

:Nombre:
  Nombre del producto o descripción del servicio (Obligatorio)

:UM:
  Unidad de medida del producto, ej: Unidad, Metro, Litro, etc... (Obligatorio)

:Referencia:
  Referencia del producto (Obligatorio)

:IVA:
  Margen de IVA con el que se compra/vende el producto (Obligatorio)

:Imagen:
  Imagen que represente al producto/servicio (Opcional)

Crear un producto/servicio
--------------------------

Para crear un productos/servicios siga los siguientes pasos:

- Ubique en el árbol la sub línea en la que desea crear el producto/servicio y selecciónela haciendo click sobre ella
- Haga click-derecho sobre la sub línea seleccionada para desplegar el menú contextual
- Seleccione la opción |wznew.bmp| *Nuevo producto* o *Nuevo Servicio* según sea el caso
- El sistema desplegará una ventana solicitando la siguiente información

 - **Nombre del producto/servicio** (Nombre del producto o la descripción del servicio)
 - **Referencia** (Si no la maneja, deje la que el sistema coloca por defecto)
 - **Código EAN** (Código de barras presente en el empaque del producto, si aplica)
 - **UM** (Unidad de medida para el inventario, ej: Unidad, Metro, Litro)
 - **Margen de IVA** (Margen de IVA con el cual está gravado el producto/servicio)

- Llene los campos solicitados y finalice el proceso presionando el botón *Guardar* para cerrar la ventana o el botón *Guardar y Continuar* para continuar creando productos/servicios dentro de la línea y sub línea actual

En la siguiente imagen se puede apreciar la ventana de creación de productos/servicios

.. figure:: /_images/generales/placeholder.png
   :align: center

   Ventana de creación de productos/servicios

Buscar un Producto/Servicio en el árbol
---------------------------------------

Con un catálogo muy extenso, puede ser difícil ubicar un producto/servicio en el árbol; por esta razón existe un mecanismo de búsqueda que le permitirá ubicar fácilmente el ítem que necesite.

Para buscar un productos/servicio siga los siguientes pasos:

- En la ventana principal del *Catálogo de productos* haga click en icono |buscar.bmp|
- El sistema despliega la búsqueda de productos/servicios
- Digite el nombre del producto/servicio
- Confirme la selección colocándose sobre el producto/servicio y presionando la tecla ENTER o haciendo doble-click
- El sistema ubicará el producto/servicio en el árbol y desplegará sus características en el panel de detalles

Editar un Producto/Servicio
---------------------------

Para editar un productos/servicio siga los siguientes pasos:

- Ubique el producto/servicio en el árbol, vea : `Buscar un Producto/Servicio en el árbol`_.
- En el panel de detalles haga click en el icono |wzedit.bmp| para habilitar la edición de las propiedades del producto/servicio
- Realice los cambios pertinentes
- En el panel de detalles haga click en el icono |save.bmp| para guardar los cambios

Eliminar un Producto/Servicio
-----------------------------

Para eliminar un productos/servicio siga los siguientes pasos:

- Ubique el producto/servicio en el árbol, vea : `Buscar un Producto/Servicio en el árbol`_.
- Haga click-derecho sobre el producto/servicio seleccionado para desplegar el menú contextual
- Seleccione la opción |delete.bmp| *Eliminar producto* o *Eliminar servicio* según el caso
- El sistema pedirá confirmar la solicitud de eliminación
- Confirme la solicitud de eliminación

.. NOTE::
   No podrá eliminar productos que presenten movimientos en el kardex o servicios que hayan sido facturados.

Descontinuar un Producto/Servicio
---------------------------------

Después de un tiempo considerable creando productos/servicios se encontrará con la necesidad de eliminar algunos que ya no se vayan a seguir utilizando, sin embargo el sistema no permitirá eliminar productos/servicios que hayan tenido algún tipo de movimiento debido a que esta información es necesaria a nivel estadístico; por esta razón existe la posibilidad de **descontinuar** productos; al descontinuar un producto este desaparece de todas las operaciones de inventario, por ejemplo : entradas, salidas, traslados y únicamente es visible en las estadísticas de las operaciones registradas previas a su discontinuación.

Para descontinuar un producto/servicio siga los siguientes pasos:

- Ubique el producto/servicio en el árbol, vea : `Buscar un Producto/Servicio en el árbol`_.
- Haga click-dereho sobre el producto/servicio seleccionado para desplegar el menú contextual
- Seleccione la opción |descartar.bmp| *Descontinuar <<producto/servicio>>*
- El sistema pedirá confirmar la solicitud de descontinuar el producto/servicio
- Confirme la solicitud de discontinuación

.. NOTE::
   No podrá descontinuar productos que presenten existencias en el inventario

Reactivar Producto/Servicio
----------------------------

El proceso de reactivación es inverso al proceso de discontinuación, consiste volver a activar productos que se encuentren descontinuados para permitir nuevamente su uso.

Para reactivar productos/servicios siga los siguientes pasos:

- En la ventana principal del *Catálogo de productos* haga click en icono |btn_ok.bmp|
- El sistema abrirá una ventana donde se listan los productos descontinuados
- La ventana posee una casilla de búsqueda que le permitirá ubicar facilmente el producto que requiera
- Para reactivar el producto/servicio ubíquelo en el listado y seleccione la casilla de verificación que se encuentra en la última columna
- Una vez seleccionados los productos que desea reactivar, presione el botón |refresh.bmp| *Reactivar*

Re-Clasificar Producto/Servicio
-------------------------------

La correcta clasificación de los productos/servicios en líneas y sub líneas, es muy importante porque nos permite:

- Ubicar fácilmente y de manera lógica los productos/servicios en el árbol
- Obtener estadísticas de ventas e inventarios por medio de esta clasificación
- Establecer la interface contable de los productos/servicios por medio en esta clasificación

Durante el proceso de creación de productos/servicios, será necesario *mover* productos/servicios de una línea *X* a una línea *Y*, o incluso, a una sub línea diferente a la actual; Esta es la función de la re-clasificación de productos/servicios.

La re-clasificación le permitirá estructurar el catálogo de productos/servicios de la manera que considere mas provechosa para la empresa

Para re-clasificar productos/servicios siga los siguientes pasos:
  - Ubique el producto/servicio en el árbol, Vea : `Buscar un Producto/Servicio en el árbol`_.
  - Haga click-derecho sobre el producto y verá la opción |wzedit.bmp| *cambiar de linea*.
  - Verá una ventana desplegarse. Seleccione en la lista la línea a la cual desea cambiarse.
  - Aparecerá una nueva lista con las sublíneas. Seleccione la sublínea para la cual desea cambiarse.
  - Haga click en el botón *Guardar* |save.bmp|


Familias de Productos
=====================

Introducción
------------

Usted podrá crear familias de productos para agrupar artículos que tengan las mismas especificaciones generales y varíen en algunos detalles no relevantes para su inventario como color, sabor, esencia, etc... Esta opción le será útil cuando varios de los artículos en su centro de costo posean características muy similares y usted no necesite diferenciarlos con referencias distintas.

Pre-requisitos 
--------------

  Para agregar un producto a una familia, primero deberá:
    - Crear un producto, vea `Crear un producto/servicio`_: Este producto deberá tener especificaciones generales y sin ingresar un código de barra.
    
       **Ejemplo 1**
        
       Si desea crear una familia de velas aromáticas cuyas esencias comprenden: fresa, mandarina, manzana, etc... entonces primero deberá crear un producto llamado 'Vela Aromática' y agregar en él solo las especificaciones que coincidan con todos los miembros de la familia, como por ejemplo en este caso: el peso o el número de unidades por empaque.
        
Para agregar productos a una familia
------------------------------------

Para agregar diferentes productos a una misma familia siga estos pasos:
  - Ubique el producto/servicio en el árbol, Vea : `Buscar un Producto/Servicio en el árbol`_.
  - En el panel de detalles haga click en el icono |wzedit.bmp| para habilitar la edición de las propiedades del producto.
  - Pulse el botón *contabilidad* y aparecerá una ventana flotante.
  - En las pestañas, haga click en *familia*, aquí podrá agregar seguidamente todos los productos que pertenezcan a la misma familia.
    
   .. Note::
    
    Cada producto de características específicas, aunque pertenezca a la misma familia, tiene un código de barras diferente. 
    
  - Ingrese en *Cód. Barra* el código de barra del producto específico que agregará a la familia.
  - En el siguiente cuadro de texto indique la característica específica que lo hace diferente al resto de la familia (color, esencia, sabor, etc...)
  
        **Ejemplo 1.1**
      
        Según el Ejemplo 1, quedaría de la siguiente forma
        Cód. barra |########| Variante |mandarina|
  
  - Presione Enter, y vea como es agregado a la lista.
  - A continuación puede seguir agregando productos a la familia o guardar los cambios en el Icono |save.bmp| Guardar.
  

Agregar/QUitar Imagen a un Producto
===================================

Agregar imagen a un Producto
----------------------------
Introducción
^^^^^^^^^^^^
Use las imágenes de los productos para identificarlos de mejor manera. Podrá agregar una sola imagen a cada artículo y quitarla cuando lo desee.

Pre-requisitos
^^^^^^^^^^^^^^

Para agregar la imagen a un Producto usted primero deberá:
    - Haber creado el producto anteriormente, vea `Crear un producto/servicio`_.
    
Para agregar imagen a un Producto
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Para agregar una imagen a un producto siga los siguientes pasos:
  - Ubique el producto en el árbol, vea : `Buscar un Producto/Servicio en el árbol`_.
  - En el panel de detalles haga click en *habilitar edición* |wzedit.bmp| para habilitar la edición de las propiedades del producto.
  - Haga doble click en el cuadro designado para la imagen.
  - Aparecerá un cuadro de dialogo donde podrá ubicar el archivo de imagen que necesita para el producto, selecciónelo y haga click en 'Abrir'. Recomendable JPEG.
  - Vera la imagen adaptada al cuadro. Ahora puede guardar los cambios haciendo click en *guardar* |save.bmp|
 
Quitar imagen a un Producto
---------------------------

Pre-requisitos
^^^^^^^^^^^^^^

Para Quitar la imagen a un Producto usted primero deberá:
    - Haber creado el producto anteriormente, vea `Crear un producto/servicio`_.
    - Haber agregado una imagen al producto seleccionado.
    
Para quitar imagen a un Producto
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Para quitar la imagen a un producto existente siga los siguientes pasos:
  - Ubique el producto en el árbol vea : `Buscar un Producto/Servicio en el árbol`_.
  - En el panel de detalles haga click en *habilitar edición* |wzedit.bmp| para habilitar la edición de las propiedades del producto.
  - Haga click-derecho en el cuadro designado para la imagen.
  - Aparecerá un pequeño recuadro con el símbolo |delete.bmp| y con el texto 'Quitar Imagen', haga click en él.



--------------------------------------------

.. |wznew.bmp| image:: /_images/generales/wznew.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp
