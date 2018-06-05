---
layout: single
title: Plan del proyecto
permalink: /acerca-edar-4-0/plan-proyecto/
sidebar:
 nav: "about"
---

El objetivo de este proyecto es el desarrollo de una plataforma integral de gestión eficiente de una EDAR que permita la medición, análisis y optimización de sus procesos energéticos con el objetivo de minimizar la demanda energética y maximizar la producción eléctrica renovable. Esta plataforma se basará en el desarrollo de nuevos sensores que ayuden a medir las variables críticas de funcionamiento energéticamente óptimo, algoritmos de modelado y control de la EDAR basados en datos y técnicas de visualización analítica para la interacción con el usuario y la realización de auditorías energéticas.

<figure>
  <img src="{{ '/assets/images/project_plan.png' | relative_url }}" alt="Esquema general del proyecto.">
</figure>

En primer lugar, este proyecto diseñará e implementará soluciones para la reducción del consumo energético mediante la mejora de los equipos con un mayor consumo energético soplantes, bombas de impulsión), de las unidades de proceso globales asociadas con el tratamiento del agua residual y del fango resultante de la separación de los sólidos en la línea de aguas, y de la EDAR en su conjunto, mediante el ajuste óptimo de los correspondientes parámetros de operación y control.


Se prestará una especial atención al diseño y operación del sistema de aireación, ya que sus costes suponen un 45-75% de los costes energéticos. La instalación de controles, soplantes energéticamente eficientes y tecnologías de difusores eficientes permitirá reducir los costes energéticos manteniendo la calidad del efluente.


Uno de los principales retos relacionados con la aireación es que no se dispone de información sobre la eficiencia de estos sistemas. Por ello, este proyecto plantea dos soluciones complementarias que refuercen la medición indirecta de los parámetros que miden la eficiencia del sistema de aireación. 


Por un lado, la medida de gases emitidos puede ofrecer información para mejorar la operación de las EDAR. En el proceso biológico de depuración de la EDAR, se producen gases de efecto invernadero que se miden de forma esporádica. En particular, la emisión de N2O puede dar idea de la eficiencia del proceso de aireación y la tasa de absorción de oxígeno, ya que supone que el proceso de nitrificación no se ha completado de forma correcta mientras que el sistema de aireación ha estado funcionando. Por ello, este proyecto plantea una forma de estimación de emisiones y cuantificación del volumen de N2O emitido a partir de la colocación de diferentes tipos de cámaras (termográficas, hiperespectrales), que ayude a detectar posibles ineficiencias en el proceso biológico.


Por otra parte, el sensor de Oxígeno Disuelto (OD) es una de las piezas clave en la optimización energética de la EDAR, ya que el control de la aireación del proceso biológico, proporcionada por las soplantes (más del 50% del consumo de energía eléctrica en la EDAR) se basa en la medida de OD. Por ello, este proyecto implementará sensores matriciales de OD en el agua inalámbricos e inteligentes, y con prestaciones innovadoras, como la integración de un sensor virtual o “soft sensor” en el propio sensor físico, con el fin de atenuar los errores de medida que habitualmente tienen asociados estos sensores. De esta forma, se implementará un control de OD más preciso y eficiente que permitirá aumentar considerablemente la eficiencia energética de la EDAR.

La segunda fuente de consumo energético en la EDAR es el bombeo del agua residual desde la cámara de unión del agua residual bruta a los tanques de, por lo que cualquier mejora en el control de las bombas o la temporización de las operaciones pueden dar lugar a ahorros en la EDAR. Las estrategias mejoradas para el control de los sistemas de bombeo involucran dos tipos de opciones: temporización de las bombas (determinar las bombas que deben operar y el momento) y el control óptimo de la velocidad de las bombas. Para ello, será necesario disponer de modelos de funcionamiento del sistema de bombeo que se basen en el consumo energético y el caudal de agua.

Este proyecto plantea la utilización de técnicas de minería de datos a los modelos de las bombas utilizadas en el tratamiento primario de la EDAR, identificando las relaciones entre el consumo energético, la velocidad del caudal del agua tras el bombeo y la velocidad de las bombas. Establecer modelos precisos para evaluar el comportamiento de los sistemas de bombeo es un reto importante debido a la complejidad del sistema.


En segundo lugar, este proyecto implementará tecnologías que permitan incrementar la producción energética (para autoconsumo o para venta a la red) que se puede obtener en una EDAR, bien sea mediante un proceso de digestión anaerobia de fangos para producción de biogás y metano, o mediante el aprovechamiento térmico de la energía calorífica de fango en un proceso de incineración.


Por un lado, y aunque la tecnología de los motores de combustión interna que operan con biogás está en el mercado y la configuración de parámetros del motor está bien definida, se ha de considerar que las condiciones reales de operación son muy diferentes. Por ello, este proyecto definirá, estudiará y diseñará la tecnología del motor que permita operar con mayores rendimientos y por lo tanto, con una mayor eficiencia. Para ello, se implementarán una serie de algoritmos de control del motor que permitan conocer y modificar el modo de operación del motor sobre la base de la calidad de entrada, optimizando el rendimiento y estimando el porcentaje de CH4 que tiene el biogás. Asimismo, se diseñará un algoritmo que permita un modo de control de emisiones del motor generado.


Igualmente, se modelizará un sistema eficiente de funcionamiento del grupo generador para realizar un análisis económico de la cogeneración en los diferentes escenarios utilizando el sistema Fuel Blending para motores de gas, donde la calidad de la energía de la alimentación de combustible es variable, aunque el cliente es capaz de complementar combustibles de calidad de energía “pobre” con gas natural.


Finalmente, se definirá y diseñará una propuesta especializada de la solución integral en busca de una mejora competitiva y una rentabilidad global de la actividad de cogeneración a nivel de potencia eléctrica y calorífica.


En tercer lugar, este proyecto utilizará todos los datos disponibles en una EDAR para permitir una gestión optimizada de la misma, más allá de una gestión individualizada de los componentes de generación y consumo energéticos. Así, se aplicarán técnicas de modelización avanzadas basadas en datos (data-driven modelling), que evalúen los datos medidos de forma puntual o aquellos recogidos de forma habitual disponibles que permitan mejorar la operación de la EDAR, tanto en aspectos relacionados con el proceso como la eficiencia energética. Los algoritmos serán autocalibrables en el tiempo con un grado alto de replicabilidad y escalabilidad.


De esta forma, se automatizará la generación y desarrollo de modelos y proporcionar una
alternativa de coste eficiente a las aproximaciones existentes, favoreciendo la reutilización de los datos para otros propósitos. Este modelado se abordará a tres niveles según la jerarquía de la automatización y control definido en la ISA-95 (International Standard of Automation): modelos de los equipos energéticamente intensivos de la EDAR.; áreas funcionales que agrupan múltiples equipos (procesos biológicos de depuración de aguas y tratamiento de fangos.) y EDAR global.

Una vez conocidos los modelos, se definirá pautas de operación, control y mantenimiento inteligente para la optimización energética de equipos y procesos de la EDAR y la EDAR en su conjunto. Así, se desarrollarán algoritmos de control basados en modelos basados en datos con capacidad de ofrecer consignas de control MIMO (Multiple Input Multiple Output). Dichos algoritmos tendrán capacidad predictiva y trabajarán con múltiples criterios de operación (criterio de calidad del agua tratada o requerimientos de vertido; criterios de optimización energética; criterio de calidad del aire o requerimientos de emisiones GEI).


Finalmente, para mejorar la interacción de los gestores de las EDAR con los datos, modelos y sistemas de control, se implementarán sistemas de monitorización inteligente e interactiva para la visualización basados en técnicas avanzadas de visualización analítica.