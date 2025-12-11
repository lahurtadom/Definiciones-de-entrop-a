# Definiciones de Entropía

## 1. Entropía en Termodinámica
En 1824, Leonard Sadi Carnot publico los resultados de un estudio sobre la eficiencia de las maquinas de vapor, para que posteriormente en una reseña de su articulo, Rudolf Clausius introdujiera una nueva propiedad termodinamica que relacionara el flujo de calor espontáneo que ocurre durante un proceso, a la temperatura en la que se desarrolla dicho proceso. Esta propiedad se definió como la relación entre el calor reversible (qrev) y la temperatura absoluta (T) medida en kelvin. Notese que la idea de un proceso reversible es un formalismo requerido para sostener varios conceptos termodinamicos, puesto que no hay un proceso realmente reversible, sino que se clasifican como irreversibles.


**Fórmula básica:**
dS = dQ_rev / T

**Ejemplos:**
Si se añaden 30,0 J de calor al agua que está a 12 °C, ¿cuál es el cambio de entropía?

Datos
*Calor añadido: Q=30,0J
*Temperatura: T= 12ºC

Ds=30,0J/(12+273,15)=0,105J/K


¿Cuál es el aumento de entropía cuando 3,00 kg de hielo a 0 °C se funden para formar agua a 0 °C?

Datos
*Masa del hielo : 3,00Kg
*Temperatura:0ºC
*Calor latente de fusion del hielo: Lf=333x10^3 J/kg

qrev=mxLf

qrev= 3,00Kg x 333000 J/Kg

Ds= 999000J/(0+273,15)
Ds= 3,66x10^3 J/K

**Referencias**
https://openstax.org/books/chemistry-2e/pages/16-2-entropy
https://www.tec-science.com/thermodynamics/heat/specific-heat-of-fusion-and-heat-of-solidification-latent-heat
https://openstax.org/books/physics/pages/12-3-second-law-of-thermodynamics-entropy
https://satheejee.iitk.ac.in/article/chemistry/chemistry-latent-heat-of-fusion

---

## 2. Entropía en Termodinámica estadistica

para poder dar una definicion de microestado, partamos de qué es un macroestado. El macroestado de un sistema químico es aquel que contiene la cantidad de materia suficiente como para poder medir su volumen, presión o temperatura. Por el contrario, podemos definir un microestado como aquel que no solo cuenta con menor materia, sino que además se trata de una visión detallada de la energía y tiempo que poseen las moléculas u otras partículas. Tomemos en consideración un sistema cualquiera. En este hay una redistribución constante de energía entre las partículas que lo componen. Para sistemas compuestos por líquidos o gases las partículas no solo se redistribuyen constantemente en su ubicación, sino que también cambian su energía de forma discreta, en múltiplos de una unidad mínima fundamental (cuantos) debido a sus frecuentes colisiones, haciendo que estas reboten unas con otras, generalmente con una cantidad de energía diferente cada molecula tras lal colisión. Cada forma específica, cada disposición de la energía de cada molécula en todo el sistema en un instante se llama microestado. Un microestado es, entonces, algo así como una "foto absolutamente instantánea" teórica de la ubicación y el momento de cada molécula y átomo en todo el macroestado. En el siguiente instante, el sistema cambia inmediatamente a otro microestado. (Una molécula que se mueve a una velocidad media de alrededor de mil millas por hora choca con otras unas siete veces en una milmillonésima de segundo. Considerando un mol de moléculas (6,022x10^23) viajando a un número muy grande de velocidades diferentes, las colisiones ocurren — y por tanto los cambios de energía de billones de moléculas — en mucho menos de una billonésima de segundo. Por eso es sensato hablar en términos de "un instante". Lo anterior de puede calcular con la siguiente formula:

**Fórmula básica:**

W=e^S/Kb
 Donde: S es la entropía del sistema, Kb es la constante de Boltzmann, W es el número de microestados posibles del sistema

 **Ejemplos:**
 1. Imagina una configuracion de un tablero de ajedrez: 
Macroestado: "Tablero con 2 torres negras y 1 rey blanco".
Microestados: Cada colocación específica de esas 3 piezas en casillas distintas es un microestado diferente.
* Microestado 1: Torre1 en a1, Torre2 en h8, Rey en e5.
* Microestado 2: Torre1 en a1, Torre2 en h7, Rey en e5.
* ... y todas las demás combinaciones de posiciones válidas.
W sería el número total de formas de colocar esas 3 piezas en las 64 casillas sin superponerse.

2. El agua líquida a la misma temperatura que el hielo, 273 K, tiene una entropía de 63,3 J/K. Por lo tanto, hay 10^1,991,000,000,000,000,000,000,000 Microestados accesibles para el agua.

**Referencias**
https://chem.libretexts.org/Bookshelves/Physical_and_Theoretical_Chemistry_Textbook_Maps/Supplemental_Modules_(Physical_and_Theoretical_Chemistry)/Thermodynamics/Energies_and_Potentials/Entropy/Microstates
https://es.paperblog.com/microestados-y-entropia-quimica-1780318/

---
## 3.Entropia como calidad de la informacion.
La transmisión de la información se basa en la teoría de la comunicación, la cual se relaciona directamente con el concepto de entropía. La entropía es una medida de la calidad de la información, ya que indica el grado de incertidumbre, complejidad o novedad que contiene un mensaje. A mayor entropía, mayor es el desorden y, por lo tanto, mayor es el valor informativo; a menor entropía, mayor es el orden y menor la información. Esto resulta clave para determinar la calidad informativa del mensaje. 

**Fórmula básica:**
H=−∑Pi​*log2​(pi​)

donde H representa la entropía del sistema, (Pi) es la probabilidad de que ocurra cada símbolo o mensaje, y el logaritmo en base 2 se emplea porque la entropía se mide en bits. El signo negativo asegura que el valor de la entropía sea positivo. Shannon definió esta ecuación considerando un sistema binario —es decir, con dos opciones posibles—, de ahí el uso del logaritmo base 2. El resultado de H indica cuántos bits se necesitan, en promedio, para describir o transmitir un mensaje.
**Ejemplos:**
Por ejemplo, la secuencia “BBBBBB” es predecible y estructurada, lo que genera una baja entropía; en cambio, la cadena “8N3P9X” es no secuencial y compleja, lo que produce una alta entropía.
**Referencias**
http://www.scielo.org.co/scielo.php?script=sci_arttext&pid=S0124-59962011000200009

---
## 4.Entropia como entrelazamiento de la informacion.
La entropía de entrelazamiento es una medida cuantitativa (un número) que cuantifica la incertidumbre o la falta de información sobre el estado cuántico definido de un subsistema, debido exclusivamente a que está entrelazado con otro subsistema. Se denota comúnmente como S sub a.
En términos más sencillos: cuando dos partículas (o sistemas) están entrelazadas, no puedes describir el estado de una de ellas por separado con certeza. La entropía de entrelazamiento mide precisamente "cuánta" de esa incertidumbre existe. A mayor entropía de entrelazamiento, mayor es el grado de conexión cuántica y la información compartida entre los subsistemas.
Si un subsistema A está (posiblemente) enredado con algún otro subsistema B, la información necesaria para calcular todos los resultados de las mediciones parciales en A se almacena dentro de un operador de densidad reducida

**formula**
SA=−kbTrA{ρ^Aln[ρ^A]}

donde: Sa es la cantidad de incertidumbre sobre el estado de A debido a su entrelazamiento con el sistema, Kb es la constante de Boltzmann, la traza TrA suma los elementos diagonales para obtener un número escalar, y el operador ρA es la matriz de densidad reducida que describe el estado cuántico "promediado" de A, obtenido al ignorar 
el sistema con el que está entrelazado.
**ejemplos**
1. Cajas de Calcetines (Sin Entrelazamiento)
Abres tu caja y ves un calcetín rojo. Como sabías desde el principio que la otra caja tenía uno azul y no había conexión entre ellas, no te llevas ninguna sorpresa. La entropía es cero, igual que cuando escuchas una canción que ya te sabes de memoria palabra por palabra.

2. Guantes Gemelos (Entrelazamiento Máximo)
Tienes un par de guantes (izquierdo y derecho) repartidos en dos cajas. Al abrir la tuya, hay un 50% de ver cualquiera de los dos: es la máxima sorpresa posible. Pero en el instante en que ves, por ejemplo, el izquierdo, sabes con certeza absoluta que en la otra caja está el derecho. La entropía es máxima, como el momento de incertidumbre justo antes de que caiga una moneda lanzada al aire.
**Referencias**
https://phys.libretexts.org/Bookshelves/Quantum_Mechanics/Quantum_Mechanics_III_(Chong)/03%3A_Quantum_Entanglement/3.07%3A_Entanglement_Entropy#:~:text=El%20concepto%20de%20entrop%C3%ADa%20de%20entrelazamiento%20busca%20cuantificar%20la%20incertidumbre,la%20elecci%C3%B3n%20de%20la%20medici%C3%B3n
---
## 5.Entropía como Función Termodinámica dependiente de la Dimensionalidad.
La entropía puede analizarse como una medida para describir un sistema; esta medida depende de la dimensionalidad de dicho sistema. Este enfoque se relaciona con el principio holográfico, que expresa que toda la información dentro de un volumen puede representarse en la superficie que lo delimita. Por lo tanto, la entropía de un sistema aumenta con el área de la frontera del sistema, mas no con el volumen. 
**formula**
Smax=  A/4*lp^2   

donde: Smax se refiere a la entropía máxima del sistema; A es el área de frontera; la D es la dimensión espacial del volumen; lp  es la longitud de Planck  y está elevado a la 2 porque depende solo de la frontera de dimensión  D-1, es decir, 2.

**ejemplos**
Un patrón notable es el de los agujeros negros; la entropía de estos es proporcional al área del horizonte de eventos y no al volumen interno de estos. Esto concuerda con el principio holográfico, con la información requerida para determinar la organización del  universo.

**Referencias**
[https://phys.libretexts.org/Bookshelves/Quantum_Mechanics/Quantum_Mechanics_III_(Chong)/03%3A_Quantum_Entanglement/3.07%3A_Entanglement_Entropy#:~:text=El%20concepto%20de%20entrop%C3%ADa%20de%20entrelazamiento%20busca%20cuantificar%20la%20incertidumbre,la%20elecci%C3%B3n%20de%20la%20medici%C3%B3n](https://iniat.ibero.mx/blog/la-entropia-los-hoyos-negros-y-la-teoria-de-la-informacion/) 

## 6. Segunda ley de la termodinamica.
En la búsqueda de una propiedad que pueda predecir de forma confiable si un proceso será espontáneo, la entropía parece ser una buena candidata. Muchos procesos en los que la entropía del sistema aumenta (ΔS > 0) suelen ser espontáneos; sin embargo, también hay muchos casos donde esto no ocurre. Para tener una idea más completa, es necesario considerar no solo los cambios de entropía del sistema, sino también los de los alrededores. Si juntamos ambos, estamos considerando todo el universo, por lo que se cumple lo siguiente.
**Fórmula básica:**
ΔSuniv=ΔSsys+ΔSsur

**donde**
___
**ΔS_univ**

Es el cambio de entropía del universo.
El “universo” en termodinámica se define como:
universo = sistema + alrededores.
Indica si un proceso es espontáneo, no espontáneo o está en equilibrio.

**ΔS_sys**
Es el cambio de entropía del sistema, o sea, del objeto o proceso que estamos estudiando.
Puede aumentar o disminuir dependiendo de si el sistema absorbe o libera energía en forma de calor.

**ΔS_surr**
Es el cambio de entropía de los alrededores, es decir, todo lo que rodea al sistema.
También cambia cuando hay flujo de calor hacia o desde el sistema.
**Ejemplos:**
Un buen caso son las estrellas las cuales son cumulos de masa y energia, su entorno alrededor es frio y vacio por lo que la tendencia de las estrellas es liberar esta energia en forma de ondas y calor, esta energia se libera y se expande a través del cosmos hasta que se vuelve difusa y pierde su utilidad, esto hace que incremente la entropia.
**Referencias**
https://openstax.org/books/chemistry-atoms-first-2e/pages/12-3-the-second-and-third-laws-of-thermodynamics


