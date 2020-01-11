# -CIERRE_SEMESTRE_S2
# -CIERRE_SEMESTRE_S2

Ejercicio 1:  Para contar la cantidad de elementos neutro, positivo y negativos, se creo un scrip en R de la siguiente forma:
length(ejemplos[ejemplos=="positivo"])
length(ejemplos[ejemplos=="neutros"])
length(ejemplos[ejemplos=="negativo"])

Dando como resultado la cantidad de elementos que existe en cada una de estas.

Ejercicio 2: Se una set.seed para que los resultados sean replicables, al usar set.seed(10), el número 10 es nuestro argumento  con el que obtendremos los mismos resultados, dando a r studio un punto de partida en lugar de dejar que elija el suyo propio. Al contar despues del set.seed(10) da como resultado 10 elementos (entre positivos, neutros y negativos)

Ejercicio 3: Si no se consideran los neutros(20) no sería una opinión realista de las noticias sobre una crisis económica en el país debido a que este corresponde a un 30% aprox del total de noticias, informando sólo lo positivo o negativo que no muestra totalmente lo que pasa en el país.

Ejercicio 4: Acá se empieza a contar conjuntos de números designados, con la funcion IF y |, utilizando una variable "cuenta" que aumenta o disminiye en 1 unidad dependiendo de las cartas que salgan. La cuenta final es -13.

Ejercicio 5:  Al aplicar set.seed da como resultado el mismo numero de "cuenta" que es -13.Se supone, que todas las cartas tienen la misma probabilidad de salir, pero al utilizar el set.seed(31) entrega más posibilidad de salir grupo de cartas altas.
