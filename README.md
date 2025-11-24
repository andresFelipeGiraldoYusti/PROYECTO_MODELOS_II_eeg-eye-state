# PROYECTOMODELOS II (eeg-eye-state)

##  Integrantes

- Andrés Felipe Giraldo Yusti — andres.giraldoy@udea.edu.co 
- John Edison Zapata Ramírez — john.zapata1@udea.edu.co

## Video
[Ver el video en Google Drive](https://drive.google.com/file/d/1hANzA318St-K8pMYKmp3Fw5zslYOuGaO/view?usp=sharing)

## Fuente de datos

Los datos utilizados para entrenar y evaluar los modelos provienen de la siguiente base de datos:

[Acceder a la base de datos](https://www.openml.org/search?type=data&sort=runs&status=active&id=1471)

## Descricion del problema 

El proyecto aborda el problema de clasificar el estado ocular (abierto o cerrado) a partir de señales electroencefalográficas (EEG) utilizando métodos de Machine Learning.
Se emplea el dataset EEG Eye State del repositorio UCI, el cual contiene 14 canales EEG registrados con un dispositivo Emotiv Neuroheadset durante 117 segundos. Cada muestra está asociada a una etiqueta binaria:

0 → ojo abierto

1 → ojo cerrado

El objetivo principal es desarrollar, evaluar y comparar modelos de clasificación capaces de predecir el estado ocular basándose únicamente en las señales EEG crudas.

Este problema es relevante en áreas como:

  - Interfaces cerebro–computador (BCI)

  - Sistemas de monitoreo de atención y fatiga

  - Aplicaciones biomédicas de trazado cerebral

  - Interacción humana con sistemas inteligentes

El dataset presenta desafíos típicos en el procesamiento de biosenales, tales como ruido inherente, variabilidad temporal y características altamente correlacionadas. Por ello, el proyecto también incluye:

  - Preprocesamiento y limpieza de señales EEG

  - Reducción de dimensionalidad y selección de características

  - Implementación y evaluación de múltiples algoritmos de ML

  - Uso de validación cruzada y métricas estándar para garantizar resultados confiables

En conjunto, este proyecto proporciona una línea base sólida para la clasificación del estado ocular a partir de señales EEG y sienta las bases para aplicaciones más avanzadas dentro del ámbito de la neuroingeniería y el aprendizaje automático.


## Modelos 

1. Gaussian Naïve Bayes (GNB)
2. Máquinas de vectores de soporte (SVM)
3. Redes Neuronales Artificiales (MLPClassifier)
4. k-Nearest Neighbors (k-NN)
5. Arboles de decision (RF)

## Para replicar el experimento 

- Para realizar un análisis y exploración preliminar de los datos puede ejecutar en notebook que se encuentra en la ruta [notebooks/exploration/Exploración_y_División_de_datos.ipynb](notebooks/exploration/Exploración_y_División_de_datos.ipynb)
- Para ejecutar los modelos, obtener los resultados puede ejecutar los notebooks que se encuentras en [notebooks/models](notebooks/models). En estos encontrara la configuración de cada modelo, con las diferentes combinaciones en los parámetros de cada modelo. Se recopilan los resultados y las métricas y se muestran por medio de gráficos e impresión de los resultados como la métrica de precisión. 






