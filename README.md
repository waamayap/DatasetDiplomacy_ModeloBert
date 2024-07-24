

## Análisis y Clasificación de Mensajes de Diplomacy

Este proyecto tiene como objetivo analizar y clasificar los mensajes del juego Diplomacy para determinar si un mensaje es una mentira o no. Utilizamos NLP (Procesamiento de Lenguaje Natural) junto con modelos de transformadores (BERT) para lograr este objetivo.

## Estructura del Proyecto

DatasetDiplomacy/ - Directorio que contiene los datos de entrada en formato JSONL.

DatasetDiplomacy/ - Jupyter Notebooks utilizados para el análisis exploratorio de datos (EDA) y el entrenamiento y evaluación del modelo.

## Análisis Realizados

ETL de Mensajes: Extracción y limpieza de datos de mensajes del juego Diplomacy.

ETL de Etiquetas: Procesamiento de etiquetas asociadas a los mensajes para determinar si contienen mentiras.

NLP de Mensajes: Análisis de lenguaje natural para la tokenización y preprocesamiento de los mensajes.

Entrenamiento del Modelo: Entrenamiento de un modelo de clasificación utilizando BERT para identificar mentiras en los mensajes.

Evaluación del Modelo: Evaluación del modelo entrenado utilizando métricas como precisión, recall, F1-score y pérdida de evaluación.

Visualización de Datos: Gráficos y visualizaciones para representar los hallazgos del análisis y el rendimiento del modelo.

## Visualización de Datos
Se realizaron visualizaciones para entender mejor los datos y los resultados del modelo, incluyendo:

Distribución de Clases: Gráfico de barras mostrando la distribución de mensajes verdaderos y falsos.

Longitud de Mensajes: Histograma de la longitud de los mensajes.

Palabras Más Comunes: Gráfico de barras con las palabras más frecuentes.

Nube de Palabras: Nube de palabras para visualizar las palabras más frecuentes de manera atractiva.
