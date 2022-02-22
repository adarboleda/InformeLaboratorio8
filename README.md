# InformeLaboratorio8

1. OBJETIVOS

Objetivo General:

* Comprobar experimentalmente las características y el funcionamiento de las señales senoidales mediante un análisis practico y teórico a través de una simulación de medida con la ayuda del DCACLAB.

Objetivos Específicos:  

* Explicar el concepto fundamental de ondas senoidales. 
* Analizar el comportamiento de la señal senoidal en el circuito propuesto utilizando un osciloscopio y un multímetro digital. 

2. MARCO TEÓRICO 

![image](https://user-images.githubusercontent.com/93733175/155142208-dec3b321-45b4-4f1e-9923-51a09186ffd1.png)

3. EXPLICACIÓN DEL PROCEDIMIENTO

**Material y equipo requerido**

![image](https://user-images.githubusercontent.com/93734334/154825345-4ad630ab-d2a0-4b55-ae7e-8830dbbf8029.png)

8.5.1. Implemente el circuito que se presenta en la figura 7.1

![image](https://user-images.githubusercontent.com/93734334/154825360-81d1ea17-285b-45f2-8453-f6c5f1e4811e.png)

8.5.2.. Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.

![image](https://user-images.githubusercontent.com/93734334/154954810-c4d6b36e-0bef-4a4e-8498-26f249545238.png)

8.5.3. Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.

![image](https://user-images.githubusercontent.com/93734334/154854464-edee4b16-9ea1-4d82-8ad1-b95808696540.png)

4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

8.5.4. Responda las siguientes preguntas:

¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

* La amplitud pico abarca 2.3 cuadros aproximadamente.

¿En qué valor está posicionada la perilla VOLTS/DIV? 

* Esta posisionado en el valor de 3v

¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

* Un ciclo completo abarca cuatro cuadros.

¿En qué valor está posicionada la perilla TIME/DIV? 

* Esta posicionado en el valor de 0.1ms.

8.5.5.¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?

Amplitud de voltaje:                                                                                                                                                             
Como cada cuadro equivale a 3V y se observa 2 cuadros y un poco mas entonces da un valor aproximado de 6.8 (V)                                                                                                                                             
Periodo: 

Un ciclo es de 4 cuadros y esto se va a multiplicar po el valor de la perilla TIME/DIV que es de 0.0001 ms                                                                       
4(0.0001) = 0.0004 s                                                                                                                                                             
**T = 0.0004s**

8.5.6. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.

Se va a usar el periodo anteriormente encontrado en la siguiente formula:                                                                                                         
fn = 1/T                                                                                                                                                                         
fn = 1/0.0004                                                                                                                                                                     
**fn: 2500 (Hz)**

ω: 2πf                                                                                                                                                                           
ω: 2π(2500)                                                                                                                                                                       
**ω: 15707,96 (rad/s)**

8.5.7. Con el multímetro digital mida el voltaje de salida en RL: 4.833 V

![image](https://user-images.githubusercontent.com/93734334/154856032-ca124316-e8eb-42d7-b266-46cc4c40bc5e.png)

8.5.8. Compare el voltaje medido en el punto 8.5.5. y el obtenido en el punto 8.5.7.

* No coinciden, esto se debe a que el osciloscopio da el valor del voltaje pico, mientras que el multimetro da un valor eficas es decir Vrms, esto pasa puesto que el multimetro da el 71% del valor del voltjae pico, si se quiere obtener el valor que da el osiloscpoio se debe usar la siguiente formula Vp = Vrms(0.707), reemplazando los valores Vp = 4.833(0.707), nos da Vp = 6.9 V que es el valor que da el osiloscopio.

5. VIDEO

https://youtu.be/UByaQab3O4E

6. CONCLUSIONES
* La onda sinusoidal con respecto  al análisis de circuitos es la representación gráfica del cambio del voltaje o la corriente con respecto al tiempo.
* La señal de onda sinusoidal del osciloscopio muestra un valor de volatje diferente al del multímetro debido a que el voltaje que muestra el osciloscopio es un valor pico y el valor del multímetro indica el 71% aproximadamente del valor del voltaje pico.

7. BIBLIOGRAFÍA

Cajas, D. (01 de septiembre de 2015). Características de la onda senoidal. Obtenido de https://es.slideshare.net/vr3220/caractersticas-de-la-onda-senoidal

ECURED. (12 de agosto de 2021). Onda senoidal. Obtenido de https://www.ecured.cu/Onda_senoidal




RUBRICA

![](https://github.com/doalulema/InformeLaboratorio/blob/main/Laboratorio.png)
