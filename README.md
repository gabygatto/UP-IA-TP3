# UP-IA-TP3

# Análisis de Sentimientos en Twitter

Trabajo Práctico N.º 3 de la materia Inteligencia Artificial.

## Descripción

El objetivo del proyecto es desarrollar un sistema de clasificación automática de sentimientos sobre tweets utilizando técnicas de Procesamiento de Lenguaje Natural (NLP).

Para ello se realizó un flujo completo de trabajo que incluye:

- Análisis exploratorio del dataset (EDA).
- Preprocesamiento y limpieza de los tweets.
- Vectorización del texto mediante TF-IDF.
- Entrenamiento y validación de modelos clásicos de Machine Learning:
  - Multinomial Naive Bayes.
  - Regresión Logística.
- Comparación de modelos utilizando Accuracy, Precision, Recall, F1-score y Matriz de Confusión.
- Validación adicional sobre conjuntos de entrenamiento y prueba para detectar posibles casos de overfitting.
- Evaluación de un modelo preentrenado (TextBlob) utilizando un conjunto de datos independiente.

## Estructura del proyecto

```
notebooks/
├── 01_EDA.ipynb
├── 02_Preprocesamiento.ipynb
├── 03_Entrenamiento_y_Validacion.ipynb
└── 04_Validacion_TextBlob.ipynb
```

## Dataset

Los datasets utilizados corresponden al corpus **Sentiment140**.

Debido a su tamaño, los archivos de datos y los modelos entrenados no se incluyen en este repositorio.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- spaCy
- TextBlob
- Matplotlib
- Seaborn
- Joblib
