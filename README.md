# Informe Tarea 9


Nombre: Mauricio Fuerez

NRC:10069

El informe realizado a continuación está evaluado y especificado para la compresión de los capítulos  17 y 18 del libro: Principios de circuitos eléctricos - Floyd

# 1.OBJETIVOS

1.1 Objetivo general:

*  Analizar y entender el capitulo 17 y 18 del libro "Principios de circuitos electricos - Floyd" para lo cual se debera leer y resolver los ejercicios pares que se encuentran al terminar el capitulo.

1.2 Objetivos especificos:

* Analizar los circuitos RCL, los tipos de resonancias y frecuencias

* Estudiar circuitos RC y RL en paralelo y en serie

* Diferenciar entre los tipos de filtros presentados en la tarea, comprendiendo sus usos
 
# 2.MARCO TEÓRICO

*  CAPITULO 17 : CIRCUITOS RLC Y RESONANCIA

Dado que la reactancia inductiva y la reactancia capacitiva tienen efectos opuestos en el ángulo de fase del circuito, la reactancia total es menor que cualquier reactancia individual. Como se sabe, la reactancia inductiva hace que la corriente total se retrase con respecto al voltaje aplicado. Cuando son iguales, se cancelan y la reactancia total es cero. El término |XL - XC| es el valor absoluto de la diferencia de las dos reactancias.

Es decir, el signo del resultado se considera positivo independientemente de la reactancia más alta. Cuando XL es mayor que XC, el circuito es mayormente inductivo, y cuando XC es mayor que XL, el circuito es mayormente capacitivo. Esta sección examina los efectos combinados de las reactancias en función de la frecuencia. comenzando en una frecuencia muy baja, XC es alta, XL es baja y el circuito es principalmente capacitivo.

A medida que aumenta la frecuencia, XC disminuye y XL aumenta hasta llegar a un valor donde se eliminan XC XL y ambas reactancias, volviendo a un circuito puramente resistivo. Esta condición se llama resonancia en serie. A medida que aumenta la frecuencia, XL se vuelve más grande que XC y el circuito es principalmente inductivo. En un circuito RLC en serie, el voltaje a través del capacitor y el inductor siempre están desfasados 180° entre sí.

Por esta razón, VC y VL se restan entre sí, por lo que el voltaje combinado de L y C siempre es más bajo que el voltaje más alto en cualquiera de los componentes. La frecuencia a la que se produce la resonancia se denomina frecuencia resonante y se denota como fr. Para un circuito RLC en serie.

Zr=R

XL y XC se cancelan en la condición de resonancia. A la frecuencia de resonancia en serie , los voltajes entre las terminales de C y L son de igual magnitud porque las reactancias son iguales. La misma corriente fluye a través de los dos componentes porque están en serie . Dado que no hay caída de voltaje de A a B pero todavía hay corriente, la reactancia total debe ser cero.

Corriente y tensiones en un circuito RLC en serie A la frecuencia de resonancia en serie, la corriente es máxima . El voltaje a través de la resistencia, VR, sigue a la corriente y es máximo en resonancia y cero cuando f = 0 y cuando f = infinito. También se tratan la conductancia, la susceptancia y la admitancia de un circuito RLC en paralelo.

En circuitos RLC en paralelo a bajas frecuencias, la reactancia inductiva es menor que la reactancia capacitiva. Por lo tanto, el circuito es inductivo. Relaciones de corriente En un circuito RLC en paralelo, las corrientes que fluyen en las ramas capacitiva e inductiva siempre están desfasadas 180° entre sí . Además, la conversión de un circuito serie-paralelo en un circuito paralelo equivalente y la sintonización en un circuito paralelo considerado no ideal.

La equivalencia de circuito significa que, a una frecuencia dada, cuando se aplica el mismo valor de voltaje a ambos circuitos, fluye la misma corriente total en ambos circuitos y los ángulos de fase son los mismos. Básicamente, un circuito equivalente solo hace que el análisis de circuitos sea más conveniente. Condiciones para la sintonización en paralelo en un circuito no ideal La sintonización de un circuito LC ideal dispuesto en paralelo se analizó en la sección 17-6. Ahora considere la resonancia en el circuito del tanque en términos de la resistencia de la bobina.

Recuerde que el factor de calidad, Q, del circuito en resonancia es simplemente el factor Q de la bobina. En el circuito equivalente en paralelo, Rp está en paralelo con una bobina y un capacitor ideales, de modo que las ramas L y C actúan como un circuito tanque ideal cuya impedancia es infinita en resonancia. Por lo tanto, la impedancia total del circuito tanque no ideal en resonancia se expresa simplemente como la resistencia paralela equivalente. En un circuito RLC en paralelo, la corriente es mínima en la frecuencia resonante porque las corrientes inductiva y capacitiva se anulan entre sí.

Este comportamiento del circuito está relacionado con una característica llamada ancho de banda. Circuitos resonantes en serie En un circuito RLC en serie, la corriente alcanza su punto máximo en la frecuencia resonante y cae en cualquier lado de esa frecuencia. El ancho de banda, a veces abreviado AB, es una característica importante de un circuito resonante. Circuitos resonantes en paralelo En un circuito resonante en paralelo, la impedancia es máxima en la frecuencia resonante.

El ancho de banda se define en términos de la curva de impedancia de la misma manera que se usó la curva de corriente en el circuito en serie. Tipo de ancho de banda El ancho de banda para circuitos resonantes en serie o en paralelo es el intervalo de frecuencia entre las frecuencias críticas para las que se encuentra la curva de respuesta .

AB=f1-f2

Entonces, el ancho de banda es en realidad la diferencia entre f2 y f1.

AB = f1 - f2

![1](https://user-images.githubusercontent.com/117534483/222610933-bfb9b48d-6805-45f1-af83-8aa1a2b133ce.png)

![2](https://user-images.githubusercontent.com/117534483/222610935-890562f2-81d8-4af0-ad12-71ee721c3e4c.png)

![3](https://user-images.githubusercontent.com/117534483/222610936-6219f4f8-0ec4-415d-ae35-0a43e0285697.png)

![4](https://user-images.githubusercontent.com/117534483/222610937-86aa9b80-df9b-4e73-9f14-8ca8b0feeff6.png)

![5](https://user-images.githubusercontent.com/117534483/222610929-7363093b-af00-44bc-a8e5-d20b32643acf.png)

![6](https://user-images.githubusercontent.com/117534483/222610932-1e2566b0-8511-4280-b028-8ee6dc50235f.png)

*  CAPITULO 18 : FILTROS PASIVOS

FILTROS DE PASO BAJO

Un filtro de paso bajo pasa señales de baja frecuencia desde la entrada a la salida mientras rechaza las frecuencias altas. El rango de frecuencias que pasan a través de un filtro dentro de los límites especificados se denomina banda de paso del filtro. El punto considerado como el extremo superior del intervalo de banda de paso está en la frecuencia crítica, fc. La frecuencia crítica (fc) es la frecuencia a la que la tensión de salida del filtro es el 70,7% de la tensión máxima. La frecuencia crítica del filtro también se conoce como frecuencia de corte, frecuencia de ruptura o frecuencia de -3 dB porque el voltaje de salida está 3 dB por debajo de su valor máximo en esta frecuencia. El término dB (decibel) es una unidad común utilizada en la medición de filtros.

Decibeles La base de la unidad de decibelios se deriva de la respuesta logarítmica que exhibe el oído humano a la intensidad del sonido. El decibelio es una medida logarítmica de la relación de una potencia a otra y de un voltaje a otro, que se puede utilizar para expresar la relación de entrada a salida de un filtro. La siguiente fórmula expresa una relación de potencia en decibelios:

dB = 10 log ( Salmo / Pent )

A partir de las propiedades de los logaritmos, se deriva la siguiente fórmula de decibelios para una relación de voltaje.

dB = 20 log (Vout / Vent)

Filtro RC de paso bajo: tenga en cuenta que el voltaje de salida se toma a través del capacitor. Cuando la entrada es CC (0 Hz), el voltaje de salida es igual al voltaje de entrada porque XC es infinitamente grande. A medida que aumenta la frecuencia de entrada, XC disminuye y, por lo tanto, Vout disminuye gradualmente hasta que se alcanza una frecuencia donde XC R. Esta es la frecuencia crítica, fc, del filtro. Estos cálculos prueban que la salida es el 70,7% de la entrada cuando XC R. La frecuencia a la que esto ocurre es, por definición, la frecuencia crítica.

Pendiente decreciente (roll-off) de la curva de respuesta: La salida máxima es, por definición, 0 dB como referencia. Cero decibelios corresponden a Vout Vent porque 20 log (Vout/Vent) 20 log 1 0 dB. La salida decae de 0 dB a –3 dB en la frecuencia crítica y luego continúa decayendo a una tasa fija. Este patrón de caída se conoce como pendiente descendente de la respuesta de frecuencia. La línea gruesa muestra una respuesta de salida ideal considerada "plana" hasta la frecuencia crítica. La salida luego disminuye a una tasa fija.

Filtro de paso bajo RL: tenga en cuenta que el voltaje de salida se toma a través de la resistencia. Cuando la entrada es CC (0 Hz), el voltaje de salida idealmente es igual al voltaje de entrada porque XL es un cortocircuito (si se ignora RW). A medida que aumenta la frecuencia de entrada, XL también aumenta y, por lo tanto, Vout disminuye gradualmente hasta alcanzar la frecuencia crítica. Exactamente como en el filtro de paso bajo RC, Vout 0.707Vin, por lo que el voltaje de salida es -3dB por debajo del voltaje de entrada en la frecuencia crítica.

FILTROS DE PASO ALTO: Un filtro de paso alto pasa señales de alta frecuencia desde la entrada a la salida mientras rechaza las señales de baja frecuencia. La frecuencia considerada como el extremo inferior de la banda de paso se denomina frecuencia crítica. Al igual que en el filtro de paso bajo, es la frecuencia en la que la salida es el 70,7% de la frecuencia máxima.

Filtro RC de paso alto: tenga en cuenta que el voltaje de salida se toma a través de la resistencia. Cuando la frecuencia de entrada alcanza su valor crítico, XC = R y el voltaje de salida es 0.707Vent, como en el caso de los filtros de paso. A medida que la frecuencia de entrada aumenta por encima de la frecuencia crítica, XC disminuye y, por lo tanto, el voltaje de salida aumenta y se acerca a un valor igual a Vent. La expresión para la frecuencia crítica del filtro de paso alto es la misma que para el filtro de paso bajo. Por debajo de fc, que el voltaje de salida tiene una pendiente decreciente a razón de 20 dB/década.

Filtro RL de paso alto: tenga en cuenta que la salida se toma a través del inductor. Cuando la frecuencia de salida alcanza su valor crítico, XL R, y el voltaje de salida es 0.707Vent. A medida que la frecuencia aumenta por encima de fc, XL aumenta y, por lo tanto, el voltaje de salida aumenta hasta igualar a Vent. La expresión para la frecuencia crítica de un filtro de paso alto es la misma que para el filtro de paso bajo.

FILTROS DE PASO DE BANDA: Un filtro de paso de banda pasa una determinada banda de frecuencias y atenúa o rechaza todas las frecuencias por debajo y por encima de la banda de paso. El ancho de banda de un filtro pasabanda es el rango de frecuencias dentro del cual la corriente, y por tanto la tensión de salida, es igual o superior al 70,7% de su valor a la frecuencia resonante. Como se sabe, el ancho de banda a menudo se abrevia AB y se calcula como: AB = fC2 - fC1 donde fc1 es la frecuencia de corte baja y fc2 es la frecuencia de corte alta. Filtro de paso bajo/paso alto Se puede utilizar una combinación de un filtro de paso bajo y un filtro de paso alto para formar un filtro de paso de banda. Debe tenerse en cuenta el efecto de carga del segundo filtro sobre el primero. Si la frecuencia crítica del filtro de paso bajo, fc, es mayor que la frecuencia crítica del filtro de paso alto, fc, las respuestas se superponen. Por lo tanto, se eliminan todas las frecuencias excepto aquellas entre fc y fc. Filtro de paso de banda resonante en serie: como aprendió en el Capítulo 17, un circuito resonante en serie tiene una impedancia mínima y una corriente máxima en la frecuencia resonante, fr. Por lo tanto, la mayor parte del voltaje de entrada cae en la resistencia a la frecuencia resonante.

AB = fo / Q

Filtro de paso de banda resonante paralelo: Recuerde que un circuito resonante paralelo tiene una impedancia máxima en la condición resonante. En condiciones de resonancia, la impedancia de un circuito tanque es mucho mayor que la resistencia. Por lo tanto, la mayor parte del voltaje de entrada está en el circuito del tanque, lo que produce un voltaje de salida máximo en la frecuencia resonante . A frecuencias por encima o por debajo de la frecuencia resonante, la impedancia del circuito del tanque se reduce y una mayor parte del voltaje de entrada está en R. En consecuencia, el voltaje de salida entre los terminales del circuito del tanque disminuye, creando una característica de paso de banda. FILTROS DE RECHAZO DE BANDA: Un filtro de rechazo de banda es esencialmente lo opuesto a un filtro de paso de banda basado en respuesta. Un filtro de muesca pasa todas las frecuencias excepto aquellas dentro de una determinada banda de parada. Filtro de paso bajo/paso alto Se puede formar un filtro de rechazo de banda con un filtro de paso bajo y un filtro de paso alto. Si la frecuencia crítica de paso bajo, fc, se establece por debajo de la frecuencia crítica de paso alto, fc, se forma una característica de muesca. Filtro de parada de banda resonante en serie: un circuito resonante dispuesto en serie en una configuración de muesca. Básicamente, esta configuración funciona así: a la frecuencia resonante, la impedancia es mínima y, por lo tanto, el voltaje de salida es mínimo.


# 3.EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

# CAPITULO 17 : -Ejercicios pares



# CAPITULO 18 : -Ejercicios pares



# 4.VIDEO

- 

# 5.CONCLUSIONES

* 


# 6.BIBLIOGRAFÍA

*  Floyd (8va Ed)(2007). Principios de circuitos electricos. Pearson Education.
