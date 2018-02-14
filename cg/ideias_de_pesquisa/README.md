# Coordenadas homogêneas

Em geometria computacional, é utilizado em lugar do sistema de coordenadas cartesiano devido às vantagens que oferece no tratamento algébrico de pontos "no infinito".

## Definição

Por definição, um ponto representado por ( X , Y ) no sistema de coordenadas cartesiano é representado, em coordenadas homogêneas, por [_**x,y,w**_], onde X = x/ w e Y = y/ w.

Deste modo, o ponto cartesiano ( X , Y ) corresponde à uma infinidade de triplas [wX,wY,w], incluindo o caso particular de [x,y,1]. O valor w é chamado de peso.

Este sistema permite representar pontos no infinito (ou direções), chamados (em geometria projetiva) de pontos impróprios, ao usar w = 0 e x ≠ 0 ou y ≠ 0. Por exemplo, o ponto impróprio que representa o feixe de retas paralelas ao eixo x tem coordenadas homogêneas [ 0 , x , 0 ].


![](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5d/Projection_azimutale_gnomonique.jpg/300px-Projection_azimutale_gnomonique.jpg)

Os pontos de cada recta têm as mesmas coordenadas homogéneas.

Em matemática, coordenadas homogêneas ou coordenadas projetivas, introduzidas por agosto Ferdinand Möbius em seu trabalho de 1827 Der Barycentrische Calcül, são um sistema de coordenadas usado na geometria projetiva, pois as coordenadas cartesianas são usadas na geometria euclidiana. Eles têm a vantagem de que as coordenadas de pontos, incluindo pontos no infinito, podem ser representadas usando coordenadas finitas. As fórmulas que envolvem coordenadas homogêneas são muitas vezes mais simples e mais simétricas do que suas contrapartes cartesianas. As coordenadas homogêneas possuem uma gama de aplicações, incluindo gráficos computacionais e visão computacional 3D, onde permitem transformações afins e, em geral, transformações projetadas para serem facilmente representadas por uma matriz.

Se as coordenadas homogêneas de um ponto forem multiplicadas por um escalar não nulo, as coordenadas resultantes representam o mesmo ponto. Uma vez que as coordenadas homogêneas também são dadas aos pontos no infinito, o número de coordenadas necessárias para permitir essa extensão é mais do que a dimensão do espaço projetivo que está sendo considerado. Por exemplo, são necessárias duas coordenadas homogêneas para especificar um ponto na linha projetiva e três coordenadas homogêneas são necessárias para especificar um ponto no plano projetivo.

As coordenadas homogêneas (x1, x2, x3) de um ponto finito (x, y) no plano são três números para os quais:

![](http://mathworld.wolfram.com/images/equations/HomogeneousCoordinates/NumberedEquation1.gif)

Coordenadas (x1, x2,0) para as quais

![](http://mathworld.wolfram.com/images/equations/HomogeneousCoordinates/NumberedEquation3.gif)

descreva o ponto no infinito na direção da inclinação lambda.

Em coordenadas homogêneas, a equação de uma linha

![](http://mathworld.wolfram.com/images/equations/HomogeneousCoordinates/NumberedEquation4.gif)

É dado por

![](http://mathworld.wolfram.com/images/equations/HomogeneousCoordinates/NumberedEquation5.gif)

Dois pontos expressos usando coordenadas homogêneas (a_1, a_2, a_3) e (b_1, b_2, b_3) são idênticos iff

![](http://mathworld.wolfram.com/images/equations/HomogeneousCoordinates/NumberedEquation6.gif)

Duas linhas expressas usando coordenadas homogêneas

![](http://mathworld.wolfram.com/images/equations/HomogeneousCoordinates/NumberedEquation7.gif)

são idênticos se

![](http://mathworld.wolfram.com/images/equations/HomogeneousCoordinates/NumberedEquation9.gif)



