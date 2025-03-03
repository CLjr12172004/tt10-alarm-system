<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
Explain how your project works
El código VHDL describe un circuito lógico combinacional que implementa la función  Y = D AND (A OR B OR C), donde D actúa como un habilitador maestro y A, B, C son entradas de sensores,
dentro de esta carpeta se encuentra ajunta la imagen de la tabla de verdad.
Tenemos cuatro entradas y una salida:
  Entradas: A, B, C, D 
  Salida: Y 
Lógica de operación:
La salida Y se activa (Y <= '1') únicamente si, D = '1' (D actúa como habilitador del sistema) y en cualquier otro caso, Y permanece en '0'.
Su comportamiento es el siguiente:
  Primer comportamiento:
    Si D = '1:
      Si A = '1', B = '1', o C = '1' (o cualquier combinación de ellos), Y = '1'.
      Si A = '0', B = '0', y C = '0', Y = '0'.
  Segundo comportamiento:   
    Si D = '0:
      Y siempre será '0', independientemente de los valores de A, B o C.
## How to test

Explain how to use your project

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
