"hola mundo"
para poder crear nuestro documento de "php" es necesario activar los servicios que "xamp" nos ofrece al instalarlo.

![[Pasted image 20230827173646.png]]
luego de ello se procederá a crear en el documento htdocs ubicada en el disco local, para luego generar una carpeta llamado "php-basico" 
![[Pasted image 20230827174529.png]]
vamos a abrir la carpeta en nuestro editor, en este caso *"Visual Studio Code"* y pasaremos a crear un documento al cual llamaremos *"index.php"* 
![[Pasted image 20230827175745.png]]
luego generamos una estrcutura basica de hmtl
![[Pasted image 20230827185759.png]]
dentro de esta generamos un tag de php *"<?php ?>"* . todo lo que escribamos dentro del tag de php es codigo interpretado por php
podemos mostrar de diferente manera un hola mundo con los tag de php *echo* y *print* 
![[Pasted image 20230827190342.png]]
##variables.
Para generar variables en php tienen que declarar al inicio con el signo de *"$"* aparte si ocupamos la variable de  *"var_dump()"* para saber el tipo de dato, ademas php toma los datos por inferencia 
###Reglas.
algunas reglas para nombrar variables de php los cuales son los siguientes.
- usar unicamente caracteres latinos **(0-9, a-z, A-Z, ) y guion bajo.** 
- No utilizar caracteres especiales.
- *SE PUEDE UTILIZAR EL GUION BAJO AL COMIENZO DEL NOMBRE DE UNA VARIABLE*
- Nombrar las variables con significado semantico.
- Tener en cuenta que se distinguen entre nombres con mayusculas y minusculas Ej : "apellidoMaterno" no es igual a "apellidomaterno"
- *evitar palabras reservadas.* 
![[Pasted image 20230827192031.png]]

##Constantes
La definicion de constante se hace con la funcion de *"define()"* como primer parametro el nombre de la constante y como segundo su valor, *estas constantes pueden ser de cualquier tipo de dato* 

Para imprimir varibles y contantes usamos la concatenacion.
![[Pasted image 20230827193434.png]]

##Opercaiones aritmeticas
las operaciones en php no son distintas a otro lenguaje siendo estas las siguientes.
![[Pasted image 20230827193550.png]]
##Operadores Logicos.
son los siguientes:

| Nombre | Símbolo  |
| ------ | -------- |
| And    | && o And |
| Or     | Or I     | 
| Not    | !        |

##operadores de comparacion.

| Ejemplo        | Nombre            |
| -------------- | ----------------- |
| $a == $b       | igual             |
| $a=== $b       | idéntico          |
| $a != $b       | Diferente         |
| $a !== $b      | No idéntico       |
| $a <> $b       | Diferente         |
| $a < $b        | Menor que         |
| $a  > $b       | Mayor que         |
| $a <= $b       | Menor o igual que |
| $a >= $b       | Mayor o igual que |
| $a <=> $b      | Nave espacial     |
| $a ?? $b ?? $c | Fusión de null    |

##IF / IF-ELSE

nos permitira preguntar si....y comparar dos o mas varibles y si la condicion se cumple o no se ejecutara lo que el programador requiera.
![[Pasted image 20230827194948.png]]
##switch
es una estrcutura de control que nos ayudara a evaluar dependiendo de los casos (case), ejecutandose el "case" correspondiente de esa solucion, en caso de que ninguno de los casos sea correcto se mandara un "default" para advertir que no hubo caso correcto.
![[Pasted image 20230827195436.png]]
##while 
es una estrcutura de controlque permite crear un bucle, ejecutandose lo interior de la estructura de control las veces que se genere el bucle.
algo a resaltar es que "while" primero *evalua* y luego *ejecuta*![[Pasted image 20230827195926.png]]
## Do-while
ejecutandose una primera vez para luego iniciar la comparacion para observar si la condicion se cumple.
![[Pasted image 20230827200304.png]]
##Arreglos 
son una collecion de datos, pueden ser numericos, booleanos, cadenas  pudiendo ser combinados sin algun problema
Ej.
![[Pasted image 20230827200713.png]]
##Objetos
Los objetos en php existen cuando son instancias de clase. Tambien llamados *"Arreglos Asociativos"*
###Arreglos Asociativos
Se conforman por una "clave" tambien llamado "valor". Para acceder a un valor del arreglo es necesario mediante sus llaves o claves.
![[Pasted image 20230827201902.png]]
##For
Nos permite hacer bucles y ejecutar el boque de codigo que contiene, ademas de permitir recorrer arreglos mas sencillo, hasta que la condicion se deje de cumplir.
![[Pasted image 20230827202257.png]]
##Foreach

Es una estructura de bucle para lograr recorrer arreglos de manera un poco mas sintetizada.
![[Pasted image 20230830155751.png]]
##Funciones 
declarándose con la  palabra *"Function"* a la par del nombre de mi función, puede o no llevar parámetros de invocación, Y estas deben resolver una única tarea.
![[Pasted image 20230830160306.png]]
##Clases

una clase se puede tener atributos, funciones o métodos y llevan un método constructor y lo que se hara referencia.
![[Pasted image 20230830160803.png]]
##Encapsulacion

	**Consiste en agrupar una líneas de código fuertemente relacionadas, darles un nombre y encapsularlas en un método o una clase**

##Funciones estaticas.

En el contexto de clases y objetos **la palabra reservada static permite definir métodos y propiedades estáticos** (lo que no tiene que ver con el concepto de variables estáticas).

