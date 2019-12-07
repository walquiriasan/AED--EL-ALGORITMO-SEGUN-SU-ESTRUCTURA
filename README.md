# <ins>EL-ALGORITMO-SEGÚN-SU-ESTRUCTURA</ins>
Descripción de las estructuras del Algoritmo en Pseudocódigo

![imagen abstracta rectángular azul con líneas blancas que forman triángulos con vértices circulares blancos](IMG/marco-superior.jpg)

###### Imagen cortada del autor [Manuchi][1] y obtenida en [Pixabay][2]

&nbsp;

<details>
<summary>ÍNDICE DE CONTENIDOS</summary>
 
+ [Presentación](#Presentación)
+ [Start](#Start)
+ [Stop](#Stop)
+ [Asignación](#Asignación)
+ [Entrada de datos](#Entrada-de-datos)
+ [Salida de datos](#Salida-de-datos)
+ [Estructuras de Control](#Estructuras-de-control)
    + [Estructura Secuencial](#Estructura-Secuencial)
    + [Estructura Selectiva Simple. Decisión 1 (IF/THEN)](#Estructura-Selectiva-Simple-Decisión-1-IF//THEN)
    + [Estrucrura Selectiva Doble. Decisión 2 (IF/THEN/ELSE)](#Estructura-Selectiva-Doble-Decisión-2-IF-THEN-ELSE)
    + [Estrucrura Selectiva Doble. Decisión 3 (IF-INLINE)](#ESTRUCTURA-SELECTIVA-DOBLE-Decisión-3-IF-INLINE)
    + [Estructura Selectiva Multiple. Decisión Múltiple (SWITCH)](#ESTRUCTURA-SELECTIVA-MÚLTIPLE-Desición-Múltiple-SWITCH)
    + [Estructura Repetitiva Mientras Verdadero. Repetición 1 (WHILE)](#ESTRUCTURA-REPETITIVA-MIENTRAS-VERDADERO-Repetición-1-WHILE)
    + [Estructura Repetitiva Hasta Verdadero. Repetición 2 (DO UNTIL)](#ESTRUCTURA-REPETITIVA-HASTA-VERDADERO-Repetición-2-DO-UNTIL)
    + [Estructura Repetitiva Hasta Falso. Repetición 3 (DO WHILE)](#ESTRUCTURA-REPETITIVA-HASTA-FALSO-Repetición-3-DO-WHILE)
    + [Estructura Repetitiva Desde. Repetición 4 (FOR)](#ESTRUCTURA-REPETITIVA-DESDE-Repetición-4-FOR)
</details>

# Presentación 
```Javascript
 ALGORITMO NOMBRE
```
# Start     
```Javascript
 COMENZAR
```
# Stop      
```Javascript
 FIN
```
# Asignación  
```Javascript
 VAR <- EXP donde VAR es la variable y EXP es la expresión de la misma
```
# Entrada de datos     
```Javascript
 LEER variables
```
# Salida de datos      
```Javascript
 MOSTRAR variables
```
# ESTRUCTURAS DE CONTROL
Controlan el modo de ejecución del programa. Son de 3 tipos: `Secuencial`, `Selectiva`, `Repetitiva`.

* ## ESTRUCTURA SECUENCIAL
```Javascript
 ACCIÓN 1
 ACCIÓN 2
 . . . . 
 ACCIÓN N
```

* ## ESTRUCTURA SELECTIVA SIMPLE. Decisión 1 (IF/THEN)
```Javascript
 SI condición
 ENTONCES 
 ...accion(es)...
 FIN SI
```
* ## ESTRUCTURA SELECTIVA DOBLE. Decisión 2 (IF-THEN-ELSE)
```Javascript
 SI condición
 ENTONCES 
 ...accion(es)...
 SINO
 ...accion(es)...
 FIN SI
```
* ## ESTRUCTURA SELECTIVA DOBLE. Decisión 3 (IF-INLINE)

```Javascript
    CONDICIÓN ? EXPRESIÓN 1
              : EXPRESIÓN 2;
```

* ## ESTRUCTURA SELECTIVA MÚLTIPLE. Desición Múltiple (SWITCH)
```Javascript
 SEGÚN Var HACER
 valor1:...accion(es)1...
 valor2:...accion(es)2...
 .  .  .  .  .  .  .  .  
 valorN:...accion(es)N...
 En otros casos de valores:...accion(es)X...
 FIN SEGÚN
 ```             
* ## ESTRUCTURA REPETITIVA MIENTRAS VERDADERO. Repetición 1 (WHILE)
## --> [De 0 a N indefinidas veces]
```Javascript
 MIENTRAS haya condición verdadera
 HACER ...accion(es)...
 FIN MIENTRAS
```
* ## ESTRUCTURA REPETITIVA HASTA VERDADERO. Repetición 2 (DO UNTIL)
## --> [De 1 a N indefinidas veces]
```Javascript
 REPETIR
 ...accion(es)...
 HASTA QUE haya condición verdadera
```

* ## ESTRUCTURA REPETITIVA HASTA FALSO. Repetición 3 (DO WHILE)
## --> [De 1 a N indefinidas veces]
```Javascript
 HACER
 ...accion(es)...
 HASTA QUE haya condición falsa
```
* ## ESTRUCTURA REPETITIVA DESDE. Repetición 4 (FOR)
## --> [N veces]
```Javascript
 PARA Var desde valorINI hasta valorFIN, con paso P
 HACER ...accion(es)...
 FIN PARA
```

[1]: https://www.instagram.com/manuchi7/

[2]: https://pixabay.com/es/illustrations/fondo-abstracto-l%C3%ADnea-ilustraci%C3%B3n-2462431/
  
