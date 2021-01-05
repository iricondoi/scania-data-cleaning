# scania-data-cleaning
Data cleaning and analysis on Scania failures dataset, as part of UOC Master in Data Science

### Autores

Iván Jiménez (https://github.com/96garciaivan/)
Itziar Ricondo (https://github.com/iricondoi/)

## Acerca de este software

* Este software es parte de la Práctica 2 de la asignatura: "Tipologia y ciclo de vida de los datos".
* Asignatura: Tipologia y ciclo de vida de los datos.
* Master de Data Science.
* [Universitat Oberta of Catalunya.](http://www.uoc.edu/portal/ca/index.html)
* Consultora: Mireia Calvo Gonzalez

## Dataset

Este conjunto ha sido proporcionado por la empresa Scania y está disponibles en el repositorio UCI Machine Learning Repository:
[https://archive.ics.uci.edu/ml/datasets/APS+Failure+at+Scania+Trucks]

## Licencia

El contenido de este proyecto esta licencia bajo la [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/), 

## Resumen

Este trabajo se ha realizado en el contexto de la asignatura Tipología y Ciclo de Vida del Dato, correspondiente al máster en ciencia de datos de la UOC.

Este conjunto de datos contiene datos de uso de camiones de gran tonelaje de Scania. El caso de estudio se centra en el Sistema de Aire a Presión (APS, del inglés Air Pressure System), sistema responsable de proveer de aire comprimido a varias de las funciones del camión, como el freno o embrague. Los casos con clase positiva son fallos de componentes relacionados con el sistema APS. Por el contrario, los caos con clase negativa corresponden a fallos de componentes no relacionados con el APS. El conjunto de datos presenta casos de ambos tipos, si bien es cierto que los casos negativos son mucho más frecuentes.

El objetivo del conjunto de datos es predecir qué tipo de fallos tienen su origen en el sistema APS y cuáles son debidos a otras causas. Este hecho tiene repercusión en las revisiones o reparaciones a realizar sobre el camión. De hecho, la bondad de la predicción se medirá en términos de coste.

Se ha realizado la limpieza del conjunto de datos y su análisis. En la fase de análisis, se han utilizado el árbol de decisión c5.0, regresión logística y Naive Bayes, en diferentes escenarios. 
