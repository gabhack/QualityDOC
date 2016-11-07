=========================================
Definición de Transacciones de Inventario
=========================================

Ubicación
=========

:Módulo:
 Inventario

:Grupo:
 Parámetros

:Descripción:
 Definición de transacciones de inventario

Introducción
============

Las *Transacciones de Inventario* son todos los tipos de movimientos de inventario que pueden ser realizados en el sistema,
como por ejemplo: *SALDOS INCIALES DE INVENTARIOS*, *SALIDAS POR AJUSTE CREDITO*, *ENTRADAS POR COMPRAS*, etc ...,
Estas transacciones están identificadas por un código compuesto de 3 carácteres, para las 3 transacciones citadas anteriormente
los códigos serían *_II*, *_SC*, *_EC* respectivamente.

Al utilizar tipos de movimientos diferentes para realizar nuestras entradas y salidas de inventario, la información se clasifica y esto nos permite generar informes
de movimientos de inventarios por un tipo especifico.

Tipos de Transacciones de Inventario
====================================

Principalmente, existen 2 tipos de *Transacciones de Inventario* : transacciones de entrada y transacciones de salida, y dentro de estas
2 clasificaciones existen 2 sub clasificaciones adicionales : transacciones de sistema y transacciones de usuario,
a continuación se detallan las principales diferencias.

- **Transacciones de Entrada**:
  Son transacciones que incrementan las existencias de los productos en el inventario.

- **Transacciones de Salida**:
  Son transacciones que disminuyen las existencias de los productos en el inventario.

- **Transacciones de sistema**:
  Son transacciones que crea el sistema **Quality** de manera automática, por lo tanto, no pueden ser eliminadas, su edición es controlada y
  pueden ser de *Entrada* o de *Salida*.

  Algunos ejemplos de transacciones del sistema, son :

  - *_EC - ENTRADA DE ALMACÉN POR COMPRAS*
  - *_FC - FACTURACIÓN DE CREDITO*
  - *_ST - SALIDA DE ALMACÉN POR TRASLADOS*

- **Transacciones de usuario**:
  Son transacciones que crean los usuarios del sistema **Quality**, son personalizadas a las necesaidades, pueden ser editadas
  abiertamente por los usuarios del sistema y pueden ser de *Entrada* o de *Salida*.

Afectación Contable
===================

Cada *Transacción de Inventario* creada por usuarios, puede afectar contabilidad si se establece la cuenta contable que actuará como
contra-partida a la cuenta de inventario (14), aunque es algo opcional a nivel de sistema, no se recomienda crear *Transacciones de Inventario*
que no tengan efecto contable, ya que de esta manera se afecta negativamente la información contable.

Crear Transacción de Inventario
===============================

Para crear una *Transacción de Inventario* siga los siguientes pasos:

- Ejecute la opción *Definición de transacciones de inventario*
- Haga clic en el botón *Nuevo* |wznew.bmp|
- El sistema abrirá una ventana solicitando la siguiente información

  - **Código** : Código de la *Transacción de Inventario*, el código es de 3 carácteres pero solo se deben especificar 2, ya que el primer caracter siempre va a ser
    un guión al piso (_)
  - **Tipo** :
    Tipo de afectación de la transación en el inventario (*Entrada* o *Salida*)
  - **Nombre** :
    Nombre de la *Transacción de Inventario*, se deben elegir nombres que representen con claridad la intención de la transacción.
  - **Cuenta** :
    Cuenta contable que se usará como contra-partida para contabilizar la transacción (**NO** es la cuenta de inventario (14))

.. |br| raw:: html

- LLene los datos solicitados y confirme presionando el botón *Guardar* |save.bmp|

Modificar Transacción de Inventario
===================================

Eliminar Transacción de Inventario
==================================

.. |wznew.bmp| image:: /_images/generales/wznew.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp
