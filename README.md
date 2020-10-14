# MCOC2020-P2-G6-E4

#### Output del ejemplo 4:

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/reticulado.png?raw=true)

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/Tensiones%20caso%201.png?raw=true)

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/Tension%20caso%202.png?raw=true)

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/Fu%20caso%201.png?raw=true)

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/FU%20caso%202.png?raw=true)

Peso :

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/Peso.JPG?raw=true)

Como se puede ver el reticulado se debe resideñar segun el caso 2 debido a que al reisar las combinaciones se ven cargas de mayor absoluto en el caso escogido que en el caso 1.



#### Escoja 5 barras interesantes del reticulado (identificadas por sus nodos) y manualmente realice el rediseño, buscando minimizar el peso de la barra y cumplir con FU < 1, pero cerca a 1.0 comparando con los resultados de su programa. 

#### Explique en detalle su función de rediseño de cada barra. Si existen supuestos importantes, declarelos ahora. 
 * En primer lugar, el objetivo de la función de rediseño de cada barra,  fue calcular el valor más optimo para el radio y espesor, logrando así, que el F.U tienda a 1.
  * En segundo lugar, el supuesto más importante que se realizo fue que F.U debe ser menor o igual a 1. Con esto se aseguró que el puente, fuese una estructura segura y por lo tanto se encuentre dentro de los rangos óptimos de diseño. 
  * Cabe destacar, que a pesar de que las barras a rediseñar fueron previamente escogidas, se tiene toda la libertar que ver que hacer con la fuerza, es decir, utilizar las combinaciones de carga a elección del consumidor. 
  * Lo que realizó la función rediseñar en nuestro caso, fue encontrar un coeficiente(variable según el tipo de problema), el cual se amplificó por el radio y el espesor para así llegar al diseño estructural optimo del puente. 
  * Finalmente, la importancia de la función rediseñar es imprescindible para el problema, ya que de esta depende que los valores de los parámetros tengan sentido.
  
#### Mostrar los nuevos factores de utilización, fuerzas en las barras y deformada para cada combinación de carga. Para esto, Graficando todo lo pedido y explicando sus criterios de rediseño. 
Al rediseñar se obtiene el peso: 

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/Peso%20redise%C3%B1o%20funcion.JPG?raw=true)

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/Tensiones%20Redise%C3%B1o%20caso%202.png?raw=true)

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/FU%20redise%C3%B1o%20caso%202.png?raw=true)

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/Deformada%20redise%C3%B1o.png?raw=true)


#### ¿Cual es el desplazamiento vertical máximo en los nodos del tablero del reticulado antes y después de los cambios?

Antes de los cambios:

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/Desplazamiento%20antes.JPG?raw=true)

Despues de los cambios:

![alt text](https://github.com/FelipeAravenaR98/MCOC2020-P2-G6-E4/blob/main/Desplazamientos%20nodos%20redise%C3%B1o%20funcion.JPG?raw=true)

Distancias en metros.

#### Comente respecto de la nueva distribución de FU del reticulado y el peso del mismo. ¿Que cambios globales se pueden hacer para mejorar aún más el costo (peso del acero) del mismo? 
