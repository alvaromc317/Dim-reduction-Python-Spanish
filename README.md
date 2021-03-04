# Introducción a técnicas de reducción de la dimensión en Python

¡Bienvenidos a este curso de introducción a las SVM en español! La estructura y códigos de de este curso está basada en parte en el libro
* [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/). 

En este curso veremos qué es la maldición de la dimensión, y cómo solucionar, al menos en parte, este problema utilizando técnicas de reducción de la dimensión. Nos centraremos en dos tipos de técnicas: técnicas de filtro, y técnicas de proyecciones.

1. Las técnicas de filtro consisten básicamente en utilizar algún criterio para seleccionar, de entre las variables del conjunto de datos, aquellas más importantes antes de construir el modelo.
2. Las técnicas basadas en proyecciones buscan construir nuevas variables que expliquen la mayor cantidad de información posible usando el menor número de variables. La técnica de proyección más conocida es el análisis e componentes principales (principal component analysis, en inglés)

Estudiaremos todo esto utilizando dos conjuntos de datos, uno de un problema de regresión basado en el precio de las casas en boston, y otro de un problema de clasificación tumoral de cancer de mama.

Así que... ¡Empecemos!
