---
layout: post
title:  "Guía básica de braille matemático  !"
date:   2022-08-07 #21:29:09 +0200
category: braille
---
En este post. vamos a hacer un breve repaso del código braille, y daremos unas bases de braille matemático.

Esta guía pretende ser un documento orientativo y muy general sobre el código braille, y en especial, sobre el braille matemático. Para tener una idea más precisa y detallada de las distintas representaciones sugerimos consultar referencias dedicadas a este fin.


 Además, puesto que hay diferentes versiones de código braille, es posible que la descripción hecha en este pequeño tutorial no sea del todo precisa.


## 1.- INTRODUCCIÓN

  El código braille se expresa mediante una secuencia de celdas o casillas donde se representan los caracteres del código. Estas celdas son, a su vez, un arreglo de 3x2 (3 filas por 2 columnas) o 4x2 (4filas por 2 columnas) de subcasillas que pueden o no estar activas. A cada subcasilla activa la denominamos  punto. El primer caso lo denominamos braille de 6 puntos o braille literal y en el segundo de braille de 8 puntos o braille computerizado. En este tutorial nos centraremos solamente en el braille de 6 puntos por lo que cada celda tendrá como máximo 6 puntos activos. Las subcasillas de una celda las enumeramos del 1 al 6 (o al 8, en el caso computerizado), de forma que el 1 es el punto que está en la esquina superior izquierda, el 2 el que está justo debajo, el 3 está en la esquina inferior izquierda o justo debajo del 2, el 4 está en la esquina superior derecha, el 5 justo  debajo del 3 o a la derecha del 2, y el 6 está en la esquina inferior derecha, o justo debajo del 5 y a la derecha del 3. En el braille computerizado, además tenemos el punto 7 que está justo debajo del 3 (formando la esquina inferior izquierda), y el 8 que queda justo debajo del 6 y a la derecha del 7, formando la esquina inferior derecha.
 


 La signografía braille en este tutorial  se indicará alternativamente con sus símbolos en la codificación ut-8 (braille), o mediante expresiones numéricas (código numérico)  entre corchetes  especificando los puntos que deben ir en cada celda, de manera que cuando aparezca una coma indicará que los siguientes puntos van en la próxima celda. Una celda especificada con el cero, “0”, significa una celda en blanco. Una expresión en braille irá delimitada entre corchetes (“[“ y “]”). Por ejemplo, la expresión en código numérico, 
 
 [125,135,123,1,0,1,0,2345,135,145,135,234]
 
  es la expresión 
  
  “hola a todos”
  
  , cuya expresión en braille es:

⠓⠕⠇⠁⠀⠁⠀⠞⠕⠙⠕⠎


  La escritura en braille se puede realizar en papel perforando los puntos de un arreglo de celdas  distribuidas en filas, por medio de una máquina Perkins o manualmente con punzón. También se puede escribir con el código braille en un computador con la ayuda de un periférico llamado línea braille  o teclado braille. Tanto la máquina Perkins como la línea braille disponen de una serie de teclas que corresponden a los distintos puntos de las celdas braille. Así el punto 1 se activa con la tecla que corresponde al dedo índice de la mano izquierda, el punto 2 con el corazón de la mano izquierda, el 3 con el anular izquierdo, el 7 con el meñique izquierdo, el 4 con el índice derecho, el 5 con el corazón derecho,  el 6 con el anular derecho y el 8 con el  meñique derecho. Además existe una tecla central que se activa con cualquier pulgar que sirve para generar una celda en blanco o espacio. Las combinaciones de puntos que forman un carácter braille se ejecutan simultáneamente a un tiempo. 
  
  Generalmente la cantidad de celdas que caben en una línea dependerá del tamaño del papel o del modelo particular de la línea braille. La línea braille suele tener una fila de celdas donde las subcasillas son huecos atravesados por pines que representan los puntos activos, de forma que dichos pines se activan o desactivan según se navega por el texto que se esté leyendo (refreshable braille display, en inglés). Las líneas brailles estándar suelen tener entre 14 a 80 celdas disponibles.


  También hay que tener en cuenta que el braille es distinto en cada idioma. Incluso dentro  del mismo idioma hay variaciones regionales. También existe lo que se denomina braille contraído que consiste en asignar caracteres especiales a sílabas o grupos de letras comunes en el idioma en cuestión.


  Aunque en el idioma español hay bastante consenso en el braille literal, el sistema anglosajón es el más estandarizado. Esto mismo ocurre con el braille matemático. En los países angloparlantes se usa el estándar NMET para el braille matemático. La "Comisión Española del Braille" se encarga de estandarizar el braille en español al menos dentro de España. En esta guía seguiremos algunas de las recomendaciones de dicha comisión.


## 2.- CARACTERES LATINOS Y SIGNOS COMUNES EN BRAILLE LITERAL

Las letras minúsculas del alfabeto castellano se representan  del siguiente modo:

|letra|código numérico|braille|
|-|---|-|
|a|[1]|⠁|
|-|---|-|
|b|[12]|⠃|
|-|---|-|
|c|[14]|⠉|
|-|---|-|
|d|[145]|⠙|
|-|---|-|
|e|[15]|⠑|
|-|---|-|
|f|[124]|⠋|
|-|---|-|
|g|[1245]|⠛|
|-|---|-|
|h|[125]|⠓|
|-|---|-|
|i|[24]|⠊|
|-|---|-|
|j|[245]|⠚|
|-|---|-|
|k|[13]|⠅|
|-|---|-|
|l|[123]|⠇|
|-|---|-|
|m|[134]|⠍|
|-|---|-|
|n|[1345]|⠝|
|-|---|-|
|ñ|[12456]|⠻|
|-|---|-|
|o|[135]|⠕|
|-|---|-|
|p|[1234]|⠏|
|-|---|-|
|q|[12345]|⠟|
|-|---|-|
|r|[1235]|⠗|
|-|---|-|
|s|[234]|⠎|
|-|---|-|
|t|[2345]|⠞|
|-|---|-|
|u|[136]|⠥|
|-|---|-|
|v|[1236]|⠧|
|-|---|-|
|w|[2456]|⠺|
|-|---|-|
|x|[1346]|⠭|
|-|---|-|
|y|[13456]|⠽|
|-|---|-|
|z|[1356]|⠵|
|-|---|-|

Notar que la secuencia de la "a" hasta la "j" se repite desde la "k" hasta la "t" (exceptuando la "ñ") añadiendo el punto "3", y luego desde la "u" hasta la "z" (exceptuando la "w") añadiendo los puntos 3 y 6.

 Las vocales acentuadas (con acento agudo), y la u con diéresis son:

|letra|código numérico|braille|
|-|---|-|
|á|[12356]|⠷|
|-|---|-|
|é|[2346]|⠮|
|-|---|-|
|í|[34]|⠌|
|-|---|-|
|ó|[346]|⠬|
|-|---|-|
|ú|[23456]|⠾|
|-|---|-|
|ü|[1256]|⠳|
|-|---|-|

Para escribir las mayúsculas debemos anteponer al código de la letra el símbolo [46], ⠨, es decir, [46,1], ⠨⠁, corresponde a la "A". 

Los dígitos del 1 al 9 y el 0 se escriben con las letras "a" a la "i" y "j", respectivamente, anteponiendo el símbolo "numerador", [3456], ⠼. Así [3456,15], ⠼⠑, corresponde al "5", etc. 

Cuando escribimos un número de varias cifras podemos anteponer el símbolo numerador a cada cifra  o bien sólo anteponerlo al primer dígito desde la izquierda, por ejemplo, [3456,1,245,14], ⠼⠁⠚⠉, corresponde al número "103".


 Cuando se escriben cifras seguidas  de letras de la "a" hasta la "j" se suele escribir el punto [5], ⠐, para indicar que lo que viene es una letra y no su cifra correspondiente. Por ejemplo, [3456,1,14,5,125,3456,1245,1346], ⠼⠁⠉⠐⠓⠼⠛⠭, significa "13h7x".


   Otros símbolos ortográficos son:


|signo|código numérico|braille|
|-|-|-|
|.|[3]|⠄|
|-|-|-|
|,|[2]|⠂|
|-|-|-|
|;|[23]|⠆|
|-|-|-|
|\:|[25]|⠒|
|-|-|-|
|¿ ó ?|[26]|⠢|
|-|-|-|
|¡ ó !|[235]|⠖|
|-|-|-|
|"|[236]|⠦|
|-|-|-|
|'|[3]|⠄|
|-|-|-|
|˜|[256]|⠲|
|-|-|-|
|…|[3,3,3]|⠄⠄⠄|
|-|-|-|
|(|[126]|⠣|
|-|-|-|
|)|[345]|⠜|
|-|-|-|
|[|[12356]|⠷|
|-|-|-|
|]|[23456]|⠾|
|-|-|-|
|{|[5,123]|⠐⠇|
|-|-|-|
|}|[456,2]|⠸⠂|
|-|-|-|
|\-|[36]|⠤|
|-|-|-|
|\+|[235]|⠖|
|-|-|-|
|❌|[236]|⠦|
|-|-|-|
|\*|[35]|⠔|
|-|-|-|
|/|[6,2]|⠠⠂|
|-|-|-|
|\ |[5,3]|⠐⠄|
|-|-|-|
|=|[2356]|⠶|
|-|-|-|
|%|[456,356]|⠸⠴|
|-|-|-|
|@|[5]|⠐|
|-|-|-|

## 3.- BRAILLE MATEMÁTICO BASICO

#### EXPRESIONES ALGEBRAICAS SIMPLES
Dado que los números en braille se componen del signo “numerador” (puntos [3456], ⠼) seguido de las letras de la “a” a la “j” para representar los números del 1 al 0 respectivamente, en los casos en que a continuación de un número vaya una letra minúscula del alfabeto latino, es necesario distinguir ésta con el punto [5], ⠐, siempre y cuando sean letras que den lugar a confusiones. Por ejemplo, para escribir “5x” no será necesario incluir el punto [5], ⠐, antes de la “x”, ya que ésta en sí no representa ningún número en braille. Sin embargo, en los casos en que la letra que suceda al número sea alguna de la “a” a la “j”, sí se hará necesario preceder la letra por el punto [5], ⠐. Por ejemplo, para representar 

“10n=20c”,

 escribimos en código numérico: 

[3456,1,245,1345,2356,3456,12,245,5,13], 

que en braille luce,

⠼⠁⠚⠝⠶⠼⠃⠚⠐⠅

Los puntos [2356], ⠶, corresponden al signo = (igual).


###### Potencias 
Para expresar potencias usamos los puntos [16], ⠡, así

⠭⠡⠼⠃ 

representa “x al cuadrado”.
 
###### Raíces cuadradas simples

Las raíces cuadradas se expresan por la combinación de dos celdas [1246,156], ⠫⠱, así escribimos:

“raíz cuadrada de 9”

 escribimos los puntos en código numérico, 
 
 [1246,156,3456,24],

y en braille,

⠫⠱⠼⠊

La expresión en braille,

⠫⠱⠼⠊⠶⠼⠉

expresa la igualdad de la raíz cuadrada de nueve y tres.

  

###### Subíndices y superíndices
Para escribir subíndices escribimos los puntos [34], ⠌, y a continuación el subíndice. Así 
para representar 

“z sub n”,
 
 escribimos en código numérico: 
 [1356,34,1345]
 
 y en braille,
 
 ⠵⠌⠝


Los superíndices se escriben igual que las potencias, ya que al igual que sucede en la escritura en tinta, la simbología de una u otra expresión no se distingue, aunque su significado sea distinto. Corresponde al lector discernir si se refiere a un significado u otro. 

Así para representar 

“x súper  0”,

 escribimos en código numérico:
 
  [1346,16,3456,245],
  
  y en braille,
  
⠭⠡⠼⠚
  



###### Fracciones simples

  Para expresar fracciones simples se usa los puntos [256], ⠲, así la fracción “5/2” se expresa en braille como:

⠼⠑⠲⠼⠃

Otro ejemplo,

"x dividido por 9”,

en código numérico escribimos:

 [1346,256,3456,24],
 
 y en braille,

⠭⠲⠼⠊


#### EXPRESIONES COMPLEJAS

Puesto que el braille es un código de escritura lineal, a diferencia de la escritura en tinta, no existe la posibilidad de escribir en diferentes niveles (arriba o abajo con respecto a una línea base), ni más pequeño o más grande, por lo que estas características deben indicarse con signos adicionales que se anteponen a las letras o números. 

En el ámbito específico de las fórmulas matemáticas lo escrito en tinta adquiere significado según su posición, tamaño o distribución. En cambio, , , en braille existen los paréntesis auxiliares los cuales se usan para agrupar términos e indicar así su significado específico en la formula. Estos no tienen equivalente en la escritura en tinta, constituyen un recurso solo para la escritura de fórmulas matemáticas en braille.


##### PARÉNTESIS AUXILIARES

Los puntos para abrir paréntesis auxiliares son los puntos [26], ⠢, y para cerrar [35],  ⠔. Éstos se usan en casos como fracciones, raíces, exponentes (o superíndices) y subíndices compuestos. 

Nótese que lo anterior se representa en tinta a partir del tamaño o posición, de manera que, por ejemplo, para escribir una fracción compuesta basta con escribir el numerador “2x+3”, debajo de Èl una línea horizontal que lo abarca completamente la cual indica “partido por” y posteriormente, debajo de esa línea, el denominador (por ejemplo “x+2”. En braille, en cambio, debemos escribir entre paréntesis auxiliares el numerador, a continuación el signo “partido por” (puntos [256], ⠲) y luego el denominador también entre paréntesis auxiliares. De no ponerse numerador y denominador entre paréntesis auxiliares, la fórmula escrita podría ser interpretada de manera incorrecta. Por ejemplo, si en tinta el signo “partido por” en lugar de ser una línea que abarca completamente numerador y denominador --de manera que queda claro qué está arriba y qué está abajo, no quedaría claro en nuestro ejemplo si a “2x” le sumamos la fracción “3/x” y luego le sumamos “2”, o si a “2x” se le suma la fracción “3/(x+2)”, o si el “2x+3”  es dividido solo por la “x” y a esto se le suma “2”. Pues bien, esto es lo que sucede en la escritura en braille, ya que el signo “partido por” se escribe en una celda.
En nuestro caso, la expresión,

"comienza fracción, 2 x + 3, sobre, x +2, fin de fracción"

se escribiría en código numérico como,

[26,3456,12,1346,235,3456,14,35,256,26,1246,235,3456,12,35]

y en braille queda,

⠢⠼⠃⠭⠖⠼⠉⠔⠲⠢⠫⠖⠼⠃⠔



De manera similar sucede con las raíces compuestas. En tinta se escribe dentro del radical todo aquello a lo que se le quiere sacar raíz. En braille se deben escribir los puntos [1246, 156], ⠫⠱, para indicar raíz cuadrada, a continuación abrir paréntesis auxiliares, escribir el radicando y posteriormente cerrar paréntesis auxiliares. Por ejemplo, para escribir la expresión,

"comienza raíz cuadrada de, “5x+2, fin de raíz cuadrada”,

 escribimos  en código numérico,

[1246,156,26,3456,1245,1346,235,3456,12,35]. 

y en braille queda como,

⠫⠱⠢⠼⠛⠭⠖⠼⠃⠔


Para escribir subíndices escribimos los puntos [34], ⠌, y a continuación el subíndice. En caso de que éste sea compuesto, debemos escribirlo en paréntesis auxiliares. Por ejemplo, para representar “z” con subíndice “n-1”, escribimos: 

⠵⠌⠢⠝⠤⠼⠁⠔

De manera análoga sucede con los exponentes o superíndices. El signo “elevado a” se representa con los puntos [16], ⠡. Cuando el exponente es compuesto utilizamos paréntesis auxiliares. Por ejemplo, para representar “x” elevado al exponente “n+1”, escribimos:
⠭⠡⠢⠝⠖⠼⠁⠔

Resumimos algunos símbolos matemáticos útiles nombrados aquí en la siguiente tabla:

|operación|código numérico|braille|
|-|-|-|
operador numerador|[3456]|⠼|
|-|-|-|
|comienzo de letras|[5]|⠐|
|-|-|-|
|\+|[235]|⠖|
|-|-|-|
|\-|[36]|⠤|
|-|-|-|
|❌|[236]|⠦|
|-|-|-|
|=|[2356]|⠶|
|-|-|-|
|potencia/superíndice|[16]|⠡|
|-|-|-|
|raíz cuadrada|[1246,156]|⠫⠱|
|-|-|-|
|subíndice|[34]|⠌|
|-|-|-|
|fracciones|[256]|⠲|
|-|-|-|
|abrir paréntesis auxiliar|[26]|⠢|
|-|-|-|
|cerrar paréntesis auxiliar|[35]|⠔|
|-|-|-|




