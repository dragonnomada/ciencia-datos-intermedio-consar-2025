# Estadística diferencial y probabilidad

    Variables aleatorias
    Distribuciones
    Pruebas de hipótesis
    Correlación
    Regresión
    Análisis de la varianza (ANOVA)

## Variables aleatorias

Los fenémenos generalmente representan problemáticas o estudios de interés sobre comportamientos naturales o artificiales que quieren ser entendididos para su mejora y automatización. Estos se derivan en eventos que describen las causas involucradas y cada evento forma una población a la que llamaremos el universo de eventos o fenómeno.

Los eventos son carecterizados y descompuestos en características que se expresan como datos y conforman un conjunto de datos al que reconocemos como una muestra de la población, es decir, si la población es el universo de todos los eventos posibles asociados al fenómeno, entonces, una muestra de esa población será el conjunto de datos sobre las características del evento.

Cada característica representa un patrón natural del evento y su comportamiento no es constante sobre toda la población, al contrario de eso, mostrará un comportamiento variable y aleatorio, en el sentido que no se puede determinar el valor exacto de un siguiente registro en el conjunto de datos. Esta variabilidad es estudiada por la estadística mediante la construcción de **Variables Aleatorias**, y cuyo comportamiento aleatorio será estudiado por su probabilidad.

En resumen, tenemos que:

    Fenómeno 
        -se explica-> 
    eventos 
        -se caracterizan-> 
    características 
        -conforman-> 
    variables aleatorias 
        -generan-> 
    ejes de análisis

![m101](./figuras/m101.png)

## Distribuciones

La probabilidad analiza eventos aleatorios que ocurren o pueden ocurrir como lanzar una moneda, lanzar los dados, si lloverá o el tiempo de llegada o espera. Estos eventos generalmente tienen naturalezas espacio-temporales y determinan posibilidades.

La posibilidad de que ocurra un evento se cuantifica como la probabilidad de que ocurra el evento según un conjunto de eventos observados. Por ejemplo, la probabilidad que al lanzar 2 dados salgan las caras $(1, 1)$ podría ser incierta, pero si observamos 36 posibles lanzamientos tendríamos:

$$
lanzamientos = \{ (1, 1), (1, 2), ..., (1, 6), (2, 1), (2, 2), ..., (2, 6), ..., (6, 6) \}
$$

El universo posible no significa que sea real ya que asumimos que cada evento tiene la misma posibilidad de ocurrir (por ejemplo, que los dados caen siempre equitativamente). Pero cuando observamos la realidad, podría ocurrir algo distinto, algunos eventos incluso podrían ni siquiera ocurrir en las $10,000$ observaciones que hicieramos.

A los eventos ocurridos les llamaremos probabilidades, a los eventos imaginados les llamaremos posibilidades.

La probabilidad consiste en observar eventos y cuantificar la frecuencia de apariciones u ocurrencias, a esta probabilidad para cada evento se le conoce como su densidad. Entonces, la densidad es una función que determina la probabilidad de que un evento ocurra según lo observado.

La densidad generalmente en fenómenos estables tiene un comportamiento fijo a lo largo de todos eventos y parecido a un montículo uniforme, normal, sesgado o bifurcado. En cualquier variante la densidad expresa un cúmulo de concentraciones de probabilidades a lo largo de ciertos valores. Cuando la probabilidad se convierte en una densidad y la densidad se aproxima a una función conocida matemáticamente se genera una función de densidad que describe la distribución de los datos.

La distribución de los datos le permite a la estadística plantear supuestos sobre los valores esperados y la dispersión entre los datos y cuantifica estos supuestos para construir estadísticos e intervalos de confianza que respaldan los supuestos de prónostico y predicción en los modelos de inferencia.

![m102](./figuras/m102.png)