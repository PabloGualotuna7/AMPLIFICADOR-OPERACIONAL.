# AMPLIFICADOR-OPERACIONAL.

### 1. PLANTEAMIENTO DEL PROBLEMA

El problema de esta práctica es verificar el principio de funcionamiento de un amplificador operacional, analizar algunas aplicaciones básicas con el amplificador operacional y familiarizarse con el uso de instrumentos de medida, para todo esto, debemos tomar en cuenta conocimientos previos impartidos en clases, donde se dio reconocimiento de varios amplificadores operacionales y su funcionamiento. Se reconocerá la manera correcta de conexión en el simulador Proteus, y se realizara la comparación con los resultados teoricos obtenidos.

### 2. OBJETIVOS

* Verificar el principio de funcionamiento de un amplificador operacional.

* Analizar algunas aplicaciones básicas con el amplificador operacional.

* Familiarizarse con el uso de instrumentos de medida.

### 3. MARCO TEÓRICO 

### 4. DIAGRAMAS

Circuitos a analizar

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL./blob/master/img/Diagramas%20circuitos.jpg)

Figura 1.

Circuito 1 realizado en Proteus

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL./blob/master/img/Circuito%201.png)

Figura 2.

Circuito 2 realizado en Proteus

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL./blob/master/img/Circuito%202.png)

Figura 3.

Circuito 3 realizado en Proteus

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL./blob/master/img/Circuito%203.png)

Figura 4.

Medición del circuito 1 obtenido en el osciloscopio

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL./blob/master/img/Medida%20c1.png)

Figura 5.

Medición del circuito 2 obtenido en el osciloscopio

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL./blob/master/img/Medida%20c2.png)

Figura 6.

Medición del circuito 3 obtenido en el osciloscopio

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL./blob/master/img/Medida%20c3.png)

Figura 7.

### 5. LISTAS DE COMPONENTES

| Cantidad | Materiales |
| --- | --- |
| 1 | Generador de señales |
| 1 | Osciloscopio |
| 3 | Resistencia |
| 1 | Capacitor | 
| 3 | Amplificadores operacionales|

### 6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Todas las caracteristicas de los circuitos que se analizaron son importante, puesto que, son las bases para para la completa fundamentación de la tecnología de los circuitos amplificadores operacionales. Los 5 que terios básicos que describen el amplificador y son fundamentales, y a partir de esto se desarrollan los 3 principales aximass de la teoría de los amplificadores operacionales los cuáles son:

1.-La atención de entrada diferenciales nula. 

2.-No existe flujo de corriente ninguno de los terminales de entrada. 

3.-En bucle cerrado la entrada negativa será regulada al potencial entrada positiva o de refencia.

* Pasos a seguir durante la practica:

1.- Construir en el simulador cada uno de los circuitos de la figura 1. Muestre
simultáneamente las señales de entrada y salida en un osciloscopio.

2.- Determinar y analizar la relación entre las señales de entrada y salida en cada uno de los circuitos indicados en la figura 1.

3.-Mostrar resultados gráficos.

### 7. ANALSIS DE RESULTADOS

Analice y compare las formas de onda obtenidas en la práctica con los resultados obtenidos en el trabajo preparatorio. Comente dicha comparación.

* Analisis del circuito 1

Las ondas tanto de salida como las de entrada son senoidales en los dos casos, y se
pueden observar que están amplificadas, se dice que se obtuvo el mismo resultado tanto en la simulación como en la práctica analizando las señales de salida y entrada, de todo esto se puede destacar que utilizamos un amplificador operacional inversor, ya que la señal se invierte y se amplifica a la vez dando el resultado esperado trabajado en el preparatorio

* Analisis del circuito 2

Las ondas de salida y de entrada, al ser simuladas y obtenidas experimentalmente en
la sumulación son las mismas, en los dos casos las ondas poseen cierta inclinación que puede ser interpretada como una onda triangular no formada, ya que los capacitores no poseen 1uF. Gracias a estas ondas se pudimos darnos cuenta que el amplificador utilizado es un integrador inversor, ya que ingresando una onda tipo cuadrada obtenemos una onda tipo cuadrada mismo, pero con cierto desfase.

* Analisis del circuito 3

En el circuito 3 se pueden observar que ambas ondas son senoidales, usando el simulador Proteus. La obtención de estas ondas nos permite identificar que el amplificador es sumador inversor. Este amplificador permite añadir algebraicamente dos (o más) señales o voltajes para formar la suma de dichas señales en este caso en la señal de salida. Se pudo notar la suma modificando los valores de frecuencia.

###### Los calculos visualizar en la sección de Anexos.

### 8. PREGUNTAS

##### 8.1 Anote parámetros técnicos importantes de un amplificador operacional que deben ser tomados en cuenta al momento de utilizarlos en un proyecto.

* Tensión de alimentación (V+ y V-): Es la tensión de alimentación máxima permitida que puede aplicarse con seguridad al amplificador. Aunque se designa como estándar 15 V de alimentación, la mayoría de los AO integrados operan sobre un amplio rango de potenciales, algunos van desde valores tan bajos como 1 V, y otros hasta 40 V.

* Rango de Temperatura de operación (Tor): Es el rango de temperatura dentro del cual el dispositivo funcionar con las especificaciones mostradas.

* Tensión de entrada diferencial (Vid): Es la tensión máxima que puede aplicarse con seguridad entre los terminales de entrada diferencial sin flujo excesivo de corriente. Estos valores son variables, los AO con entrada cascodo pn p/n pn soportan hasta 30 V, similares a los AO con entrada FET.

* Voltaje de entrada en modo común (Vcm): Es el rango de voltaje que se puede aplicar en ambas entradas respecto a tierra.

* Consumo de potencia (Pc): Es la potencia requerida para operar el AO o la potencia consumida por el AO con propósitos de polarización. Se especifica para 15 V.

* Disipación de potencia (PD): Es la potencia que un dispositivo particular es capaz de disipar con seguridad en forma continua mientras opera dentro de un rango de temperatura específico. Esta característica varía de acuerdo al tipo de encapsulado. Por ejemplo, los encapsulados cerámicos permiten una alta disipación de potencia, los metálicos permiten la siguiente más alta disipación, en cambio los de plásticos tienen la más baja. Un valor típico es de 500 mW

##### 8.2 Investigue las características de amplificadores operacionales distintos a los utilizados en esta práctica.

##### Amplificador Operacional No Inversor
Este circuito es muy parecido al inversor, la diferencia es que la señal se introduce por el terminal no inversor, lo cual va a significar que la señal de salida estará en fase con la señal de entrada y amplificada. El análisis matemático será igual que en el montaje inversor. la ganancia de éste amplificador no puede ser menor que 1. la corriente de entrada al operacional es cero, por lo tanto I1 es igual a I2. tiene una ganancia en tensión Av = 1 + R1 / R2 . Esto quiere decir que la salida será Av veces la entrada, sin invertirse la señal ya que Av es positiva.

##### Amplificador Operacional Diferencial
Este dispositivo nos permite obtener la derivada de la señal de entrada. En el caso general la tensión de entrada variará con el tiempo Vi=Vi(t). La principal diferencia que se observa en este circuito es la presencia de un condensador de capacidad constante C. Como se sabe la carga Q que almacena un condensador es proporcional a su capacidad C y a la diferencia de potencial V a la que estén sometidos las armaduras de éste (Q=CV). Es fácil entender que si la tensión varía con el tiempo y la capacidad del condensador es constante, la carga que éste almacena también variará con el tiempo, Q=Q(t).

##### Amplificador Sumador No inversor
Tiene múltiples entradas en el pin no inversor. Al igual que en un sumador inversor cada entrada tiene su propia impedancia de entrada que esta por el orden de 100 Mega
Ohmios o más y solo hay una impedancia de salida que esta por el orden de mili Ohmios o menos.

##### Amplificador Operacional Seguidor de Voltaje
Este amplificador hace que la salida siga a la entrada, es decir el voltaje de salida es el mismo voltaje de entrada. Al presentar una alta impedancia de entrada (por el orden de Megas de Ohm o más), se garantiza una baja potencia de entrada, que a su vez garantiza que la señal de entrada no se distorsionara al conectarse al pin no inversor, y además que la señal de entrada quedara en su totalidad en la impedancia de entrada. Al presentar una muy baja impedancia de salida (por el orden de milis de Ohm) se garantiza que haya una transferencia total de potencia a la RL de salida. Por esta razón al Opamp seguidor también se le conoce como buffer y se usa para acoplar impedancias.

##### 8.3 Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales.

##### Amplificador de instrumentación
Este es un amplificador diferencial que consta de dos etapas, una etapa de entrada
formada por dos amplificadores inversores, y una etapa de salida que es un amplificador
diferencial. Resuelve todos los inconvenientes que se presenta en el amplificador
diferencial. 

Esquema de un circuito con Amplificador de instrumentación.

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL./blob/master/img/Imagen.png)

Figura 8.

Dentro de este tipo de aplicaciones se puede encontrar los Amplificadores para Señales de Biopotenciales

### 9. CONCLUSIONES 

* Un amplificador operacional actúa de diferente manera, dependiendo de los elementos a las cuales estén conectados, es decir, si existen elementos resistivos, la
amplitud de la onda de salida aumenta, pero si está conectado un capacitor, entonces su amplitud cada vez será menor. También depende mucho del tipo de onda de entrada, ya que
se derivara o integrara la corriente de salida, en el caso de los cosenos, solo se desplazan 90º, por lo que solo se notara mejor en funciones lineales.

* En la práctica, pudimos com'render el principio de funcionamiento de los amplificadores operacionales, con la ayuda de la fundamentación teorica, y de los data sheet de los amilificadores los cuales nos daban información sobre la distribución de los pines y ciertas características, como por ejemplo que los voltajes maximos que se puede aplicar es de 15V.

* Llegamos a la conclusión que una de las utilidades basicas de los amlidicadores operacionales, son la de realizar operaciones matematicas en computadores analitícos, las características operativas, como por ejemplo, suma, resta, multiplicación, división, etc.

* Comprendimos, que en los circuitos realizados con los amplificadores, la señal de entrada no puede ser igual a la señal de salida, esto quiere decir eue en el circuito existe alguna falla o que el amplificador esta averiado, ya que no esta cumpliendo su función operacional.

### 10. RECOMENDACIONES 

* Se debe verificar que el amplificador operacional este polarizado, que este conectado de forma correcta.

* Es fundamental revisar la hoja técnica de cada amplificador para verificar la función de cada pin, en este laboratorio se puede ver la importancia de esto.

### 11. CRONOGRAMA

Actividades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL./blob/master/img/Cronograma.png)

### 12. BIBLIOGRAFÍA 

Alexander, C, & Sadiku, M. (2006). Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. (2011). Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
