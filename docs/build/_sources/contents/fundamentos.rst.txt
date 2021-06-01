.. highlight:: verilog

Fundamentos del lenguaje Verilog
================================

En esta sección se cubren los principales fundamentos del lenguaje de descripción de hardware Verilog.

Módulos
-------

Un módulo en Verilog es un bloque de código que ejecuta cierta funcionalidad. Un módulo puede contener una instancia de otro módulo, y el módulo de nivel superior puede comunicarse con los módulos de nivel inferior a través de sus puertos de entrada y salida.

Sintaxis
^^^^^^^^

Los módulos se definen entre las *keywords* ``module`` y ``endmodule``. El nombre del módulo se coloca inmediatemente después de ``module`` y además se pueden definir sus puertos, de la siguiente manera::

    module <nombre> ([lista_de_puertos]);
        // Contenido del modulo
    endmodule



Simulación y Síntesis
---------------------

Convenciones de Léxico
----------------------

Tipos de Datos
--------------

Modelado por Flujo de Datos: RTL
--------------------------------

Modelado Estructural
--------------------

Diseño Secuencial
-----------------

If-Then-Else
^^^^^^^^^^^^

Asignaciones bloqueantes y no-bloqueantes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

FlipFlops, Registros y Latches
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Sentencia Case
^^^^^^^^^^^^^^

Máquinas de Estado Sincrónicas
------------------------------

System Tasks, System Function
-----------------------------

Módulo Testbench
----------------