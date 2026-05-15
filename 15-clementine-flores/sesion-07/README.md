# sesión 07 - 15/05
## Los loop son infinitos?
Definción - Bucle: Informática _> Serie de instrucciones que se repiten indefinidamwente mientras no  se cumpla una condicion oreviamente establecida
Loop_> Estructura de control que permite ejecutar un bloque de instrucciones de manera repetida mientras se cumpla una condicion especifica o hasta que se alcance un estado determinado.
While 3 elementos -> los bucles while son útiles para repetir isntrucciones mientras una codnicion sea verdadra. son vomo sentencias if que se repite

##FOR (4 ELEMENTOS)
Una forma de repetir un bloque de código cuando se conoce el número
de iteraciones. Los bucles `for` son útiles para repetir instrucciones un
número determinado de veces.
Son una especie de SHORTCUT para hacer loops y siempre tienen 4
elementos:

1. Inicialización de una variable
2. Condición booleana (V-F)
3. Actualización ( Incrementación o decrementación)
4. Lo que queremos que pasé cuando la condición sea TRUE

5. for (inicialización variable; condición booleana; actualización){
Lo que queremos que pase cuando la condición sea verdadera
}

for (let x=0 ; x <= width; x=x+1) {
ellipse (x , 200, random(300))

}
