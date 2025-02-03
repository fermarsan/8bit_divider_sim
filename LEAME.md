# Simulación de un divisor secuencial de 8 bits

Este ejemplo implementa una simulación de un divisor secuencial digital de 8 bits en [SimulIDE](https://simulide.com/p/), que está compuesta por:

- registros de desplazamiento a la derecha de entrada paralela dual de 8 bits (16 bits) (subcircuitos)
- registro de desplazamiento a la izquierda de salida paralela de 8 bits (subcircuito)
- registro de carga paralela de 8 bits (subcircuito)
- comparador de cero de 4 bits
- sumador de 8 bits (subcircuito)
- selector/multiplexor de 2 entradas de 8 bits
- módulo de complemento a dos de 8 bits
- contador descendente de 4 bits
- máquina de estados finitos FSM como bloque de control (script) [archivo readme de un circuito similar](/FSM/README.md)

![](assets/Divider.png)
También puedes ver este [tutorial](https://youtu.be/PAcU9CNJh7A?si=TVzpL2JlhtzKox_8) (en español) sobre un circuito similar.

Esto se hace como ejercicio didáctico en _SimulIDE_, para que los usuarios implementen por sí mismos la Unidad de Control (FSM) del divisor.

## Uso
Hay que copiar todas las carpetas de los componentes dentro de una en la carpeta de datos de usuario, por ejemplo `~/User_data/test` y asociarla en Simulide.
Puedes ver cómo hacer esto en los Tutoriales oficiales de SimulIDE:
[Carpeta de datos de usuario SimulIDE 1.1.0](https://www.youtube.com/watch?v=pAU7fdUWCqs)
[Crear Componentes SimulIDE 1.1.0 ](https://www.youtube.com/watch?v=LBknR6y5Qho) (español)
