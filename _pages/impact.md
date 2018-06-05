---
layout: single
title: Impacto
permalink: /acerca-edar-4-0/impacto/
sidebar:
 nav: "about"
toc: true
toc_label: Impacto
---

EDAR 4.0 es una plataforma integral de gestión eficiente de una EDAR que permita la medición, análisis y optimización de sus procesos energéticos con el objetivo de minimizar la demanda energética y maximizar la producción eléctrica renovable. Esta plataforma se basará en el desarrollo de nuevos sensores que ayuden a medir las variables críticas de funcionamiento energéticamente óptimo, algoritmos de modelado y control de la EDAR basados en datos y técnicas de visualización analítica para la interacción con el usuario y la realización de auditorías energéticas.

<figure>
  <img src="{{ '/assets/images/project_plan.png' | relative_url }}" alt="Esquema general del proyecto.">
</figure>

EDAR 4.0 incluirá una herramienta de visualización interactiva para la realización de auditorías y certificaciones energéticas de la eficiencia energética de las EDAR. Dicha herramienta será un panel de control a modo de observatorio, que visualizará las variables y criterios de evaluación asociados a los procedimientos de auditoría y certificación energética de la EDAR correspondientes (NORMA ISO 50001). De esta forma, se podrán establecer unas referencias de eficiencia energética óptimas que permitan auditar y certificar las EDAR con mayor precisión que en la actualidad.


Aunque EDAR 4.0 es una plataforma integral para la gestión de toda la planta, se han definido tres niveles de actuación sobre los diferentes elementos de la EDAR según la jerarquía de la automatización y control definido en la ISA-95 (International Standard of Automation): equipos energéticamente intensivos de la EDAR.; áreas funcionales que agrupan múltiples equipos (procesos biológicos de depuración de aguas y tratamiento de fangos.) y EDAR global. Con el fin de clarificar los productos resultantes, se seguirá esta clasificación.


## Nuevos sensores matriciales de Oxígeno Disuelto

El sensor de OD es una pieza clave en la optimización energética de la EDAR. Este
subproducto será un sensor matricial de OD de bajo coste para poder medir en continuo el nivel de OD en las balsas de aireación. Dichos sensores serán matriciales formados por N sensores individuales comunicados inalámbricamente, de modo que se puedan calcular los valores de OD en diferentes puntos de la balsa. El sensor incorporará una lógica para el cálculo de la medida representativa de la balsa sobre la base de la matriz de medidas que proporciona el sensor. El despliegue de N sensores que combinen sus mediciones mientras cubren una parte importante de la superficie de la balsa permitirá ofrecer una solución con una precisión mucho más elevada que las soluciones actuales, con el consiguiente mejora de la eficiencia energética en el uso optimizado de las soplantes. Igualmente, dicho sensor incorporará un sensor virtual basado en un modelo matemático del sensor, que permitirá detectar fallos en las medidas y por lo tanto, mejorar la precisión del sensor. Igualmente, se implementarán tecnologías inalámbricas para evitar el cableado de dichos sensores así como una reducción de los costes de instalación.

## Medidores de N2O basados en técnicas de visión

Este subproducto incluirá un sistema de medida basado en cámaras, probablemente
cámaras demográficas e hiperespectrales, que permitirán cuantificar la totalidad de las emisiones de estos gases. Este nuevo sistema de medición en continuo permitirá controlar el consumo y la eficiencia de la aireación como uno de los mayores consumidores
energéticos de la EDAR. Igualmente, se podrán detectar problemas de deterioro de los difusores del sistema de aireación, ya que un incremento en la emisión de N2O podría ser representativo de un empeoramiento de la eficiencia de los difusores. De esta forma, se complementarán las tareas de mantenimiento de estos difusores con técnicas eficientes frente a la observación visual de la superficie del tanque actual.

## Equipos energéticamente intensivos consumidores de energía

Este subproducto estará orientado a los elementos energéticamente intensivos
consumidores de la EDAR (bombas de impulsión, soplantes del sistema de aireación). Dada su gran influencia en el balance energético final de la EDAR (especialmente en el caso de las soplantes), tiene una gran importancia la correcta modelización de dichos elementos en tiempo real. Para ello, se aplicarán modelos basados en técnicas de minería de datos y aprendizaje automático, que definan el rango de operación óptimo, energéticamente eficiente, de estos equipos. Ahora bien, el rendimiento de estos equipos y por tanto, su eficiencia energética, está condicionada no solamente por su propio diseño y operación, sino también por el diseño y operación global de la EDAR, y de los sistemas y subsistemas auxiliares de dichos equipos. Por ello, se considerarán tanto datos de operación óptima, energéticamente eficiente de los propios equipos, como variables de estado y de operación de la propia EDAR (características de carga contaminante del afluente y las características de calidad de agua del efluente). Estos modelos se calibrarán con datos experimentales, de manera que reproduzcan fielmente el funcionamiento del correspondiente equipo.


Igualmente, este subproducto ofrecerá pautas de operación inteligente para la optimización energética y operacional de los equipos y pautas de mantenimiento inteligente mediante la aplicación de algoritmos basados en aprendizaje automático. El sistema analizará en continuo los datos de funcionamiento de los equipos y variables de estado y operación de la EDAR asociados con el modelo de operación óptima, interpretando el comportamiento y la gestión que se está llevando a cabo de los mismos. Como resultado, se obtendrán un conjunto de indicadores de pautas de operación energéticamente eficientes, y avisos y/o
alarmas de pautas de mantenimiento inteligente.

Los datos de operación de cada equipo se visualizarán de forma inteligente e interactiva en tiempo real, comparando el funcionamiento de cada equipo con sus valores óptimos de operación energéticamente eficiente. El panel de control mostrará los puntos de operación óptimos y eficientes y se generarán avisos y/o alarmas de pautas de mantenimiento y/o de pautas de operación eficiente. Igualmente, el operador podrá visualizar tanto los costes asociados a pérdidas de eficiencia energética, como aquellos asociados a actividades de mantenimiento, de manera que las pautas de mantenimiento incorporen criterios económicos y técnicos. Dado que existe una relación con las propias variables de la EDAR, se mostrará igualmente información útil de otros equipos o áreas funcionales.


## Equipos energéticamente intensivos generadores de energía

Este subproducto se centra en los sistemas de cogeneración, ya que proveerán una fuente de energía renovable a la gestión de la EDAR para conseguir equilibrar el balance energético final de la EDAR. Se han incluido dos líneas de actuación para este subproducto: actuaciones sobre el control del motor de cogeneración y actuaciones sobre el control del sistema de cogeneración en su conjunto y de sus equipos auxiliares.

El sistema permitirá estimar el contenido en CH4 del biogás producido en el proceso de digestión y alimentado al sistema de cogeneración en función de la corrección de la carburación según emisiones de GEI. De esta forma, se garantizará un control más robusto de la carburación y por consiguiente el control de emisiones de GEI, así como hacer más
fiable el funcionamiento del motor. Si el motor de cogeneración funciona con biogás, será necesario conocer con precisión la calidad del biogás (porcentaje de CH4) para el control de la carburación,, con el fin de mantener el nivel de emisiones de GEI establecido. Igualmente, se añadirá un sensor de NOX con objeto de controlar la carburación del motor, y por consiguiente, las emisiones de GEI. Adicionalmente, se implementará un algoritmo de corrección de la eficiencia del motor de cogeneración, con el fin de aumentar la eficiencia energética del sistema de cogeneración.


Al igual que en el caso anterior, los datos de operación de cada equipo se visualizarán de forma inteligente e interactiva en tiempo real, comparando el funcionamiento de cada equipo con sus valores óptimos de operación energéticamente eficiente. El panel de control mostrará los puntos de operación óptimos y eficientes y se generarán avisos y/o alarmas de pautas de mantenimiento y/o de pautas de operación eficiente. Igualmente, el operador podrá visualizar tanto los costes asociados a pérdidas de eficiencia energética, como aquellos asociados a actividades de mantenimiento, de manera que las pautas de mantenimiento incorporen criterios económicos y técnicos. Dado que existe una relación con las propias variables de la EDAR, se mostrará igualmente información útil de otros equipos o áreas funcionales.


## Áreas funcionales

Tal y como se ha definido previamente, las áreas funcionales de una EDAR corresponden a la línea de aguas y la línea de fangos. En primer lugar, este subproducto permitirá un modelado basado en datos de cada área funcional, que permitirá enviar los puntos de operación óptimos y energéticamente eficientes a los equipos subyacentes, tales como las bombas de impulsión y soplantes de la línea de aguas, el sistema de cogeneración o la incineradora. En segundo lugar, los modelos de las áreas funcionales permitirán predecir el consumo energético sobre las condiciones operacionales en tiempo real, principalmente las características del influente, con el fin de contrastar el consumo modelado de la energía con el consumo real, y generar alarmas o avisos en caso de desviaciones fuera del rango óptimo de operación. Finalmente, cada área funcional dispondrá de herramientas de monitorización relacionadas con las variables y sus dependencias en el balance. La utilización de diferentes técnicas de visualización permitirá identificar posibles desviaciones y tendencias de forma temprana. Este panel de control permitirá al operador disponer de una visión integrada de todos los parámetros del área funcional, de modo que puedan analizarse de forma conjunta.


## EDAR global

Este subproducto incluirá modelos basados en datos y pautas de operación y control
inteligente para la optimización energética global de la EDAR bajo el concepto de "Plant Wide Control for Plant Wide Energy Optimization" y servirá como centro de control general para conseguir un funcionamiento eficiente de la EDAR. El modelo de la EDAR se basará en algoritmos que utillicen técnicas de minería de datos y aprendizaje automático. Sobre dicho modelo, se podrán introducir algoritmos de control automático autocalibrables, replicables y escalables a cualquier tipo de configuración de la EDAR. Dichos algoritmos ofrecerán consignas de control con capacidad predictiva, considerando múltiples criterios de operación (calidad del agua tratada o requerimientos de vertido; optimización energética; calidad del aire o requerimientos de emisiones GEI), que integren datos externos a la EDAR como datos meteorológicos, tarifas eléctricas y de gas horarias, y que ofrezcan la posibilidad de alcanzar el óptimo global. Algunos criterios de optimización estarán orientados hacia una optimización económica que minimice el coste de operación, una optimización energética que consiga una autosufiencia energética de la EDAR o una optimización medioambiental que minimice los gases emitidos. Finalmente, el operador de la EDAR dispondrá de un panel de control integrado basado en técnicas de analíticas visuales que incluya los tres niveles de gestión.
