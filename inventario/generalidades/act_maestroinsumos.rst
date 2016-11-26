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

Crear un producto/servicio
--------------------------

- Ubique en el árbol la sub línea en la que desea crear el producto/servicio y selecciónela haciendo click sobre ella
- Haga click-derecho sobre la sub línea seleccionada para desplegar el menú contextual
- Seleccione la opción |wznew.bmp| *Nuevo producto* o *Nuevo Servicio* según sea el caso
- El sistema desplegará una ventana solicitando la siguiente información:


   :Nombre:
   Nombre del producto o la descripción del servicio.                   *

   :Referencia: 
   Si no la maneja, deje la que el sistema coloca por defecto.          *

   :Código EAN:
   Código de barras presente en el empaque del producto, si aplica.     *

   :UM: 
   Unidad de medida para el inventario, ej: Unidad, Metro, Litro.       *

   :Margen de IVA: 
   Porcentaje de IVA con el cual está gravado el producto/servicio.     *


  *Los campos señalados con un * son obligatorios*

**El código es único para cada producto/servicio y es generado por el sistema.**

- Llene los campos solicitados y finalice el proceso presionando el botón *Guardar* para cerrar la ventana o el botón *Guardar y Continuar* para continuar creando productos/servicios dentro de la línea y sub línea actual

En la siguiente imagen se puede apreciar la ventana de creación de productos/servicios

.. figure:: /_images/generales/placeholder.png
   :align: center

   Ventana de creación de productos/servicios

   Para agregar una imágen a un producto vea el apartado `Agregar imagen a un Producto`_

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


Descontinuar un Producto/Servicio
=================================

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

Re-Clasificar (Cambiar de línea) Producto/Servicio
==================================================

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

Permitir fraccionar un producto
-------------------------------

*Permitir Fracción*  es una opción útil para aquellas tiendas que manejen productos en cantidades con decimales. Por ejemplo una venta de verduras, frutas, cemento, arena, detergentes líquidos, etc. Estos productos se comercializan por unidades, kilos y litros expresados en números racionales. 

  .. Note:

  **Ejemplo** Una ferretería puede vender un Kilo y medio de cemento ( 1½Kg)

Para activar *Permitir Fracción*  habilite la edición del producto, vea `Editar un Producto/Servicio`_, y dirijase a la pestaña *Otros*, allí marque la opción 'Permitir fracción'. Una vez seguidos estos pasos podrá ingresar cantidades racionales en el proceso de venta de un producto. Recuerde que la unidad del producto (Kg, L, grs, UND) fue seleccionada en las características principales en el momento de su creación.

.. figure:: /_images/generales/placeholder.png
  :align: center

  En este campo puede introducir una cantidad decimal si lo desea. 


Acerca de los Servicios
=======================

Los *Servicios* forman parte del producto no tangible de su empresa: asesorías, consultas, trabajos intelectuales, diseños, balances, etc... y tienen ciertas características en las que se diferencian de un producto. 

  - Un Servicio no forma parte del inventario, no tiene Stock y no se puede acabar. Si no prestará más un servicio, entonces puede descontinuarlo. 

  - Puede agregar *Información extendida* a un servicio para poder agregar información detllada en la factura. Para activarla habilite la edición del servicio, vea `Editar un Producto/Servicio`_, y dirijase a la pestaña *Otros*, allí marque la opción 'Registrar información extendida'.
  Pueda Usar la *Información extendida* en el momento de incluir el servicio en la factura de venta. Verá algo como:

  .. figure:: /_images/generales/placeholder.png   
    :align: center

  En este campo puede introducir una descripción detallada del servicio que prestó.

    .. Note:
    **Ejemplo:** Incluya el servicio 'Reparación de electrodoméstico' y en información detallada puede colocar 'Licuadora Oster - Cambio de hojillas'




Familias de Productos
=====================

Introducción
------------

Usted podrá crear familias de productos para agrupar artículos que tengan las mismas especificaciones generales y varíen en algunos detalles no relevantes para su inventario como color, sabor, esencia, etc... Son útiles cuando varios de los artículos en su centro de costo posean características muy similares y usted no necesite diferenciarlos con referencias distintas.

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

  .. figure:: /_images/generales/placeholder.png   
    :align: center

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
  



Combos
======

Introducción
------------

Usted podrá agrupar sus productos en un *Combo* para facilitar la venta. De esta manera usted podrá ofrecer promociones a sus clientes y además agilizar la creación de las facturas. 

    .. Note:
    **Ejemplo 1:**
    Un *combo* puede referirse a la salida de inventario de un dispositivo móvil, una tarjeta de memoria SD y un forro de cuero, seleccionando el combo 'Promoción Celular' en su lista de productos al momento de hacer la factura.

Cuando un *Combo* es vendido, se hace automáticamente la salida del inventario de cada uno de los productos incluídos en él. El *Combo* no tiene existencia en el inventario, por lo tanto no podrá hacer entradas de él, ni tampoco verlo en los reportes de existencias o salidas en el inventario, ya que no es un producto sino una referencia para agilizar la venta de varios artículos a la vez.

  .. Note:
  **Ejemplo 1.1:**
  Al salir una 'Promoción Celular' por una venta, puede verificar en la factura que aparece el nombre del *Combo* =' Promoción Celular', mientras que en el inventario que la salida será la de un dispositivo móvil, una tarjeta de memoria SD y un forro de cuero.

Pre-requisitos
--------------

- Deberá haber creado los productos que van incluídos en el combo. Vea, `Crear un producto/servicio`_.
- Tener al menos una Linea y una Sub-Linea en la rama del arbol de productos bajo el apartado Combos y Presentaciones.

Crear un Combo
--------------

- Ubique en el árbol la sub línea en la que desea crear el *Combo* y selecciónela haciendo click sobre ella.
- Haga click-derecho sobre la sub línea seleccionada para desplegar el menú contextual.
- Seleccione la opción |wznew.bmp| *Nuevo Combo/presentación*.
- El sistema desplegará una ventana solicitando la siguiente información:

   :Nombre:
   Nombre del Combo.                   *

   :Referencia: 
   Si no la maneja, deje la que el sistema coloca por defecto.          *

   :Código EAN:
   Código de barras presente en el empaque del producto, si aplica.     

   :UM: 
   Unidad de medida para el inventario, ej: Unidad, Metro, Litro.       *

   :Margen de IVA: 
   Porcentaje de IVA con el cual está gravado el *Combo*.     *

 *Los campos señalados con un * son obligatorios*

**El código es único para cada *Combo* y es generado por el sistema.**

- Llene los campos solicitados y finalice el proceso presionando el botón *Guardar* |save.bmp| para cerrar la ventana o el botón *Guardar y Continuar* para continuar creando *Combos* dentro de la línea y sub línea actual.

Agregar productos al Combo
--------------------------

Pre-requisitos
^^^^^^^^^^^^^^

- Deberá haber creado un *Combo* anteriormente.
- Deberá haber creado un producto al menos para agregar al combo. Vea, `Crear un producto/servicio`_ 


Para agregar productos al Combo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

- Ubique el *Combo* en el árbol, vea : `Buscar un Producto/Servicio en el árbol`_..
- Haga click-dereho sobre el *Combo* seleccionado para desplegar el menú contextual.
- Haga click en la opción 'descargues automáticos' |wzedit.bmp|
- Se desplegará una ventana donde podrá buscar los productos |buscar.bmp| y agregarlos al Combo digitando el código del producto o presinando Enter para buscarlos en la lista de productos.
- Al seleccionar el producto que dese agregar verá una información desplegada de la siguiente manera:

  +------------+---------------------+--------+---------------+----------+----------+
  | referencia | nombre del producto | código | código rápido | cantidad ||plus.bmp||
  +------------+---------------------+--------+---------------+----------+----------+

- Inserte la cantidad del producto seleccionado que irá en el combo. 
- Presione Enter o haga click en el ícono |plus.bmp|
- Una vez satisfecho con todos los productos agregados al combo, guarde los cambios haciendo click en |save.bmp|.

  .. Note:
    Si desea eliminar un producto que acaba de agregar al combo o que ya estaba agregado, puede en esta misma lista, situar el cursor en el código de la linea del producto y presionar la tecla 'Supr'. 


Presentaciones
==============

Introducción
------------
Las presentaciones son una manera de agrupar productos que se venden o adquieren en cantidades fijas mayores a una unidad. Usted podrá dar salida o entrada a varias unidades del inventario al mismo tiempo seleccionando una presentación cuando quiera hacer una venta o, una compra a proveedor.

    .. Note:
    Ejemplo 2:
    Cree una 'unidad de huevo' para luego crear presentaciones de varias cantidades. Puede agrupar las 'unidades de huevo' en una presentación de docena, de 24 unidades, etc.

Cuando una *Presentacion* es vendida, se hace automáticamente la salida del inventario de la cantidad del producto establecida en su creación. La *Presentación* no tiene existencia en el inventario, por lo tanto no podrá verlo en los reportes de existencias o salidas en el inventario, ya que no es un producto sino una referencia para agilizar la venta de varias unidades de un mismo artículo a la vez.

  .. Note:
  Ejemplo 2.1
  Cuando a través de una venta de salida a una 'docena de huevos', entonces podrá ver en la factura reflejado el nombre de la *Presentación* = 'docena de huevos' y la cantidad, mientras que si verífica en el inventario, verá que la salida fue de 12 'unidades de huevo' a la vez.

  
Pre-requisitos
--------------

- Deberá haber creado un producto principal en unidad, que luego agrupará en la *Presentación*, Ejemplo: Huevo. Vea, `Crear un producto/servicio`_.
- Tener al menos una Linea y una Sub-Linea en la rama del arbol de productos bajo el apartado *Combos y Presentaciones*.

Crear una Presentación
----------------------

- Ubique en el árbol la sub línea en la que desea crear La *Presentación* y selecciónela haciendo click sobre ella.
- Haga click-derecho sobre la sub línea seleccionada para desplegar el menú contextual.

  .. figure:: /_images/generales/placeholder.png   
    :align: center

- Seleccione la opción |wznew.bmp| *Nuevo Combo/presentación*.
- El sistema desplegará una ventana solicitando la siguiente información:

   :Nombre:
   Nombre de la presentación.                   *

   :Referencia: 
   Si no la maneja, deje la que el sistema coloca por defecto.          *

   :Código EAN:
   Código de barras presente en el empaque del producto, si aplica.     

   :UM: 
   Unidad de medida para el inventario, ej: Unidad, Metro, Litro.       *

   :Margen de IVA: 
   Porcentaje de IVA con el cual está gravada la *Presentación*.     *

 *Los campos señalados con un * son obligatorios*

**El código es único para cada *Prensentación* y es generado por el sistema.**

- Llene los campos solicitados y finalice el proceso presionando el botón *Guardar* |save.bmp| para cerrar la ventana o el botón *Guardar y Continuar* para continuar creando *Presentaciones* dentro de la línea y sub línea actual.


Agregar productos a la Presentación
-----------------------------------

Pre-requisitos
^^^^^^^^^^^^^^

- Deberá haber creado una *Presentación* anteriormente.
- Deberá haber creado un producto al menos para agregar a la presentación. Vea, `Crear un producto/servicio`_ 


Para agregar productos a la presentación
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

- Ubique la *Presentación* en el árbol, vea : `Buscar un Producto/Servicio en el árbol`_..
- Haga click-dereho sobre la *Presentacion* seleccionado para desplegar el menú contextual.
- Haga click en la opción 'descargues automáticos' |wzedit.bmp|
- Se desplegará una ventana donde podrá buscar los productos |buscar.bmp| y agregarlos a la presentación digitando el código del producto o presinando Enter para buscarlos en la lista de productos.

  .. figure:: /_images/generales/placeholder.png   
    :align: center

- Al seleccionar el producto que dese agregar verá una información desplegada de la siguiente manera:

  +------------+---------------------+--------+---------------+----------+----------+
  | referencia | nombre del producto | código | código rápido | cantidad ||plus.bmp||
  +------------+---------------------+--------+---------------+----------+----------+

- Inserte la cantidad del producto seleccionado que irá en la presentación. 

  -- Note:
  **Ejemplo 2.2**
  En la creación de la *Presentación* 'Docena de Huevos', seleccione el producto 'Huevo' y en el campo cantidad digite '12'.

- Presione Enter o haga click en el ícono |plus.bmp|
- Una vez satisfecho con el producto agregados a la presentación y su cantidad, guarde los cambios haciendo click en |save.bmp|.

  .. Note:
    - Si desea eliminar un producto que acaba de agregar a la presentación que ya estaba agregado, puede en esta misma lista, situar el cursor en el código de la linea del producto y presionar la tecla 'Supr'.
    - Recuerde que la idea es que una presentación sea un aglomerado de unidades de un solo producto, por ejemplo: una docena de globos.


Actualización de Códigos EAN
============================

Esta interfaz le permite actualizar los códigos EAN (barras) de cualquier producto, de una manera más sencilla que la interfaz de edición de producto.

  - Ejecute la opción *Catálogo de productos y servicios*
  - En la cabecera de la ventana desplegada, haga click en el botón |codbar.bmp|
  - Vera una nueva ventana como esta:

      .. figure:: /_images/generales/placeholder.png   
      :align: center


  - El cursor se colocará en el primer cuadro de texto. Si sabe el código del producto digítelo, ingréselo con el lector láser, o también oprima Enter y búsquelo en la lista de productos. 
  - Una vez seleccionado el producto, se mostrará su nombre en el segundo campo de texto y el cursor se posará sobre el tercer campo de texto.
  - Ingrese el nuevo código EAN y presione Enter para cambiar el código.
  - Una vez haya presionado enter el producto tomará inmediatamente el nuevo código
  - Vera la lista de productos a los que cambió el código en la grilla inferior a los campos de texto.

  Impresión de código de barras
  =============================

  Esta interfaz le permite acceder rápidamente e imprimir las etqiuetas de código de barras de uno o más productos.

    - Ejecute la opción *impresión de código de barras* |imprimircodbar.bmp|
  - En la ventana que se desplega, elija el centro de costo donde se encuentran los productos que desea marcar con las etiquetas.
  - Elija la lista de precios que se manejarán en caso de que el formato de sticker que elija tenga el precio incluído.
  - Ahora puede proceder a insertar los artículos que desea marcar:
    - Haga click en la cabezera de la columna 'Código' en la grilla.
    - Se crea un nueva linea en la grilla, y el foco se ubicará en la columna código. Presione Enter.
    - Se desplegará una ventana con la lista de productos y usted podrá hacer click en cualquiera y presionar Enter para seleccionarlo.
    - Verá el producto que seleccionó en la grilla. 
    - La casilla en la columna 'Cantidad' es modificable. Digite allí el número de etiquetas para este producto que desea imprimir.
    - La casilla en la columna 'Valor' es modificable. Digite allí el precio de este producto.

      .. Note:

      No es obligatorio colocar el precio en la columna 'Valor' si no eleigió mostrar el precio del producto en la eqtiqueta. Vea `Configuración de Stickers`_

      En cualquier caso, el precio que coloque en la columna 'Valor', siempre modificará el valor en la 'Lista de precios "1"', vea `Configuración de listas de precio por defecto <>`_

    -Puede insertar los productos que quiera a la grilla. Para insertar de nuevo un producto, sitúese en la fila del último producto de la grilla y presione la tecla direccional 'abajo' ↓ dos veces.
  - Bajo la grilla encontrará una lista donde podrá cambiar la configuración del Sticker. Si desea crear una nueva configuración de sticker, entonces presione el botón |wzedit.bmp| y vea `Configuración de Stickers`_
  - Luego, encontrará otra lista donde debe seleccionar el formato de impresión.
  - Puede realizar una vista previa presionando el ícono |printer_q.bmp| a la izquierda.
  - Para imprimir las etiquetas de los productos en la grilla, según lo que indicó en la columna *Cantidad* y *Valor*, presione F2 o haga click en |printer_q| a la derecha.

--------------------------------------------

.. |plus.bmp| image:: /_images/generales/plus.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp
.. |wznew.bmp| image:: /_images/generales/wznew.bmp