1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* `for`
Crea un bucle que consiste en tres expresiones opcionales, encerradas en paréntesis y separadas por puntos y comas, seguidas de una sentencia ejecutada en un bucle (repetir varias veces una accion).
Un for en programación se usa cuando queremos repetir un conjunto de instrucciones un número finito de veces.

Ejemplo: 
            for (var i = 0; i < 9; i++) {
                n += i;
                mifuncion(n);
            }


* `&&`
Este operador se entiende como si fuera un "y". 
Es decir, en la condición de la sentencia IF, se puede añadir este operador para que en vez de una sola condición, se cumplan 2 o más condiciones.

`||`
Este es un operador lógico OR (o) para un conjunto de operandos es verdadero si y solo si uno o más de sus operandos es verdadero. Normalmente se utiliza con valores Boleanos y, devuelve un valor booleano. 
Sin embargo, el ||operador realmente devuelve el valor de uno de los operandos especificados, por lo que si este operador se usa con valores no booleanos, devolverá un valor no booleano.


Ejemplo: 
            function operadoresLogicos(num1, num2, num3) {
                if(num1 < 0 || num2 < 0 || num3 < 0) {
                    return "Hay negativos";
                }
                else if(num1 === 0 || num2 === 0 || num3 === 0) {
                    return "Error";
                }
                else if(num1 > 0 && num1 > num2 && num1 > num3) {
                    return "Número 1 es mayor y positivo";
                }
                else if(num3 > num1 && num3 > num2) {
                    return num3 + 1;
                }
                else {
                    return false;
                }
                }


 `!`
Es operador lógico es el operador "NOT" ("NO"). Se escribe como un solo signo de exclamación (!). 
Este devolvera el valor booleano opuesto de lo que se le pasa.

Ejemplo:

        if (!(1 === 1)) {
            console.log('1 es igual a 1, de modo que la expresión devuelve true. El operador ! devolverá lo contrario de eso, por lo que este código NO se ejecutará');
        }