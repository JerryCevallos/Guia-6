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

![WhatsApp Image 2021-03-02 at 12 41 33](https://user-images.githubusercontent.com/75337022/109694310-a7f32380-7b58-11eb-948c-c0f2935cee67.jpeg)


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

  3.2 ¿Como funciona un osciloscopio?

Para entender el funcionamiento de los controles que posee un osciloscopio es necesario deternerse un poco en los procesos internos llevados a cabo por este aparato. Empezaremos por el tipo analógico ya que es el más sencillo.

¿Qué controles posee un osciloscopio típico?
A primera vista un osciloscopio se parece a una pequeña televisión portatil, salvo una rejilla que ocupa la pantalla y el mayor número de controles que posee. En la siguiente figura se representan estos controles distribuidos en cinco secciones:

	** Vertical. 
	** Horizontal. 
	** Disparo. 
	** Control de la visualización. 
	** Conectores.
	
	
  3.3 Tipos de Osciloscopios

    3.3.1 Osciloscopios analógicos
  
  Cuando se conecta la sonda a un circuito, la señal atraviesa esta última y se dirige a la sección vertical. Dependiendo de donde situemos el mando del amplificador vertical     atenuaremos la señal ó la amplificaremos. En la salida de este bloque ya se dispone de la suficiente señal para atacar las placas de deflexión verticales (que naturalmente       estan en posición horizontal) y que son las encargadas de desviar el haz de electrones, que surge del catodo e impacta en la capa fluorescente del interior de la pantalla, en   sentido vertical. Hacia arriba si la tensión es positiva con respecto al punto de referencia (GND) ó hacia abajo si es negativa.
  
  ![analogico](https://user-images.githubusercontent.com/75337022/109572157-c30f5600-7aba-11eb-8b75-32d09185d26f.png)
  
    3.2.2 Osciloscopio digital 
  
  Los osciloscopios digitales poseen además de las secciones explicadas anteriormente un sistema adicional de proceso de datos que permite almacenar y visualizar la señal.Cuando   se conecta la sonda de un osciloscopio digital a un circuito, la sección vertical ajusta la amplitud de la señal de la misma forma que lo hacia el osciloscopio analógico.
  
  ![digital](https://user-images.githubusercontent.com/75337022/109572173-c9053700-7aba-11eb-854a-e3bba7cdb89d.png)
  
  
  3.4 Metodos para medir
   
  Métodos de muestreo
  Se trata de explicar como se las arreglan los osciloscopios digitales para reunir los puntos de muestreo. Para señales de lenta variación, los osciloscopios digitales 	   pueden perfectamente reunir más puntos de los necesarios para reconstruir posteriormente la señal en la pantalla. No obstante, para señales rápidas (como de rápidas dependerá   de la máxima velocidad de muestreo de nuestro aparato) el osciloscopio no puede recoger muestras suficientes y debe recurrir a una de estas dos técnicas:

   - Interpolación , es decir, estimar un punto intermedio de la señal basandose en el punto anterior y posterior.
   - Muestreo en tiempo equivalente . Si la señal es repetitiva es posible muestrear durante unos cuantos ciclos en diferentes partes de la señal para después reconstruir la          señal completa.

    3.4.1 Muestreo en tiempo real con Interpolación

  El método standard de muestreo en los osciloscopios digitales es el muestreo en tiempo real: el osciloscopio reune los suficientes puntos como para recontruir la señal. Para     señales no repetitivas ó la parte transitoria de una señal es el único método válido de muestreo. Los osciloscopios utilizan la interpolación para poder visualizar señales que   son más rápidas que su velocidad de muestreo. Existen basicamente dos tipos de interpolación:

  Lineal : Simplemente conecta los puntos muestreados con lineas. Senoidal : Conecta los puntos muestreados con curvas según un proceso matemático, de esta forma los puntos       intermedios se calculan para rellenar los espacios entre puntos reales de muestreo. Usando este proceso es posible visualizar señales con gran precisión disponiendo de           relativamente pocos puntos de muestreo.

![Interpolacion](https://user-images.githubusercontent.com/75337022/109572197-d02c4500-7aba-11eb-9cc1-2e92a9e0c933.png)

    3.4.2 Muestreo en tiempo equivalente

  Algunos osciloscopios digitales utilizan este tipo de muestreo. Se trata de reconstruir una señal repetitiva capturando una pequeña parte de la señal en cada ciclo.Existen dos   tipos básicos: Muestreo secuencial- Los puntos aparecen de izquierda a derecha en secuencia para conformar la señal. Muestreo aleatorio- Los puntos aparecen aleatoriamente       para formar la señal

![Equivalente](https://user-images.githubusercontent.com/75337022/109572217-d6222600-7aba-11eb-90e9-2a8b75e0d0cb.png)


   3.5 Ondas senoidales en el osciloscopio 

Son las ondas fundamentales y eso por varias razones: Poseen unas propiedades matemáticas muy interesantes (por ejemplo con combinaciones de señales senoidales de diferente amplitud y frecuencia se puede reconstruir cualquier forma de onda), la señal que se obtiene de las tomas de corriente de cualquier casa tienen esta forma, las señales de test producidas por los circuitos osciladores de un generador de señal son también senoidales, la mayoria de las fuentes de potencia en AC (corriente alterna) producen señales senoidales.

![Ondas](https://user-images.githubusercontent.com/75337022/109572230-dc180700-7aba-11eb-9c22-4c5e8ae371f7.png)

La señal senoidal amortiguada es un caso especial de este tipo de ondas y se producen en fenomenos de oscilación, pero que no se mantienen en el tiempo.


4. Material y Equipo Requerido

![Materiales](https://user-images.githubusercontent.com/75337022/109574456-f0a9ce80-7abd-11eb-9bc9-4bc1d50f7b27.png)

5. Procedmiento 

  Implemente el circuito que se presenta en la figura
  
![Diagrama](https://user-images.githubusercontent.com/75337022/109574470-f8697300-7abd-11eb-8881-0e51fa9e85cc.png)
  
  5.1 Una vez el circuito construido iremos respondiendo los diferentes items que se indican

	5.1.1 Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.

	5.1.2 Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.

	5.1.3 Responda las siguientes preguntas: ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?___________
	
	¿En qué valor está posicionada la perilla VOLTS/DIV? ___________
	
	¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?__________
	
	¿En qué valor está posicionada la perilla TIME/DIV? ___________
	
	5.1.4 ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?
	
	Amplitud de voltaje: ____________(V) 
	
	Periodo: ____________(s)
	
	5.1.5 Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.
	
	f: _____________(Hz)
	
	ω: ____________(rad/s)
	
	5.1.6 Con el multímetro digital mida el voltaje de salida en RL: _______________

	5.1.7 Compare el voltaje medido en el punto 7.5.5. y el obtenido en el punto 7.5.7.¿Coinciden? _______ ¿Por qué?

Elaboramos el circuitos en el software 


![Circuito elaborado en Proteus](https://user-images.githubusercontent.com/75337022/109571522-cfdf7a00-7ab9-11eb-8e1e-4c0e1d047e38.jpeg)


Ahora utilizamos el osciloscopio para realizar las respectivas mediciones 

![WhatsApp Image 2021-03-01 at 21 27 55](https://user-images.githubusercontent.com/75337022/109599922-2664ac80-7aea-11eb-8655-28f4120d1914.jpeg)

6. Analisis y Resultados

![Preguntas_page-0001](https://user-images.githubusercontent.com/75337022/109685037-db30b500-7b4e-11eb-8f34-fd366ef99d07.jpg)

![Procedimiento y resolucion_page-0002](https://user-images.githubusercontent.com/75337022/109599746-b524f980-7ae9-11eb-9207-42dc8dea6dd5.jpg)	

![Error](https://user-images.githubusercontent.com/75337022/109705186-7b91d400-7b65-11eb-95b2-0e9dda9dad89.png)


7. Conclusiones y Recomendaciones

• El haz electrónico puede compararse con la parte móvil de un instrumento electromecánico, la desviación de dicho haz, depende de la tensión aplicada a los electrodos desviación.

• La altura de las señales observadas en la pantalla, se gobierna manipulando los controles del bloque vertical.

• El ancho de las señales observadas en la pantalla, se controlan manipulando los controles del bloque horizontal.

• La estabilidad de la imagen en la pantalla se logra manipulando los controles del bloque de sincronismo.

• A pesar de sus múltiples usos, el osciloscopio sirve para dar dos mediciones fundamentales tensión y tiempo.

• El procedimiento de cálculo del valor de la indicación del osciloscopio, es similar al de todos los medios de medición.


8. Bibliografia

- Electricidad del Hogar y Electrónica Facil: https://www.electricasas.com/diferencias-entre-corriente-continua-y-corriente-alterna/

- CORRIENTE DIRECTA Y CORRIENTE ALTERNA: https://www.angelfire.com/empire/seigfrid/Corrientedirectayalterna.html

- GreenFacts: http://www.greenfacts.org/es/glosario/abc/corriente-alterna.htm

- Electronica Facil, El osciloscopio, Recuperado de: https://www.electronicafacil.net/tutoriales/Uso-del-osciloscopio.html


  
