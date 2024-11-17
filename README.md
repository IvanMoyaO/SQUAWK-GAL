El código SQUAWK es un código octal de cuatro números (0000 - 7777). Para codificarlo, en binario, A4 A2 A1 B4 B2 B1 C4 C2 C1 D4 D2 D1. 
Buscamos que cada pulso (A4, A2, etc) tenga una duración de 1 us, con una separación de 2us. Por tanto, buscamos una secuencia tal que así (x = pulso): - - x - - x - - x - - x. Vemos que los pulsos estarán en una posiciones determinadas. Por ende, la práctica se reduce a hallar las ecuaciones de un contador 0-35 (12 * 3 = 36), 
y añadir una salida (Z) que "saque" el valor de las entradas de los microinterruptores en unos cuentas determinadas (en: 2 + 3n). 

Respecto al circuito, es simplemente conectar los interruptores a la GAL. 
