<img src="https://github.com/hernancontigiani/ceia_memorias_especializacion/raw/master/Figures/logoFIUBA.jpg" width="500" align="center">

# Trabajos Prácticos de Procesamiento de Lenguaje Natural I

### Carrera de Especialización en Inteligencia Artificial - Cohorte 18

**Autora**: María Luz Micozzi

---

## Desafíos

Este repositorio contiene una serie de notebooks que exploran diferentes conceptos y técnicas fundamentales en el campo del Procesamiento del Lenguaje Natural (PLN). Los desafíos fueron desarrollados como parte de la cursada y abordan temas que van desde la vectorización y análisis semántico hasta generación de texto.

---

## Contenido del Repositorio

### [Desafío 1](https://github.com/mlmicozzi/PLN/blob/main/Desafio_1_Micozzi.ipynb)
**Vectorización de texto y modelo de clasificación Naïve Bayes con el dataset 20 newsgroups**

Aplicación de técnicas de vectorización y utilización de clasificadores Naïve Bayes para tareas de clasificación de texto.

Datos utilizados: Se utilizó el dataset 20newsgroups de sklearn.datasets.

Conclusión: En general, se logró clasificar el texto de manera efectiva. A pesar de las bajas medidas de similitud en algunos casos, fue posible encontrar relaciones contextuales entre las palabras dentro de los textos analizados.

### [Desafío 2](https://github.com/mlmicozzi/PLN/blob/main/Desafio_2_Micozzi.ipynb)
**Generación de embeddings con Gensim**

La consigna consiste en probar términos de interés y explicar similitudes en el espacio de embeddings. Intentar plantear y probar tests de analogías. Graficar los embeddings resultantes.

Datos utilizados: Se utilizó el libro “Orgullo y Prejuicio” en español, descargado del sitio textos.info.

Conclusión: Los embeddings entrenados en un corpus literario pequeño como "Orgullo y Prejuicio" son útiles para captar el contexto específico de ese texto. Sin embargo, su capacidad para generalizar relaciones semánticas más abstractas o universales es limitada, sugiriendo la recomendación de usar modelos preentrenados en grandes corpus para tareas más generales.

### [Desafío 3](https://github.com/mlmicozzi/PLN/blob/main/Desafio_3_Micozzi.ipynb)
**Modelo de lenguaje con tokenización por caracteres**

Seleccionar un corpus de texto sobre el cual entrenar el modelo de lenguaje. Realizar el pre-procesamiento adecuado para tokenizar el corpus, estructurar el dataset y separar entre datos de entrenamiento y validación. Proponer arquitecturas RNN para implementar el modelo. Generar nuevas secuencias con*greedy search y beam search.

Datos utilizado: El corpus seleccionado es una colección de subtítulos de películas y series traducidos al español obtenidos de la web OPUS. Los mismos fueron recolectados desde el sitio opensubtitles.

Conclusión: Aunque los modelos implementados logran formar palabras correctas, la coherencia sintáctica y semántica de las frases generadas es limitada.

### [Desafío 4](https://github.com/mlmicozzi/PLN/blob/main/Desafio_4_Micozzi.ipynb)
**LSTM Bot QA**

Utilización de datos disponibles del challenge ConvAI2 (Conversational Intelligence Challenge 2) de conversaciones en inglés para construir un BOT que responda preguntas del usuario (QA).

Datos utilizados: Se trabajó con el dataset `data_volunteers` de ConvAI2.

Conclusión: El modelo alcanzó una precisión moderada, pero las respuestas generadas fueron coherentes en estructura, aunque genéricas, repetitivas y, en la mayoría de los casos, no adecuadas a las preguntas específicas.

---

### Requisitos

Para ejecutar los notebooks, asegúrate de tener Python 3.8+ instalado. Las principales librerías requeridas pueden instalarse vía `pip`:

```bash
pip install numpy pandas scikit-learn gensim matplotlib seaborn tensorflow keras nltk ipywidgets jupyter
