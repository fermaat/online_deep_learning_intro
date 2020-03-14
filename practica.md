# Evaluación de la  Asignatura

El alumno podrá elegir **uno** de los siguientes temas para realizar la tarea correspondiente al módulo de Deep Learning:

- Uso de redes recurrentes para predicción en series temporales
- Uso de un modelo preentrenado para su afinado en un dataset de clasificación de imágenes.

En ambos casos los criterios de evaluación (0-10) pueden resumirse en los siguientes puntos:
- Análisis exploratorio de los datos (1.5 puntos): Consiste en un breve vistazo a los datos proporcionados.
- Metodología (2puntos): Se valorará si el alumno comprende los conceptos de los tipos de dataset y es capaz de generar un modelo de acuerdo con la metodología propia de Machine Learning
- Explicabilidad y reproductibilidad (1.5 punto): Se valorará si el alumno entiende los conceptos y es capaz de explicarlos. También si los expeerimentos pueden reproducirse
- Construcción y entrenamiento del modelo (5 puntos) Se evaluarán las técnicas empleadas y el nivel de acierto en el dataset elegido.


## Redes recurrentes para predicción en series temporales:

Esta prueba consiste en la predicción de la variable objetivo (nivel de ozono elevado o no). Se trata de un problema de clasificación binaria, tal y como está descrito [aquí](http://archive.ics.uci.edu/ml/datasets/Ozone+Level+Detection)
El dataset puede ser descargado de esta página, pero al alumno se le proporcionará también una versión en csv, en la que la variable objetivo estará marcada como 'target'. Dicho dataset estará en el repositorio, en la ruta datasets/practica/ozone.csv

#### Objetivo

Se trata de crear un modelo de red recurrente que prediga esta variable, de forma análoga a lo hecho en clase con otro dataset. Se valorará un análisis exploratorio moderado, si bien no se requerirá uno exhaustivo.

## Uso de transferencia de conocimiento para la clasificación de un dataset pequeño

En este caso se proporcionará a los alumnos un dataset pequeño de imágenes con tres categorías de osos: 'grizzly', 'teddy' y 'black'. Dicho dataset estará en el repositorio de código, en la ruta datasets/practica/osos.tar Los alumnos emplearán una red preentrenada que afinarán con este dataset, de manera similar a la vista en clase para otros dataset.

#### Objetivo

El objetivo de esta práctica es que los alumnos reentrenen un modelo de tipo convolucional para emplear el conocimiento de una red entrenada en un dataset mayor, pero en este caso en un dataset local.


