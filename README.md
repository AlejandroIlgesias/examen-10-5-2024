# ALEJANDRO IGLESIAS GONZALEZ

#FACTORIAL

Partiendo de que n es un numero natural tiene 2 opciones.Es mayor a cero o es cero.
Si es cero la funcion devuelve el valor 1.Si es mayor que cero,la funcion realiza una segunda llamada a sí misma
pasando como parámetro el número que se le pasó a la primera llamada menos 1.
Después vuelve a comprobar si dicho número es cero o distinto de cero.En caso de ser cero la funcion termina y 
devuelve el numero 1,que es devuelto por la primera llamada multiplicado  por el parametro.

Por ejemplo:Calcular el factorial de 5

La primera vez que se llama a la fucnion n es igual a 5.Como es distinto de cero
se llama una segunda vez a la función pasando como parámetro el número 4.Al ser distinto 
de cero se realiza una tercera llamada a la función con el número 3 como argumento.

Después se llama una cuarta vez a la funcion con 2 como parámetro.
Se llama una quinta vez a la función con el número 1 como parámetro y por último se llama una sexta vez a la función con el 
cero como argumento.
Así la sexta llamada devuelve el número 1,que se multiplica por el valor 2 de la quinta llamada,el resultado se multiplica por 
el valor 3 de la cuarta llamada,éste resultado por el valor 4 de la tercera llamada.Éste producto se multiplica pr el valor 5 
de la segunda llamada y por último se devuelve el resultado en la primera llamada de la fucnion.


#BUBBLE SORT

El método bubble sort se trata de un método para ordenar una serie de valores comparandolos de dos en dos.
Se empieza por el primer elemento a la izquierda del todo.Éste se compara con el elemento de su derecha.Si es
mayor se intercambian las posiciones.Si es menor se mantienen estos dos elementos en sus posiciones originales.
Después se hace lo mismo con el elemento que está a la derecha del primer elemento.Es decir,se compara con el 
elemento de su derecha ; si es mayor ,se intercambian las posiciones,sino mantienen sus posiciones.


Se sigue este procedimiento hasta terminar la serie de elementos.

El problema de este método radica en que si ,por ejemplo,el segundo elemento de la serie es mayor que 
el quinto elemento de la serie,sus posiciones no se van a intercambiar.Es decir,no se ordenan.Es el resultado 
de sólo comparar pares de elementos que están juntos.

Para ordenar por completo la lista tendría que repetirse todo el proceso desde el principio.Se haría las veces
que haga falta hasta que el orden sea el correcto.

No sólo se puede aplicar para ordenar la serie de menor a mayor,también se puede aplicar para ordenarla de
mayor a menor.Basta con cambiar la condición que obliga al algoritmo a intercambiar las posiciones de dos elementos.

Para ordenar series de elementos pequeñas se puede utilizar.Cuando el número de elementos a ordenar es grande éste método
es ineficiente comparado con otros.

Ejemplo:Ordenar la lista [34,7,23,32,5] de menor a mayor.

1)Primero se compara el 34 con el 7.Al ser 34>7 se intercambian las posiciones:

[7,34,23,32,5]

2)Ahora se vuelve a comparar el número 34 (resultado de haber intercambiado posiciones)
con el de su derecha,el 23.Como 34>23 se intercambian sus posiciones:

[7,23,34,32,5] 

3)Otra vez se vuelve a compara 34 con el de su derecha,32.Como 34>32 se intercambian posiciones:

[7,23,32,34,5]

4)Por último se vuelve a comparar 34 con el de su derecha.Como 34>5 se intercambain posicones:
[7,23,32,5,34]

Se vuelve a aplicar el algoritmo a la lista,dado que todavía no está ordenada:

1) [7,23,32,5,34]
2) [7,23,32,5,34]
3) [7,23,5,32,34]
4) [7,23,5,32,34]

El algoritmo termina.Como la lista está ordenada no hace falta volver a aplicarlo.

