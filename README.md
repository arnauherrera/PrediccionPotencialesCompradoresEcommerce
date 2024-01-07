# Predicción de potenciales compradores de un ecommerce
Este repositorio recoge los html de los notebooks del proyecto "Predicción de potenciales compradores de un ecommerce" de la Universitat Oberta de Catalunya (UOC).

Este conjunto de notebooks han sido construidos a lo largo de todo el proceso del desarollo, iterando y añadiendo mejoras durante todo el proceso. Para que fuera más manejable todo el proyecto, se ha estructurado de esta forma para que no se tuviera que ejecutar todo cada vez, definiendo un conjunto de fases estructuradas en los notebooks.

Los tres primeros notebooks representan el primer ciclo, en el cual se recoge un subconjunto de atributos y se desarrolla todo el ciclo del dato desde la limpieza hasta la obtención del mejor modelo. Se ha querido proceder de esta forma para enfocar los esfuerzos en cada paso, sin perder la noción de los objetivos por querer abarcar todas las posibilidades en la primera etapa. Estos tres notebooks son los que asientan las bases de todos los pasos, por lo que se obtienen:

* Lectura de los datos, limpieza, análisis exploratorio y creación del primer dataset.

* Estudio de técnicas para tratar el conjunto de datos desbalanceados.

* Estudio de modelos: Conjunto de datos del primer ciclo.


Posteriores notebooks enriquecen el conjunto de datos con nuevos atributos y exploran cómo afecta en el modelo final.

* Mejoras en el dataset.

* Estudio Modelos: Conjunto de datos refinado.

Se utiliza pyspark para la lectura y manipulación de los datasets por facilidad en su uso, ya que es el que suelo utilizar diariamente en mi entorno laboral, por lo que en cada notebook se inicia una sesión de spark para poder utilizarlo.
