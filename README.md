<img src="https://github.com/hernancontigiani/ceia_memorias_especializacion/raw/master/Figures/logoFIUBA.jpg" width="500" align="center">

# Trabajos Prácticos de Procesamiento de Lenguaje Natural I

### Carrera de Especialización en Inteligencia Artificial - Cohorte 18

**Autora**: María Luz Micozzi

---

## Desafíos

Este repositorio contiene una serie de cuadernos Jupyter que exploran diferentes conceptos y técnicas fundamentales en el campo del Procesamiento del Lenguaje Natural (PLN). Los desafíos fueron desarrollados como parte de la cursada y abordan temas que van desde la vectorización y análisis semántico hasta generación de texto con modelos recurrentes.

---

## Contenido del Repositorio

### [Desafío 1](https://github.com/mlmicozzi/PLN/blob/main/Desafio_1_Micozzi.ipynb)  
**Vectorización de texto y modelo de clasificación Naïve Bayes con el dataset 20 newsgroups**  
Aplicación de técnicas de vectorización (CountVectorizer, TfidfVectorizer) y utilizar clasificadores Naïve Bayes para tareas de clasificación de texto.

Datos utilizados: Se utilizó el dataset 20newsgroups de sklearn.datasets.

### [Desafío 2](https://github.com/mlmicozzi/PLN/blob/main/Desafio_2_Micozzi.ipynb)  
**Generación de embeddings con Gensim**  
Consigna: Probar términos de interés y explicar similitudes en el espacio de embeddings. Intentar plantear y probar tests de analogías. Graficar los embeddings resultantes.  

Datos utilizados: Se utilizó el libro “Orgullo y Prejuicio” en español, descargado del sitio textos.info.

### [Desafío 3](https://github.com/mlmicozzi/PLN/tree/main/Desafio%203)  
**Modelo de lenguaje con tokenización por caracteres**  
Consigna: Seleccionar un corpus de texto sobre el cual entrenar el modelo de lenguaje. Realizar el pre-procesamiento para tokenizar el corpus, estructurar el dataset y separar datos de entrenamiento y validación. Proponer arquitecturas RNN para implementar el modelo. Generar nuevas secuencias con greedy search y beam search (determinístico y estocástico), observando el efecto de la temperatura.  

Datos utilizados: El corpus seleccionado es una colección de subtítulos de películas y series traducidos al español obtenidos de la web OPUS. Los mismos fueron recolectados desde el sitio opensubtitles.

### [Desafío 4](https://github.com/mlmicozzi/PLN/blob/main/Desafio_4_Micozzi.ipynb)  
**LSTM Bot QA**  
Consigna: Utilizar datos disponibles del challenge ConvAI2 (Conversational Intelligence Challenge 2) de conversaciones en inglés para construir un BOT que responda preguntas del usuario (QA).

Datos utilizados: Se trabajó con el dataset data_volunteers de ConvAI2.
