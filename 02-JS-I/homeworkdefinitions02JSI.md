HOMEWORK DEFINICIONES EXPLICACION DE CONCEPTOS

* Variables:

Una variable tiene un nombre y contiene un valor.
Podemos imaginar que una variable como si fuera una caja. A esta caja le ponemos una equiqueta que se llama Biblioteca,
 y colocó un libro en su interior, en términos de programación, Biblioteca es el nombre de la variable y el nombre de ella es el valor.
Una variable puede almacenar un solo tipo de valor.
Por lo general estos son números, fracciones o frases. El tipo de valor que puede contener una variable también se denomina tipo de datos.

  Ejemplos:         var nombre = " BIblioteca Nacional ";
                    let seccion = " lengua española "
                    const librofavorito = "Quijote"

* Strings:

Es  una variable usada para representar texto. Las cadenas contienen grupos de caracteres, como una palabra o una frase.
Las “strings” son bloques de texto, siempre se definirán entre comillas, ya sea simple o doble.
Cualquier texto entre comillas es una cadena o string. Piensa en una persona o en un animal como una variable.
El nombre es simplemente un valor que se usa para identificar a esa persona o animal.

Ejemplo:       var nombrePerro = " Pelusa ";
               var edadPerro = "15"


* Funciones (argumentos, `return`)

Las funciones son una parte muy importante de todo lenguaje de programacion y sobre todo en JavaScript.
Son objetos invocables, con las mismas propiedades que cualquier objeto. Las funciones nos permiten calcular, 
cambiar o hacer algo con estos objetos.
Argumentos:  son las variables que necesitan las funciones para funcionar.
La función debe indicar cuántos argumentos necesita y cuál es el nombre de cada argumento .
Los argumentos se indican dentro de los paréntesis que van detrás del nombre de la función y se separan con una coma (,).
Una vez que podemos ejecutar una funcion basica podemos integrarle los argumentos.


Ejemplo funcion basica:
                            function logsaludo() {
                                console.log("Buenos Dias");
                            }

                            logsaludo('Pedro');
                            Buenos Dias

Ejemplo integrando mas argumentos:  
                            function logsaludo(nombre) {
                                console.log("Buenos dias, " + nombre);
                            }

                            logsaludo('Pedro');
                            Buenos dias, Pedro

Return: 

Las funciones pueden devolvernos algo es decir que podemos utirlizar el termino   - return-  por ejemplo en la suma de dos numeros.
El retorno seria la suma. Para conseguir que la funcion nos retorne algo ya no debemos utilizar – console.log – 
debido a que este comando no nos permite el acceso a su contenido desde fuera de la funcion, esto se llama scope (alcance).
La única forma de acceder a algo dentro de la función es devolverlo.
También podemos establecer variables para igualar lo que devuelve una función.

Ejemplos:
                            function multiplicarDosNumeros(a, b) {
                                var producto = a * b;
                                return producto;
                            }

                            multiplicarDosNumeros(6, 3); // 18
                            console.log(producto); // undefined


                            var diferenciaDeResta = restarDosNumeros(10, 9);
                            console.log(diferenciaDeResta); // 1
                            console.log(diferencia); // undefined



* Declaraciones `if`:

Es un operador de control de flujo que nos permite verificar si algo es verdadero (true).
Al ejecutar el codigo suministrado nos dira si es true y sino (false) seguira avanzando.

Ejemplo: 

                            function puedeIngresar(edad) {
                            if (edad > 18) {
                            return true;
                            }

                            return false;
                            }

                            puedeIngresar(32); // true



* Valores booleanos (`true`, `false`)

Los Boleanos son valores Verdaderos o Falsos. Estos son true o false. 
Se utilizan para probar una condicion, y se ejecuta el codigo segun corresponda.

Eejmplo: 

            var numeroMayorQueOtro = 6 < 3;
            undefined
            numeroMayorQueOtro
            false
            var numeroMayorQueOtro = 6 > 3;
            undefined
            numeroMayorQueOtro
            true
​
