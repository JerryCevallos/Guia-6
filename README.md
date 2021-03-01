# Guia-6
Características de la Onda Senoidal

1. Objetivos

  1.1 Objetivo General 

  Determinar experimentalmente las características de señales senoidales.

  1.2 Objetivos Especificos 
  
  •	Comprender y aprender a usar el software Proteus 
  •	Reconocer las diferentes señales que nos proporciona la onda senoidal y hacer un muestreo con los valores obtenidos
  •	Construir un circuito utilizar un multímetro y utilizar el osciloscopio para realizar mediciones


2. Requisitos previos

  Investigue la representación de la onda senoidal, tanto en su forma gráfica como en su forma matemática.

3. Marco Teorico

¿Que es una Onda Senoidal?

Onda senoidal representa el valor de la tensión de la Corriente alterna a través de un tiempo continuamente variable, en un par de ejes cartesianos marcados en amplitud y tiempo. Responde a la corriente de canalización generada en las grandes plantas eléctricas del mundo. También responden a la misma forma, todas las corrientes destinadas a generar los campos electromagnéticos de las ondas de radio.

Forma de la onda: La Corriente alterna se genera por diferentes métodos los más utilizados son los mecánicos rotativos, o alternadores de las bobinas eléctricas, para grandes potencias, y los electrónicos cuando las mismas son pequeñas, esta manera de generar la corriente, determinará su Ley de Variación con respecto al tiempo.Es la forma mas generalizada y responde a la corriente de canalización generada en las grandes plantas eléctricas del mundo. 

También responden a la misma forma, todas las corrientes destinadas a generar los campos electromagnéticos de las ondas de radio. La manera mas práctica de entender la generación de esta onda es utilizar el “círculo trigonométrico“, o sea, un círculo centrado en un par de ejes cartesianos, con un radio que gira a velocidad constante con sentido contrario a las agujas del reloj, partiendo de la posición horizontal derecha, de manera que el ángulo que forma con la horizontal, partiendo de 0º pasa a 90º cuando está vertical, sigue a 180º cuando llega a horizontal a la izquierda , sigue con 270º cuando está nuevamente vertical pero hacia abajo, y termina en 360º cuando llega a la posición inicial, o sea horizontal a la derecha. El seno trigonométrico de estos ángulos que se va generando a medida que el radio de la circunferencia gira, viene representado por la altura del punto correspondiente al extremo del radio que forma el círculo, referida al eje horizontal. Esa altura comienza en 0 para el comienzo, o sea el ángulo de 0º, para ir aumentando hasta llegar al máximo, que se toma como valor unitario “1“ cuando el radio esté vertical, o sea con un ángulo de 90º. El radio sigue girando y la altura comenzará a disminuir, para llegar nuevamente a cero cuando el radio forme el ángulo de 180º, o sea esté nuevamente en posición horizontal.


Para su representacion decimos que esta Ley de Variación en un par de ejes cartesianos marcados en amplitud y tiempo, se producirán gráficas con diferentes formas geométricas que identifiquen la corriente. Las formas de ondas más comunes son:

•	La senoidal
•	La cuadrada
•	La triangular
•	La diente de sierra

Tambien podemos hablar de la continuidad de giro: Continuidad del giro: A partir de ese momento, con la continuación del giro, la altura comenzará nuevamente a aumentar, pero ahora hacia abajo de la línea horizontal, con los mismos valores absolutos que los anteriores, por lo que se los toma con el signo negativo. Al llegar a la posición horizontal, o sea a un ángulo de 360º, se termina el ciclo. A partir de ese momento, comenzará uno nuevo, que se superpondrá con el anterior con todos los mismos valores que ya se produjeron. Si ahora graficamos todos los valores de la altura del punto extremo del radio mientras va girando, o sea el valor del seno del ángulo que se va formando, a partir de una recta horizontal y respetando el signo, se formará una figura ondulada cuando se unan todos los extremos de las mencionadas alturas; figura que recibe el nombre de curva sinusoidal o senoidal, por responder a la función del seno.

  3.1 Uso de oscilocopio para medir ondas senosoidales

  Primero debemos entender ¿Qué es un osciloscopio?

El osciloscopio es basicamente un dispositivo de visualización gráfica que muestra señales electricas variables en el tiempo. El eje vertical, a partir de ahora denominado Y, representa el voltaje; mientras que el eje horizontal, denominado X, representa el tiempo.

  ¿Qué podemos hacer con un osciloscopio?

  •	Determinar directamente el periodo y el voltaje de una señal.
  •	Determinar indirectamente la frecuencia de una señal.
  •	Determinar que parte de la señal es DC y cual AC.
  •	Localizar averias en un circuito.
  •	Medir la fase entre dos señales.
  •	Determinar que parte de la señal es ruido y como varia este en el tiempo.

¿Como funciona un osciloscopio?

Para entender el funcionamiento de los controles que posee un osciloscopio es necesario deternerse un poco en los procesos internos llevados a cabo por este aparato. Empezaremos por el tipo analógico ya que es el más sencillo.

Tipos de Osciloscopios

  Osciloscopios analógicos
  
  Cuando se conecta la sonda a un circuito, la señal atraviesa esta última y se dirige a la sección vertical. Dependiendo de donde situemos el mando del amplificador vertical     atenuaremos la señal ó la amplificaremos. En la salida de este bloque ya se dispone de la suficiente señal para atacar las placas de deflexión verticales (que naturalmente       estan en posición horizontal) y que son las encargadas de desviar el haz de electrones, que surge del catodo e impacta en la capa fluorescente del interior de la pantalla, en   sentido vertical. Hacia arriba si la tensión es positiva con respecto al punto de referencia (GND) ó hacia abajo si es negativa.
  
  Osciloscopio digital 
  
  Los osciloscopios digitales poseen además de las secciones explicadas anteriormente un sistema adicional de proceso de datos que permite almacenar y visualizar la señal.Cuando   se conecta la sonda de un osciloscopio digital a un circuito, la sección vertical ajusta la amplitud de la señal de la misma forma que lo hacia el osciloscopio analógico.
  
  Metodos para medir
  
  Métodos de muestreo
Se trata de explicar como se las arreglan los osciloscopios digitales para reunir los puntos de muestreo. Para señales de lenta variación, los osciloscopios digitales pueden perfectamente reunir más puntos de los necesarios para reconstruir posteriormente la señal en la pantalla. No obstante, para señales rápidas (como de rápidas dependerá de la máxima velocidad de muestreo de nuestro aparato) el osciloscopio no puede recoger muestras suficientes y debe recurrir a una de estas dos técnicas:

Interpolación , es decir, estimar un punto intermedio de la señal basandose en el punto anterior y posterior.
Muestreo en tiempo equivalente . Si la señal es repetitiva es posible muestrear durante unos cuantos ciclos en diferentes partes de la señal para después reconstruir la señal completa.

	

 
EL OSCILOSCOPIO
¿Qué es un osciloscopio?
El osciloscopio es basicamente un dispositivo de visualización gráfica que muestra señales electricas variables en el tiempo.

El eje vertical, a partir de ahora denominado Y, representa el voltaje; mientras que el eje horizontal, denominado X, representa el tiempo.

¿Qué podemos hacer con un osciloscopio?
Basicamente esto:

Determinar directamente el periodo y el voltaje de una señal.
Determinar indirectamente la frecuencia de una señal.
Determinar que parte de la señal es DC y cual AC.
Localizar averias en un circuito.
Medir la fase entre dos señales.
Determinar que parte de la señal es ruido y como varia este en el tiempo.
Articulo extraido de Lidernet.com Firmado por Agustin Borrego Colomer

Los osciloscopios son de los instrumentos más versatiles que existen y lo utilizan desde técnicos de reparación de televisores a médicos. Un osciloscopio puede medir un gran número de fenomenos, provisto del transductor adecuado (un elemento que convierte una magnitud física en señal eléctrica) será capaz de darnos el valor de una presión, ritmo cardiaco, potencia de sonido, nivel de vibraciones en un coche, etc.

¿Qué tipos de osciloscopios existen?
Los equipos electrónicos se dividen en dos tipos: Analógicos y Digitales . Los primeros trabajan con variables continuas mientras quie los segundos lo hacen con variables discretas. Por ejemplo un tocadiscos es un equipo analógico y un Compact Disc es un equipo digital.

Los Osciloscopios también pueden ser analógicos ó digitales. Los primeros trabajan directamente con la señal aplicada, está una vez amplificada desvia un haz de electrones en sentido vertical proporcionalmente a su valor. En contraste los osciloscopios digitales utilizan previamente un conversor analógico-digital (A/D) para almacenar digitalmente la señal de entrada, reconstruyendo posteriormente esta información en la pantalla.

Ambos tipos tienen sus ventajas e inconvenientes. Los analógicos son preferibles cuando es prioritario visualizar variaciones rápidas de la señal de entrada en tiempo real. Los osciloscopios digitales se utilizan cuando se desea visualizar y estudiar eventos no repetitivos (picos de tensión que se producen aleatoriamente).

¿Qué controles posee un osciloscopio típico?
A primera vista un osciloscopio se parece a una pequeña televisión portatil, salvo una rejilla que ocupa la pantalla y el mayor número de controles que posee. En la siguiente figura se representan estos controles distribuidos en cinco secciones:



** Vertical. ** Horizontal. ** Disparo. ** Control de la visualización ** Conectores.

¿Como funciona un osciloscopio?
Para entender el funcionamiento de los controles que posee un osciloscopio es necesario deternerse un poco en los procesos internos llevados a cabo por este aparato. Empezaremos por el tipo analógico ya que es el más sencillo.

Osciloscopios analógicos


Cuando se conecta la sonda a un circuito, la señal atraviesa esta última y se dirige a la sección vertical. Dependiendo de donde situemos el mando del amplificador vertical atenuaremos la señal ó la amplificaremos.

En la salida de este bloque ya se dispone de la suficiente señal para atacar las placas de deflexión verticales (que naturalmente estan en posición horizontal) y que son las encargadas de desviar el haz de electrones, que surge del catodo e impacta en la capa fluorescente del interior de la pantalla, en sentido vertical. Hacia arriba si la tensión es positiva con respecto al punto de referencia (GND) ó hacia abajo si es negativa.


 
La señal también atraviesa la sección de disparo para de esta forma iniciar el barrido horizontal (este es el encargado de mover el haz de electrones desde la parte izquierda de la pantalla a la parte derecha en un determinado tiempo).

El trazado (recorrido de izquierda a derecha) se consigue aplicando la parte ascendente de un diente de sierra a las placas de deflexión horizontal (las que estan en posición vertical), y puede ser regulable en tiempo actuando sobre el mando TIME-BASE. El retrazado (recorrido de derecha a izquierda) se realiza de forma mucho más rápida con la parte descendente del mismo diente de sierra.

De esta forma la acción combinada del trazado horizontal y de la deflexión vertical traza la gráfica de la señal en la pantalla. La sección de disparo es necesaria para estabilizar las señales repetitivas (se asegura que el trazado comienze en el mismo punto de la señal repetitiva).

En la siguiente figura puede observarse la misma señal en tres ajustes de disparo diferentes: en el primero disparada en flanco ascendente, en el segundo sin disparo y en el tercero disparada en flanco descendente.

		
Como conclusión para utilizar de forma correcta un osciloscopio analógico necesitamos realizar tres ajuste básicos:

La atenuación ó amplificación que necesita la señal. Utilizar el mando AMPL. para ajustar la amplitud de la señal antes de que sea aplicada a las placas de deflexión vertical. Conviene que la señal ocupe una parte importante de la pantalla sin llegar a sobrepasar los límites.
La base de tiempos. Utilizar el mando TIMEBASE para ajustar lo que representa en tiempo una división en horizontal de la pantalla. Para señales repetitivas es conveniente que en la pantalla se puedan observar aproximadamente un par de ciclos.
Disparo de la señal. Utilizar los mandos TRIGGER LEVEL (nivel de disparo) y TRIGGER SELECTOR (tipo de disparo) para estabilizar lo mejor posible señales repetitivas.
Por supuesto, también deben ajustarse los controles que afectan a la visualización: FOCUS (enfoque), INTENS. (intensidad) nunca excesiva, Y-POS (posición vertical del haz) y X-POS (posición horizontal del haz).

Osciloscopios digitales
Los osciloscopios digitales poseen además de las secciones explicadas anteriormente un sistema adicional de proceso de datos que permite almacenar y visualizar la señal.



Cuando se conecta la sonda de un osciloscopio digital a un circuito, la sección vertical ajusta la amplitud de la señal de la misma forma que lo hacia el osciloscopio analógico.

El conversor analógico-digital del sistema de adquisición de datos muestrea la señal a intervalos de tiempo determinados y convierte la señal de voltaje continua en una serie de valores digitales llamados muestras . En la sección horizontal una señal de reloj determina cuando el conversor A/D toma una muestra. La velocidad de este reloj se denomina velocidad de muestreo y se mide en muestras por segundo.



Los valores digitales muestreados se almacenan en una memoria como puntos de señal. El número de los puntos de señal utilizados para reconstruir la señal en pantalla se denomina registro. La sección de disparo determina el comienzo y el final de los puntos de señal en el registro. La sección de visualización recibe estos puntos del registro, una vez almacenados en la memoria, para presentar en pantalla la señal.

Dependiendo de las capacidades del osciloscopio se pueden tener procesos adicionales sobre los puntos muestreados, incluso se puede disponer de un predisparo, para observar procesos que tengan lugar antes del disparo.


 
Fundamentalmente, un osciloscopio digital se maneja de una forma similar a uno analógico, para poder tomar las medidas se necesita ajustar el mando AMPL.,el mando TIMEBASE asi como los mandos que intervienen en el disparo.


 
Métodos de muestreo
Se trata de explicar como se las arreglan los osciloscopios digitales para reunir los puntos de muestreo. Para señales de lenta variación, los osciloscopios digitales pueden perfectamente reunir más puntos de los necesarios para reconstruir posteriormente la señal en la pantalla. No obstante, para señales rápidas (como de rápidas dependerá de la máxima velocidad de muestreo de nuestro aparato) el osciloscopio no puede recoger muestras suficientes y debe recurrir a una de estas dos técnicas:

Interpolación , es decir, estimar un punto intermedio de la señal basandose en el punto anterior y posterior.
Muestreo en tiempo equivalente . Si la señal es repetitiva es posible muestrear durante unos cuantos ciclos en diferentes partes de la señal para después reconstruir la señal completa.
Muestreo en tiempo real con Interpolación
El método standard de muestreo en los osciloscopios digitales es el muestreo en tiempo real: el osciloscopio reune los suficientes puntos como para recontruir la señal. Para señales no repetitivas ó la parte transitoria de una señal es el único método válido de muestreo.

Los osciloscopios utilizan la interpolación para poder visualizar señales que son más rápidas que su velocidad de muestreo. Existen basicamente dos tipos de interpolación:

Lineal : Simplemente conecta los puntos muestreados con lineas. Senoidal : Conecta los puntos muestreados con curvas según un proceso matemático, de esta forma los puntos intermedios se calculan para rellenar los espacios entre puntos reales de muestreo. Usando este proceso es posible visualizar señales con gran precisión disponiendo de relativamente pocos puntos de muestreo.



Muestreo en tiempo equivalente
Algunos osciloscopios digitales utilizan este tipo de muestreo. Se trata de reconstruir una señal repetitiva capturando una pequeña parte de la señal en cada ciclo.Existen dos tipos básicos: Muestreo secuencial- Los puntos aparecen de izquierda a derecha en secuencia para conformar la señal. Muestreo aleatorio- Los puntos aparecen aleatoriamente para formar la señal

Ondas senoidales en el osciloscopio 
Son las ondas fundamentales y eso por varias razones: Poseen unas propiedades matemáticas muy interesantes (por ejemplo con combinaciones de señales senoidales de diferente amplitud y frecuencia se puede reconstruir cualquier forma de onda), la señal que se obtiene de las tomas de corriente de cualquier casa tienen esta forma, las señales de test producidas por los circuitos osciladores de un generador de señal son también senoidales, la mayoria de las fuentes de potencia en AC (corriente alterna) producen señales senoidales.

La señal senoidal amortiguada es un caso especial de este tipo de ondas y se producen en fenomenos de oscilación, pero que no se mantienen en el tiempo.


4. Material y Equipo Requerido

5. Procedmiento 

  Implemente el circuito que se presenta en la figura
  
  
  5.1 Una vez el circuito construido iremos respondiendo los diferentes items que se indican 

6. Resultados



7. Conclusiones y Recomendaciones



8. Bibliografia
  
