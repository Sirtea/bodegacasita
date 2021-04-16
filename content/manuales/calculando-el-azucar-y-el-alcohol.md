---
title: "Calculando el azúcar y el alcohol"
weight: 3
---

**FUENTES**: [The Home Winemaking Page][1]

Ya sabemos que hay un relación entre el azúcar y el alcohol que se vaya a generar,
siempre que no haya un problema y la fermentación pare antes; por eso hablamos del
**nivel de alcohol potencial**.

Medir el azúcar en un mosto no es posible; el densímetro nos indica la *gravedad
específica*, que es una función directa del azúcar que contiene. Visto que estos
valores están relacionados, podemos añadirlos los tres en una tabla para su fácil
consulta; esta tabla se basa en muestras tomadas:

|  SG  | % alcohol potencial | azúcar (g/L) |
|------|---------------------|--------------|
| 1010 |                 0,9 |         12,5 |
| 1015 |                 1,6 |           25 |
| 1020 |                 2,3 |           44 |
| 1025 |                 3,0 |           57 |
| 1030 |                 3,7 |           76 |
| 1035 |                 4,4 |           95 |
| 1040 |                 5,1 |          107 |
| 1045 |                 5,8 |          120 |
| 1050 |                 6,5 |          132 |
| 1055 |                 7,2 |          145 |
| 1060 |                 7,8 |        157,5 |
| 1065 |                 8,6 |          170 |
| 1070 |                 9,2 |        182,5 |
| 1075 |                 9,9 |          195 |
| 1080 |                10,6 |          208 |
| 1085 |                11,3 |          225 |
| 1090 |                12,0 |          240 |
| 1095 |                12,7 |          252 |
| 1100 |                13,4 |          265 |
| 1105 |                14,1 |          277 |
| 1110 |                14,9 |          290 |
| 1115 |                15,6 |        302,5 |
| 1120 |                16,3 |          315 |
| 1125 |                17,0 |        327,5 |
| 1130 |                17,7 |          340 |
| 1135 |                18,4 |          352 |

Alternativamente podemos aproximarlo con un simple cálculo:

* El agua tiene gravedad 1000
* Cada incremento de gravedad incrementa 2,7gr de azúcar
* Cada 19gr de azúcar genera 1% de alcohol potencial

**EJEMPLO**: Quiero generar un vino de un 6% de alcohol; tengo que tener elevar
el azúcar de 0gr (agua) a 114gr (19*6) por litro. Eso supone unos 42 (114/2,7)
incrementos en la gravedad, que partiendo de agua (gravedad 1000), resultaría
en una gravedad aproximada de 1042.

## Cuanto azúcar añado?

Supongamos que queremos un vino con un 10% de alcohol. ¿Cuánto azúcar hay que poner
para obtener el volumen de alcohol deseado? Es una pregunta que es muy fácil de
responder, ya que ambos valores están relacionados. Basta con mirar la tabla y sacar
el valor de la gravedad en algo entre 1075 y 1080, que serían unos 200g de azúcar
por litro.

El mosto ya lleva azúcares disueltos, que podemos saber de antemano, por ejemplo,
[usando el densímetro][2]. Entonces solo necesitamos saber cuanto azúcar adicional
es necesario.

**EJEMPLO**: Tenemos un mosto con una gravedad de 1040 (son 107gr de azúcar y un alcohol
potencial de 5,1%), pero queremos hacer un vino de un 12% de alcohol (gravedad 1090, o
lo que es lo mismo, 240gr de azúcar por litro). Tendríamos que añadir 133gr de azúcar
por litro. Si hacemos 5 litros, sería 133gr*5 (665gr de azúcar extra).

El densímetro no es necesario, pero si queremos ser precisos y tener una idea del azúcar
que ya tenemos, es bastante útil. En algunos casos no es necesario para saber lo que
tenemos; el agua tiene gravedad 1000 y si partimos de un zumo comercial, la información
nutricional nos aportará este valor.

**EJEMPLO**: Queremos hacer un vino de manzana con un zumo comercial de manzana, que
tiene 10,5gr de azúcar cada 100ml. Eso son 105gr de azúcar cada 1000ml (un litro).

## Cuanto alcohol hemos generado?

El alcohol final del producto no va a sorprender: o bien no hay problemas y es cercano
al calculado, o bien ha parado la fermentación y nos hemos quedado a medio camino.

La forma más fácil de salir de dudas es medir la gravedad otra vez. Con la gravedad
inicial y la final (es importante recordar estos valores!) se puede calcular el valor
real de alcohol del licor final:

> %alcohol = (SG<sub>inicial</sub> - SG<sub>final</sub>) / 7,36

**EJEMPLO**: La gravedad inicial era de 1080 y hemos acabado en 990. que resulta
en (1080-990)/7,36 = 12,23% de alcohol real. Si la gravedad final fuera de 1030,
nos habríamos quedado en (1080-1030)/7,36 = 6,79% de alcohol.

[1]: https://mpesgens.home.xs4all.nl/thwp/sugar.html
[2]: {{< relref "/manuales/como-usar-el-densimetro.md" >}}
