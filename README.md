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

IMPEDANCIA DE CIRCUITOS RLC EN SERIE: 

Un circuito RLC en serie contiene resistencia, inductancia y capacitancia. Como la reactancia inductiva y la reactancia capacitiva tienen efectos opuestos en el ángulo de fase del circuito, la reactancia total es menor que cualquier reactancia individual.

Como se sabe, la reactancia inductiva (XL) causa que la corriente total se retrase con respecto al voltaje aplicado. La reactancia capacitiva (XC) tiene el efecto opuesto: provoca que la corriente se adelante con respecto al voltaje. Por tanto, XL y XC tienden a contrarrestarse entre sí. Cuando son iguales, se eliminan y la reactancia total es de cero.

El término |XL - XC| es el valor absoluto de la diferencia de las dos reactancias. Es decir, el signo del resultado se considera positivo sin que importe cuál reactancia sea más grande. Por ejemplo, |3 - 7| = -4, pero el valor absoluto es 4

Cuando XL es mayor que XC, el circuito es predominantemente inductivo, y cuando XC es mayor que XL, el circuito es predominantemente capacitivo.

ANÁLISIS DE CIRCUITOS RLC EN SERIE: 

Recordemos que la reactancia capacitiva varía inversamente con la frecuencia y la reactancia inductiva varía directamente con la frecuencia. En esta sección, se examinan los efectos combinados de las reactancias como una función de la frecuencia. al empezar a una frecuencia muy baja, XC es alta, XL es baja, y el circuito es predominantemente capacitivo. Conforme se incrementa la frecuencia, XC disminuye y XL aumenta hasta que se alcanza un valor donde XC XL y las dos reactancias se eliminan, lo cual vuelve al circuito puramente resistivo. Esta condición se denomina resonancia en serie. A medida que la frecuencia se incrementa aún más, XL llega a ser mayor que XC, y el circuito es predominantemente inductivo.

La gráfica de XL es una línea recta y la gráfica de XC es una curva, como se muestra en la figura 17-3. La ecuación general de una línea recta es y = mx + b, donde m es la pendiente de la línea y b es el punto de intersección del eje y. La fórmula XL = 2pfL se ajusta a esta fórmula general de la línea recta, donde y = XL (una variable), m = 2pL (una constante), x = f (una variable), y b = 0 como sigue: XL 2pLf + 0. La curva XC se llama hipérbola, y su ecuación general es xy = k. La ecuación de capacitancia reactiva, XC = 1/2pfC, puede ser reordenada como XCf 1/2pC, donde x = XC (una variable), y = f (una variable), y k = 1/2pC (una constante).

En un circuito RLC en serie, el voltaje entre las terminales del capacitor y entre las terminales del inductor siempre están desfasados entre sí por 180°. Por esa razón, VC y VL se restan entre sí, y por tanto el voltaje de L y C combinados siempre es menor que el voltaje individual más grande que pueda haber entre las terminales de uno u otro componente.

RESONANCIA EN SERIE: 

En un circuito RLC en serie, la resonancia en serie ocurre cuando XC = XL. La frecuencia a la cual tiene lugar la resonancia se llama frecuencia resonante y se designa mediante fr.

En un circuito RLC en serie, la resonancia es una condición en la cual las reactancias capacitiva e inductiva son iguales en magnitud; por tanto, se eliminan entre sí y el resultado es una impedancia puramente resistiva. Para un circuito RLC en serie.

En condición resonante, XL XC y los términos j se eliminan; por tanto, la impedancia es puramente resistiva. Estas condiciones resonantes se establecen en las siguientes ecuaciones:

XL = XC

Zr = R

XL y XC se cancelan en condición de resonancia En la frecuencia resonante en serie (fr), los voltajes entre las terminales de C y L son iguales en magnitud porque las reactancias son iguales. Fluye la misma corriente a través de ambos componentes porque están en serie (IXC = IXL). Además, VL y VC están desfasados siempre en 180° entre sí. Durante cualquier ciclo dado, las polaridades de los voltajes en C y L son opuestas. Los voltajes iguales y opuestos entre las terminales de C y L se cancelan y quedan cero volts del punto A al punto B como se muestra. Puesto que no hay caída de voltaje de A a B pero sigue habiendo corriente, la reactancia total debe ser de cero.

Corriente y voltajes en un circuito RLC en serie En la frecuencia resonante en serie, la corriente es máxima (Imáx = Vs/R). Por encima y por debajo de la condición de resonancia, la corriente disminuye porque la impedancia se incrementa.

El voltaje entre las terminales del resistor, VR, sigue a la corriente y es máximo (igual a Vs) en condición de resonancia y de cero cuando f = 0 y cuando f = infinito

IMPEDANCIA DE CIRCUITOS RLC EN PARALELO: 

En esta sección, se estudiará la impedancia y el ángulo de fase de un circuito RLC dispuesto en paralelo. Conductancia, susceptancia y admitancia de un circuito RLC en paralelo también son abordadas.

Conductancia, susceptancia y admitancia Los conceptos de conductancia (G), susceptancia capacitiva (BC), susceptancia inductiva (BL), y admitancia (Y) fueron analizados en los capítulos 15 y 16. Las fórmulas fasoriales se vuelven a establecer aquí.

ANÁLISIS DE CIRCUITOS RLC EN PARALELO: 

Como ya se vio, en un circuito en paralelo domina la reactancia más pequeña porque produce la mayor corriente de rama.

Recordemos que la reactancia capacitiva varía inversamente con la frecuencia, y que la reactancia inductiva varía directamente con la frecuencia. En circuitos RLC en paralelo a frecuencias bajas, la reactancia inductiva es menor que la reactancia capacitiva; por consiguiente, el circuito es inductivo. Conforme se incrementa la frecuencia, XL aumenta y XC disminuye hasta alcanzar un valor donde XL = XC. Éste es el punto de resonancia en paralelo. A medida que la frecuencia aumenta un poco más, XC se vuelve más pequeña que XL, y el circuito se vuelve capacitivo.

Relaciones de corriente En un circuito RLC dispuesto en paralelo, las corrientes que circulan por las ramas capacitiva e inductiva siempre están desfasadas en 180° entre sí (omitiendo cualquier resistencia de bobina). Como IC e IL se suman algebraicamente, la corriente total es en realidad la diferencia de sus magnitudes. Por tanto, la corriente total que entra a las ramas de L y C en paralelo siempre es menor que la corriente de rama individual más grande.

RESONANCIA EN PARALELO: 

En esta sección, se considerará primero la condición resonante de un circuito LC ideal (sin resistencia de devanado) dispuesto en paralelo. Luego, se examinará el caso más realista en que la resistencia de la bobina se toma en cuenta.

Condición para resonancia ideal en paralelo De manera ideal, la resonancia en paralelo ocurre cuando XC = XL. La frecuencia a la cual ocurre la resonancia se llama frecuencia resonante, exactamente como en el caso en serie. Cuando XC = XL, las corrientes de rama, IC e IL, son iguales en magnitud, y, desde luego, siempre están desfasadas entre sí en 180°. Por tanto, las dos corrientes se cancelan y la corriente total es de cero.

ANÁLISIS DE CIRCUITOS RLC EN SERIE-PARALELO: En esta sección, las combinaciones serie y paralelo de los componentes de R, L y C se analizan en ejemplos específicos. Además, se aborda la conversión de un circuito en serie-paralelo a un circuito equivalente en paralelo y se considera la resonancia en un circuito no ideal en paralelo.

La equivalencia de los circuitos significa que, a una frecuencia dada, cuando se aplica el mismo valor de voltaje a ambos circuitos, la misma corriente total fluye en ambos circuitos y los ángulos de fase son los mismos. De manera básica, un circuito equivalente sólo propicia que el análisis de circuitos sea más conveniente.

Condiciones resonantes en paralelo en un circuito no ideal La resonancia de un circuito LC ideal dispuesto en paralelo se examinó en la sección 17-6. Ahora, consideremos la resonancia en un circuito tanque con la resistencia de la bobina tomada en cuenta. Recuerde que el factor de calidad, Q, del circuito en condición de resonancia es simplemente el factor Q de la bobina.

En el circuito equivalente en paralelo, Rp(eq) está en paralelo con una bobina ideal y un capacitor, por lo que las ramas L y C actúan como un circuito tanque ideal cuya impedancia es infinita en condición de resonancia. Por consiguiente, la impedancia total del circuito tanque no ideal en condición de resonancia se expresa simplemente como la resistencia equivalente en paralelo.

ANCHO DE BANDA DE CIRCUITOS RESONANTES: 

En un circuito RLC dispuesto en serie, la corriente alcanza su valor máximo a la frecuencia resonante porque las reactancias se eliminan entre sí. En un circuito RLC en paralelo, la corriente es mínima en la frecuencia resonante porque las corrientes inductiva y capacitiva se eliminan entre sí. Este comportamiento del circuito se relaciona con una característica llamada ancho de banda.

Circuitos resonantes en serie En un circuito RLC dispuesto en serie, la corriente es máxima a la frecuencia resonante (también conocida como frecuencia central) y se reduce a uno y otro lado de esta frecuencia. El ancho de banda, abreviado en ocasiones AB, es una característica importante de un circuito resonante. El ancho de banda es el intervalo de frecuencias dentro del cual la corriente es igual a o mayor que el 70.7% de su valor resonante.

Circuitos resonantes en paralelo En un circuito resonante en paralelo, la impedancia es máxima a la frecuencia resonante; de modo que la corriente total es mínima. El ancho de banda se define en relación con la curva de impedancia del mismo modo en que la curva de corriente fue utilizada en el circuito en serie. Desde luego, fr es la frecuencia a la cual Z es máxima; f1 es la frecuencia crítica inferior a la cual Z 0.707Zmáx; y f2 es la frecuencia crítica superior a la cual de nuevo Z 0.707Zmáx. El ancho de banda es el intervalo de frecuencias entre f1 y f2.

Fórmula para el ancho de banda El ancho de banda para circuitos resonantes en serie o en paralelo es el intervalo de frecuencias localizado entre las frecuencias críticas para las cuales la curva de respuesta (I o Z) es de 0.707 del valor máximo. Así, el ancho de banda es en realidad la diferencia entre f2 y f1.

AB = f1 - f2

![1](https://user-images.githubusercontent.com/117534483/222610933-bfb9b48d-6805-45f1-af83-8aa1a2b133ce.png)

![2](https://user-images.githubusercontent.com/117534483/222610935-890562f2-81d8-4af0-ad12-71ee721c3e4c.png)

![3](https://user-images.githubusercontent.com/117534483/222610936-6219f4f8-0ec4-415d-ae35-0a43e0285697.png)

![4](https://user-images.githubusercontent.com/117534483/222610937-86aa9b80-df9b-4e73-9f14-8ca8b0feeff6.png)

![5](https://user-images.githubusercontent.com/117534483/222610929-7363093b-af00-44bc-a8e5-d20b32643acf.png)

![6](https://user-images.githubusercontent.com/117534483/222610932-1e2566b0-8511-4280-b028-8ee6dc50235f.png)

*  CAPITULO 18 : FILTROS PASIVOS

FILTROS PASABAJAS: 

Un filtro pasabajas deja pasar señales de bajas frecuencias desde la entrada hasta la salida mientras rechaza las frecuencias altas. El intervalo de frecuencias pasadas por un filtro dentro de límites especificados se llama banda de paso del filtro. El punto considerado como extremo superior del intervalo de la banda de paso está en la frecuencia crítica, fc. La frecuencia crítica (fc) es la frecuencia a la cual el voltaje de salida del filtro es un 70.7% del voltaje máximo. La frecuencia crítica del filtro se conoce también como frecuencia de corte, frecuencia de ruptura, o frecuencia de -3 dB porque el voltaje de salida se encuentra a 3 dB por debajo de su valor máximo en esta frecuencia. El término dB (decibel) es una unidad utilizada comúnmente en mediciones con filtros.

Decibeles La base de la unidad decibel se deriva de la respuesta logarítmica que el oído humano presenta a la intensidad del sonido. El decibel es una medida logarítmica de la relación de una potencia a otra y de un voltaje a otro, la cual puede ser utilizada para expresar la relación de entrada a salida de un filtro. La siguiente ecuación expresa una relación de potencia en decibeles:

dB = 10 log ( Psal / Pent )

A partir de las propiedades de los logaritmos, se deriva la siguiente fórmula de los decibeles para un relación de voltaje.

dB = 20 log ( Vsal / Vent )

Filtro RC pasabajas: 

Advierta que el voltaje de salida se toma a través del capacitor. Cuando la entrada es de cd (0 Hz), el voltaje de salida es igual al voltaje de entrada porque XC es infinitamente grande. Conforme se incrementa la frecuencia de entrada, XC disminuye y, por tanto, Vsal disminuye gradualmente hasta que se alcanza una frecuencia a la cual XC R. Esta es la frecuencia crítica, fc, del filtro. Estos cálculos comprueban que la salida es el 70.7% de la entrada cuando XC R. La frecuencia a la cual ocurre esto es, por definición, la frecuencia crítica.

Pendiente decreciente (roll-off) de la curva de respuesta: La salida máxima es, por definición, de 0 dB como referencia. Cero decibeles corresponde a Vsal Vent porque 20 log (Vsal/Vent) 20 log 1 0 dB. La salida disminuye desde 0 dB hasta – 3 dB en la frecuencia crítica y luego continúa disminuyendo a un ritmo fijo. Este patrón de disminución se conoce como pendiente decreciente de la respuesta a la frecuencia. La línea gruesa muestra una respuesta de salida ideal considerada “plana” hasta la frecuencia crítica. La salida disminuye luego a un ritmo fijo.

Filtro RL pasabajas: 

Advierta que el voltaje de salida se toma a través del resistor. Cuando la entrada es de cd (0 Hz), el voltaje de salida idealmente es igual al voltaje de entrada porque XL es un corto (si RW se ignora). Conforme la frecuencia de entrada se incrementa, XL también lo hace y, por tanto, Vsal disminuye gradualmente hasta que se alcanza la frecuencia crítica. Exactamente como en el filtro RC pasabajas, Vsal 0.707Vent y, por tanto, el voltaje de salida está a –3 dB por debajo del voltaje de entrada en la frecuencia crítica.

FILTROS PASAALTAS: Un filtro pasaaltas deja pasar señales de alta frecuencia desde la entrada hasta la salida en tanto que rechaza las señales de baja frecuencia. La frecuencia considerada como el extremo inferior de la banda de paso se llama frecuencia crítica. Al igual que en el filtro pasabajas, es la frecuencia a la cual la salida es el 70.7% de la frecuencia máxima.

Filtro RC pasaaltas:

Advierta que el voltaje de salida se toma a través del resistor. Cuando la frecuencia de entrada alcanza su valor crítico, XC = R y el voltaje de salida es de 0.707Vent, como en el caso del filtro pasabajas. Conforme la frecuencia de entrada se incrementa por encima de la frecuencia crítica, XC disminuye y, por consiguiente, el voltaje de salida aumenta y tiende a un valor igual a Vent. La expresión para la frecuencia crítica del filtro pasaaltas es la misma que para el filtro pasabajas. Por debajo de fc, que el voltaje de salida presenta una pendiente decreciente a razón de 20 dB/década.

Filtro RL pasaaltas: 

Observe que la salida se toma a través del inductor. Cuando la frecuencia de salida alcanza su valor crítico, XL R, y el voltaje de salida es de 0.707Vent. Conforme la frecuencia se incrementa por encima de fc, XL aumenta y, por consiguiente, el voltaje de salida aumenta hasta que es igual a Vent. La expresión para la frecuencia crítica de un filtro pasaaltas es la misma que para el filtro pasabajas.

FILTROS PASABANDA: 

Un filtro pasabanda deja pasar cierta banda de frecuencias y atenúa o rechaza todas las frecuencias por debajo y por encima de la banda de paso. El ancho de banda de un filtro pasabanda es el intervalo de frecuencias dentro del cual la corriente, y por tanto el voltaje de salida, es igual o mayor que el 70.7% de su valor en la frecuencia de resonancia. Como se sabe, el ancho de banda a menudo se abrevia AB y se calcula como:

AB = fC2 - fC1

donde fc1 es la frecuencia de corte baja y fc2 es la frecuencia de corte alta.

Filtro pasabajas/pasaaltas Se puede utilizar la combinación de un filtro pasabajas y un filtro pasaaltas para formar un filtro pasabanda. El efecto de carga del segundo filtro sobre el primero debe ser tomado en cuenta. Si la frecuencia crítica del filtro pasabajas, fc(l), es más alta que la frecuencia crítica del filtro pasaaltas, fc(h), las respuestas se traslapan. Por tanto, todas las frecuencias excepto aquellas entre fc(h) y fc(l) son eliminadas.

Filtro pasabanda resonante en serie: Como se aprendió en el capítulo 17, un circuito resonante en serie tiene impedancia mínima y corriente máxima en la frecuencia resonante, fr. Así, la mayor parte del voltaje de entrada disminuye a través del resistor en la frecuencia de resonancia. Por consiguiente, la salida a través de R tiene una característica pasabanda con una salida máxima en la frecuencia de resonancia. La frecuencia resonante se llama frecuencia central, f0. El factor de calidad Q del circuito y la frecuencia resonante determinan el ancho de banda, tal como se vio en el capítulo 17. Recuerde que Q = XL/R.

Un valor alto de Q produce un ancho de banda más pequeño. Un valor bajo de Q produce un ancho de banda más grande. En la siguiente ecuación se establece una fórmula para determinar el ancho de banda de un circuito resonante en función de Q:

AB = fo / Q

Filtro pasabanda resonante en paralelo: Recordemos que un circuito resonante en paralelo tiene impedancia máxima en condición de resonancia. Bajo condición de resonancia, la impedancia de un circuito tanque es mucho más grande que la resistencia. Por tanto, la mayor parte del voltaje de entrada está en el circuito tanque, de modo que se produce un voltaje de salida máximo en la frecuencia de resonancia (central).

En frecuencias sobre o bajo la frecuencia de resonancia, la impedancia del circuito tanque se reduce y más del voltaje de entrada está en R. Por consiguiente, el voltaje de salida entre las terminales del circuito tanque disminuye y se crea una característica pasabanda.

FILTROS RECHAZABANDA: 

Un filtro rechazabanda es, en esencia, lo opuesto de un filtro pasabanda en función de las respuestas. Un filtro rechazabanda deja pasar todas las frecuencias excepto aquellas que quedan dentro de cierta banda de rechazo. Filtro pasabajas/pasaaltas Se puede formar un filtro rechazabanda con un filtro pasabajas y un filtro pasaaltas. Si la frecuencia crítica pasabajas, fc(l), se ajusta más baja que la frecuencia crítica pasaaltas, fc(h), se forma una característica rechazabanda.

Filtro rechazabanda resonante en serie: Un circuito resonante dispuesto en serie en una configuración rechazabanda. Básicamente, esta configuración funciona como sigue: en la frecuencia resonante, la impedancia es mínima y, por consiguiente, el voltaje de salida es mínimo. La mayor parte del voltaje de entrada disminuye a través de R. En frecuencias sobre y bajo la frecuencia de resonancia la impedancia se incrementa, lo cual provoca más voltaje en la salida.

Filtro rechazabanda resonante en paralelo: 

un circuito resonante dispuesto en paralelo utilizado en una configuración rechazabanda. En la frecuencia resonante, la impedancia del circuito tanque es máxima, y por tanto la mayor parte del voltaje de entrada aparece a través de él. Muy poco voltaje aparece en R en condición de resonancia. Conforme la impedancia del circuito tanque disminuye sobre y bajo la frecuencia de resonancia, el voltaje de salida aumenta.

![7](https://user-images.githubusercontent.com/117534483/222611061-11332dd2-b808-41f2-9488-817946a6caa4.png)

![8](https://user-images.githubusercontent.com/117534483/222611065-64596c94-a8ab-4f1c-bfef-878fa22ec021.png)

# 3.EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

# CAPITULO 17 : -Ejercicios pares

![17 1](https://user-images.githubusercontent.com/117534483/222614284-5380c3ae-c454-451e-ae28-c8f8fd95fdd1.jpg)

![17 2](https://user-images.githubusercontent.com/117534483/222614286-5906f03c-ad64-4620-ae49-bc072f967c23.jpg)

![17 3](https://user-images.githubusercontent.com/117534483/222614288-a6d12c72-b5c1-4de9-8d8d-f7812e8fadde.jpg)

![17 4](https://user-images.githubusercontent.com/117534483/222614290-2c71c373-63b0-4c2e-8d8a-9e86fb425783.jpg)

![17 5](https://user-images.githubusercontent.com/117534483/222614291-f4058efc-cd99-4922-99ce-12f5c6658fb5.jpg)

![17 6](https://user-images.githubusercontent.com/117534483/222614292-16fff9ba-b342-4868-b9d9-d932fd772e76.jpg)

![17 7](https://user-images.githubusercontent.com/117534483/222614293-410b13b5-ac45-4607-a34c-9dec6d475c9f.jpg)

![17 8](https://user-images.githubusercontent.com/117534483/222614295-80c69bf1-b073-469e-a92d-4b15e54677a4.jpg)

![17 9](https://user-images.githubusercontent.com/117534483/222614296-eed438ad-97f8-492d-ba04-dd78c1318637.jpg)

![17 10](https://user-images.githubusercontent.com/117534483/222614298-9c0fb8e2-309c-40b2-af4e-0b3f891a41a6.jpg)

# CAPITULO 18 : -Ejercicios pares

![18 1](https://user-images.githubusercontent.com/117534483/222614353-a4560af0-76ee-4a9c-bcb4-74d14e21dd36.jpg)

![18 2](https://user-images.githubusercontent.com/117534483/222614356-0b7c818e-bba3-4d5c-9cd5-fe30d4d83c97.jpg)

![18 3](https://user-images.githubusercontent.com/117534483/222614358-e2d2f2e8-69b8-43ef-a8e0-f761e35fedd6.jpg)

![18 4](https://user-images.githubusercontent.com/117534483/222614359-375012ed-7fd5-47d9-9dc8-56fcf1ea6a7a.jpg)

![18 5](https://user-images.githubusercontent.com/117534483/222614360-cfcf059c-a87f-4af8-8340-5af80e1e5511.jpg)

![18 6](https://user-images.githubusercontent.com/117534483/222614361-f438d510-d4f6-4d3e-b01c-369214c45201.jpg)

![18 7](https://user-images.githubusercontent.com/117534483/222614363-2f2dc2c2-1c34-41b0-bef8-f83f9bcc9533.jpg)

![18 8](https://user-images.githubusercontent.com/117534483/222614364-03332065-0f5f-43bb-a237-225293927247.jpg)

# 4.VIDEO

- 

# 5.CONCLUSIONES

* XL y XC tienen efectos opuestos en un circuito RLC.

* En un circuito RLC dispuesto en serie, la reactancia más grande determina la reactancia neta del circuito.

* En condición de resonancia en serie, las reactancias inductiva y capacitiva son iguales.

* La impedancia de un circuito RLC en serie es puramente resistiva en condición de resonancia.

* En un circuito RLC en serie, la corriente es máxima en condición de resonancia.

* Los voltajes reactivos VL y VC se eliminan en condición de resonancia en un circuito RLC en serie porque son iguales en magnitud y están desfasados por 180°.

* En un circuito RLC en paralelo, la reactancia más pequeña determina la reactancia neta del circuito.

* En un circuito resonante en paralelo, la impedancia es máxima a la frecuencia resonante.

* Un circuito resonante en paralelo comúnmente se llama circuito tanque.

* Cuatro categorías de filtros pasivos, de acuerdo con sus características de respuesta, son: pasabajas, pasaaltas, pasabanda y rechazabanda.

* En un filtro RC pasabajas, el voltaje de salida se toma a través del capacitor y la salida se retrasa con respecto a la entrada.

* En un filtro RL pasabajas, el voltaje de salida se toma a través del resistor y la salida se retrasa con respecto a la entrada.

* En un filtro RC pasaaltas, la salida se toma a través del resistor y la salida se adelanta a la entrada.

* En un filtro RL pasaaltas, la salida se toma a través del inductor y la salida se adelanta a la entrada.

* La pendiente decreciente de un filtro RC o RL es de –20 dB por década.

* Un filtro pasabanda deja pasar frecuencias localizadas entre las frecuencias críticas baja y alta y rechaza todas las demás.

* Un filtro rechazabanda rechaza frecuencias ubicadas entre sus frecuencias críticas baja y alta y deja pasar todas las demás.

# 6.BIBLIOGRAFÍA

*  Floyd (8va Ed)(2007). Principios de circuitos electricos. Pearson Education.
