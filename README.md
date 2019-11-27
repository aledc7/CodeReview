![Laravel](https://raw.githubusercontent.com/aledc7/Laravel/master/pirullo.png "Aledc.com")

[![aledc.com](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/aledc.com.svg)](https://aledc.com)
[![ingenea.com.ar](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/ingenea.svg)](http://ingenea.com.ar)
[![License](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/mit-license.svg)](https://aledc.com)
[![GitHub release](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/release.svg)](https://aledc.com)
[![Dependencies](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/dependencias-none.svg)](https://aledc.com)

# Revisión de Codigo


## Diez consejos para guiarlo hacia una revisión efectiva del Código.

1. 
## Revise menos de 400 líneas de código a la vez

Un estudio de SmartBear de un equipo de programación de Cisco Systems reveló que los desarrolladores no deberían revisar más de 200 a 400 líneas de código (LOC) a la vez.  
El cerebro solo puede procesar efectivamente cierta información a la vez; más allá de 400 Lineas de código (LOC) , la capacidad de encontrar defectos disminuye.  

En la práctica, una revisión de 200-400 LOC durante 60 a 90 minutos debería producir un 70-90% de descubrimiento de defectos.  
Por lo tanto, si existían 10 defectos en el código, una revisión bien realizada encontraría entre siete y nueve de ellos.


## Mejores Prácticas de revisión de Código

2. 
## Tómate tu tiempo. 

Las tasas de inspección deben ser inferiores a 500 LOC por hora.   
Puede ser tentador analizar una revisión, suponiendo que otra persona detecte los errores que no encuentra. Sin embargo, la investigación de SmartBear muestra una caída significativa en la densidad de defectos a velocidades superiores a 500 LOC por hora.   
Las revisiones de código en cantidades razonables, a un ritmo más lento durante un período de tiempo limitado, dan como resultado la revisión de código más efectiva.  


3. 
## No revise por más de 60 minutos a la vez.  

Del mismo modo que no debe revisar el código demasiado rápido, tampoco debe revisarlo durante demasiado tiempo de una sola vez.  
Cuando las personas participan en cualquier actividad que requiera un esfuerzo concentrado durante un período de tiempo, el rendimiento comienza a disminuir después de unos 60 minutos.  
Los estudios demuestran que tomar descansos de una tarea durante un período de tiempo puede mejorar en gran medida la calidad del trabajo.  
Realizar revisiones más frecuentes debería reducir la necesidad de tener que realizar una revisión de esta duración.  


4. 
## Establecer objetivos y capturar métricas.

Antes de implementar un proceso, su equipo debe decidir cómo va a medir la efectividad de la revisión de código y nombrar algunos objetivos tangibles.  

Comience con métricas externas. Por ejemplo, "reduzca las llamadas de soporte en un 15%" o "reduzca a la mitad el porcentaje de defectos inyectados por el desarrollo".   
Esta información debería darle una imagen cuantificable de cómo está mejorando su código.  
  "Arreglar más errores" no es un objetivo efectivo.

También es útil para ver métricas de procesos internos, que incluyen:

  - Tasa de Inspección: la velocidad con la que se realiza una revisión.  
  - Tasa de defectos: la cantidad de errores encontrados por hora de revisión.  
  - Densidad del defecto: el número promedio de errores encontrados por línea de código.  
  
Siendo realistas, solo los procesos automatizados o estrictamente controlados pueden proporcionar métricas repetibles.    
Una herramienta de revisión de código basada en métricas recopila datos automáticamente para que su información sea precisa y sin prejuicios humanos.   

5. 
## Los Programadores autores deben comentar el código fuente antes de la revisión. 

Los autores deben comentar el código antes de que ocurra la revisión porque las anotaciones guían al revisor a través de los cambios, mostrando qué archivos deben examinar primero y defendiendo la razón detrás de cada modificación del código.  
Las anotaciones deben dirigirse a otros revisores para facilitar el proceso y proporcionar más profundidad en el contexto.  
Como beneficio adicional, el autor a menudo encontrará errores adicionales incluso antes de que comience la revisión de código.  
Más errores encontrados antes de la revisión de código producirán una menor densidad de defectos porque existen menos errores en general.  

6. 
## Use Listas de Verificación (Checkbox)

Es muy probable que cada persona en su equipo cometa los mismos 10 errores una y otra vez.  Las omisiones en particular son los defectos más difíciles de encontrar porque es difícil revisar algo que no está allí.  
Las listas ckeckbox son la forma más efectiva de eliminar errores cometidos con frecuencia y combatir los desafíos de encontrar omisiones.
 Las listas de verificación de revisión de código de tipo ckeckbox también brindan a los miembros del equipo expectativas claras para cada tipo de revisión y pueden ser útiles para realizar un seguimiento con fines de informes y mejora de procesos.  

7. 
## Establecer un proceso para reparar los defectos encontrados. 

Incluso después de optimizar los procesos de revisión de código mediante revisiones de boxeo de tiempo, limitando el LOC revisado por hora y nombrando las métricas clave para su equipo, todavía falta un paso clave de revisión.  

## ¿Cómo se solucionarán los errores? 

Parece obvio, pero muchos equipos no tienen un método sistemático para corregir los errores que han trabajado tan duro para encontrar.

La mejor manera de garantizar que los defectos se corrijan es utilizar una herramienta de revisión de código colaborativa que permita a los revisores registrar errores, discutirlos con el autor y aprobar cambios en el código.  
Sin una herramienta automatizada, es probable que los errores encontrados en la revisión no se registren en el sistema de seguimiento de defectos habitual del equipo porque se encuentran antes de que se envíe el código al control de calidad.  


8. 
## Fomentar una cultura positiva de revisión de código.

La revisión de código puede ejercer presión sobre las relaciones interpersonales en equipo. Es difícil que los pares critiquen cada pieza de trabajo y que la gerencia evalúe y mida la densidad de defectos en su código.
 Por lo tanto, para que la revisión del código  sea exitosa, es extremadamente importante que los gerentes creen una cultura de colaboración y aprendizaje en la revisión de código.  

Si bien es fácil ver los defectos como puramente negativos, __cada error es en realidad una oportunidad__ para que el equipo mejore la calidad del código.
 La revisión de código también permite a los miembros del equipo junior aprender de los líderes senior e incluso de los programadores más experimentados para romper los malos hábitos.

Los defectos encontrados en la revisión de código no son una métrica aceptable para evaluar a los miembros del equipo. 
 Los informes extraídos de revisiones de código nunca deben usarse en informes de rendimiento.   
 Si las métricas personales se convierten en una base para la compensación o la promoción, los desarrolladores se volverán hostiles hacia el proceso y, naturalmente, se centrarán en mejorar las métricas personales en lugar de escribir un mejor código general.  
 

9. 
## Acepte la Revision de código como algo naturar y parte del proceso de codificar.

El conocimiento de que otros examinarán su trabajo naturalmente lleva a las personas a producir un mejor producto.  
Este "Ego Effect" naturalmente incentiva a los desarrolladores a escribir un código más limpio porque sus compañeros lo verán.   El estudio SmartBear de Cisco Systems encontró que la "verificación puntual" del 20% al 33% del código resultó en una menor densidad de defectos con un gasto de tiempo mínimo. 
Si su código tiene una probabilidad de 1 en 3 de ser llamado para su revisión, eso es un incentivo suficiente para verificar su trabajo.

10. 
## Practica revisiones de código livianas

Existen muchas formas de revisar el código de forma colaborativa. Sin embargo, para optimizar completamente el tiempo de su equipo y medir efectivamente sus resultados, se recomienda un proceso ligero y asistido por herramientas.

El estudio SmartBear de Cisco Systems descubrió que la revisión de código liviana toma menos del 20% del tiempo de las revisiones formales y encuentra la misma cantidad de errores. 

La inspección formal o de peso pesado promedia nueve horas por 200 LOC. Si bien a menudo es efectivo, este proceso rígido requiere hasta seis participantes y horas de reuniones tediosas.  


Fuente:

smartbear  .com /learn/code-review/best-practices-for-peer-code-review/



