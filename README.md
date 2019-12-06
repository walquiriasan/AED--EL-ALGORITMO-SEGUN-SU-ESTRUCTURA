# <ins>EL-ALGORITMO-SEGÚN-SU-ESTRUCTURA</ins>
Descripción de las estructuras del Algoritmo en Pseudocódigo

<img src="IMG/marco superior.jpg">

###### Imagen basada en la Imagen del autor [Manuchi][1] y obtenida en [Pixabay][2]

# Presentación    

> ## ALGORITMO NOMBRE

# Start     

> ## COMENZAR

# Stop      

> ## FIN

# Asignación  

> ## VAR <- EXP donde VAR es la variable y EXP es la expresión de la misma

# Entrada de datos     

> ## LEER variables

# Salida de datos      

> ## MOSTRAR variables

# ESTRUCTURAS DE CONTROL

Controlan el modo de ejecución del programa. Son de 3 tipos: Secuencial, Selectiva, Repetitiva.

* ## ESTRUCTURA SECUENCIAL

> ## ACCIÓN 1
> ## ACCIÓN 2
> ## . . . . 
> ## ACCIÓN N


* ## ESTRUCTURA SELECTIVA SIMPLE. Decisión 1 (IF/THEN)

> ## SI condición
> ## ENTONCES 
> ## ...accion(es)...
> ## FIN SI

* ## ESTRUCTURA SELECTIVA DOBLE. Decisión 2 (IF/THEN/ELSE)

> ## SI condición
> ## ENTONCES 
> ## ...accion(es)...
> ## SINO
> ## ...accion(es)...
> ## FIN SI

* ## ESTRUCTURA SELECTIVA DOBLE. Decisión 3 (IF-INLINE)

```C++
    CONDICIÓN ? EXPRESIÓN 1
              : EXPRESIÓN 2;
```

* ## ESTRUCTURA SELECTIVA MÚLTIPLE. Desición Múltiple (SWITCH)

> ## SEGÚN Var HACER
> ## valor1:...accion(es)1...
> ## valor2:...accion(es)2...
> ## .  .  .  .  .  .  .  .  
> ## valorN:...accion(es)N...
> ## En otros casos de valores:...accion(es)X...
> ## FIN SEGÚN
              
* ## ESTRUCTURA REPETITIVA MIENTRAS VERDADERO. Repetición 1 (WHILE)
## --> [De 0 a N indefinidas veces]

> ## MIENTRAS condición
> ## HACER ...accion(es)...
> ## FIN MIENTRAS

* ## ESTRUCTURA REPETITIVA HASTA VERDADERO. Repetición 2 (DO UNTIL)
## --> [De 1 a N indefinidas veces]

> ## REPETIR
> ## ...accion(es)...
> ## HASTA QUE condición


* ## ESTRUCTURA REPETITIVA HASTA FALSO. Repetición 3 (DO WHILE)
## --> [De 1 a N indefinidas veces]

> ## HACER
> ## ...accion(es)...
> ## HASTA QUE condición falsa

* ## ESTRUCTURA REPETITIVA DESDE. Repetición 4 (FOR)
## --> [N veces]

> ## PARA Var desde valorINI hasta valorFIN, con paso P
> ## HACER ...accion(es)...
> ## FIN PARA


[1]: https://www.instagram.com/manuchi7/

[2]: https://pixabay.com/es/illustrations/fondo-abstracto-l%C3%ADnea-ilustraci%C3%B3n-2462431/
  
