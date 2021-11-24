## RIMERA PREUBA

Primer error de Arduino :

avrdude: ser_open(): can't open device "/dev/ttyACM0": Permission denied

El error se debe a que no puede acceder al puerto.
Protoboard
                    
Intentamos programarl programa de ejemplo blink.ino pero el programa avrdude lanzó una excepción y detuvo el programa. Esto por un tema de permisos de usuario.

En Linux hay dos tipos de usuario: El usuario y el superusuario.
Primeros circuitos
Circuito simple

Este pese a funcionar y dar luz genera dos problemas:
 
Circuito en serie

Si desconectamos una parte no funciona
Circuito en paralelo

Da igual si una parte se desconecta
Apuntes sobre electricidad

Voltaje --> Altura (Diferencia de potencial)

Intensidad o Amperaje --> cantidad de agua o rotuladores

Resistencia --> Resistencia al paso del agua o rotulador

Intensidad = Voltaje ÷ Resistencia ---> Ley de Ohm

Voltaje = Intesidad x Voltaje

Resistencia = Voltaje ÷ Intensidad
Por qué necesitamos resistencias con los LEDs?

Tenemos 2 circuitos

Circuito 1 : 5V,GND 0V

Circuito 2 : 5V, bombilla, GND 0V

El voltaje de los dos circuitos es 5V.

Y la resistencia? Circuito 1, 1 Ohm Circuito 2 440 Ohms

5V ÷ 441 Ohms = 0,01133 A = 11,33 mA

5V ÷ 1 Ohm = 5 A

5V ÷ 0 Ohm = ∞ A (Cortocircuito) ---> Evitar
Lenguaje de programación

## errrores y excepciones
-BUG: Es un problema en un programa de un ordenador o sistema de software que desencadena un resultado indeseado.

-GLITCH: Es un tipo de bug grafico.


