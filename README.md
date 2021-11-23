# Informe-laboratorio-2

# 1. OBJETIVOS
**-General**

Demostrar el conocimiento adquirido en clases sobre los metedos de mallas, ley de ohm y leyes de Kirchhoff atraves del circuito planteado en la guia para mejorar el aprendizaje de estos circuitos.

**-Especificos**

   1.Construir un circuito eléctrico con la herramienta Tinkercad

   2.Relacionar los metodos de mallas con las leyes de kirchhoff y ley de ohm

   3.Comparar los resultados obtenidos con los valores calculados.


# 2. MARCO TEÓRICO

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/IMGBV/01.png)

# 3. EXPLICACIÓN DEL PROCEDIMIENTO

**MATERIALES UTILIZADOS**

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/IMGBV/3.png)

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/IMGBV/5.png)

Lo que haremos para resolver este circuito es:

1. Trazaremos las trayectorias y los signos de los componentes para guiarnos de mejor manera

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/1.png)

Despues pondremos todas las resistencias a una sola unidad

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/2.png)


**TRAYECTORIA 1**


En la trayectoria uno se encuentran los siguientes elementos

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/2.1.png)

En este caso tomaremos a la trayectoria I1 como principal y la I2 como secuendaria por que exite una resistencia en el medio de estas dos por lo cual restaremosa la principal menos la secuandaria y luego la multiplicaremos por la resistencia para asi obtener el voltaje.


![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/2.2.png)

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/2.3.png)

Y con esto obtendremos la primera ecuación


![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/2.4.png)

**TRAYECTORIA 2**

En la trayectoria dos se encuentran los siguientes elementos

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/3.1.png)

En este caso tomaremos a la trayectoria I2 como principal y la I3 como secuendaria por que exite una resistencia en el medio de estas dos, ademas tiene otra resistencia entrelazada en este caso sera la I2 la principal menos I1 que es la secundaria  y luego la multiplicaremos por la resistencia para asi obtener el voltaje


![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/3.2.png)

Y asi obtenemos la segunda  ecuación 


![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/3.3.png)


En la trayectoria tres se encuentran los siguientes elementos


![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/4.1.png)


En este caso tomaremos a la trayectoria I3 como principal y la I2 como secuendaria por que exite una resistencia en el medio de estas dos por lo cual restaremosa la principal menos la secuandaria y luego la multiplicaremos por la resistencia para asi obtener el voltaje.


![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/4.2.png)


Y con esto obtendremos la tercera ecuación


![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/4.3.png)



Con estas ecuaciones, las ubicaremos en una aplicación para calcular los sistemas de ecuaciones


![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/5.png)

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/6.png)

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/7.png)

Obteniendo los siguientes resultados


![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/8.png)

y por ultimo transformaremos a una misma unidad.

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Imagenes%20BN/9.png)

**SIMULACIÓN EN PROTEUS**

**Circuito armado**

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/IMGBV/1.png)

**Toma de medidas en cada malla**

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/IMGBV/2.png)

**SIMULACIÓN EN TINKERCAD**

**Circuito armado**

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Img/lab2_5.JPG)

**Toma de medidas en cada malla**

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Img/lab2_7.JPG)

**TABLA DE DATOS**

| MALLA | RESULTADOS ANALÍTICOS | RESULTADOS EXPERIMENTALES| RESULTADOS SIMULADOS |
| ------------- | ------------- | ------------- | ------------- |
| 1 | 11.5 mA | 11.5 mA | 11.5 mA |
| 2 | 2.85 mA | 2.85 mA | 2.85 mA |
| 3 | 0.49 mA | 0.488 mA | 0.49 mA |


# 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Los resultados analíticos, experimentales y simulados son practicamente iguales, debido a que los programas utilizados no toman en cuenta condiciones reales o las tolerancias de las resistencias. Por tanto estaría trabajando como un sistema ideal.
 
 **Cálculos del porcentaje de error**

Para calcular el porcentaje de error de los valores obtenidos se utiliza la siguiente formula:

![](https://github.com/bonacimba/Informe-laboratorio-2/blob/main/IMGBV/4.png)

| MALLA | RESULTADOS ANALÍTICOS | RESULTADOS EXPERIMENTALES| % ERROR|
| ------------- | ------------- | ------------- | ------------- |
| 1 | 11.5 mA | 11.5 mA | 0 % |
| 2 | 2.85 mA | 2.85 mA | 0 % |
| 3 | 0.49 mA | 0.488 mA | 0.41 % |

!()[https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Img/lab2_8.JPG]

| MALLA | RESULTADOS ANALÍTICOS | RESULTADOS SIMULADOS| % ERROR |
| ------------- | ------------- | ------------- | ------------- |
| 1 | 11.5 mA | 11.5 mA | 0 % |
| 2 | 2.85 mA | 2.85 mA | 0 % |
| 3 | 0.49 mA | 0.49 mA | 0 % |

!()[https://github.com/bonacimba/Informe-laboratorio-2/blob/main/Img/lab2_9.JPG]

Como se observa el porcentaje de error es practicamente de 0% devido a lo ya antes mencionado.

# 5. VIDEO

# 6. CONCLUSIONES

Los simuladores tanto como proteus y Tinkercad nos ayudaron a relacionar y practicar todo lo dicho anteriormente por que al usarlos asimilamos la teoria de las leyes y componentes del cicuito

Gracias a toda la informacion reunida anteriormete, podemos interpretar que podemos utilizar diferentes metodos y llegar a la misma solucion.


Tal y como hemos podido comprobar los valores analizados y calculados por nosotros mismos en este circuito son identicos a los valores medidos en el simullador y en el Tinkercad, pero con su debido error de calculo pero este es minimo.

# 7. BIBLIOGRAFÍA

Capítulo 21: Análisis de Mallas. (2019, 8 abril). Análisis de Circuitos En Ingeniería. Recuperado 22 de noviembre de 2021, de https://analisisdecircuitos1.wordpress.com/parte-1-circuitos-resistivos-cap-21-a-30-en-construccion/capitulo-21-analisis-de-mallas/

colaboradores de Wikipedia. (2020, 14 octubre). Análisis de mallas. Wikipedia, la enciclopedia libre. Recuperado 22 de noviembre de 2021, de https://es.wikipedia.org/wiki/An%C3%A1lisis_de_mallas

Ley de Kirchhoff: Análisis de mallas. (2020, 10 abril). HETPRO/TUTORIALES. Recuperado 22 de noviembre de 2021, de https://hetpro-store.com/TUTORIALES/ley-de-kirchhoff-analisis-de-mallas/
