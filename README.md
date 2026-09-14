# Predictivo-Diabetes-Mexico
Prototipo de clasificación multiclase de diabetes usando Deep Learning y MongoDB.

# Tamizaje Clínico de Diabetes con Deep Learning 🩺📊

Este repositorio contiene el prototipo funcional y el código fuente para el **Modelo Predictivo de Aprendizaje Profundo para el Tamizaje Oportuno y Clasificación Multiclase de Tipologías de Diabetes en México**.

## Arquitectura del Prototipo
* **Base de Datos:** Los históricos clínicos originales (70,000 registros de la ENSANUT) se gestionan mediante una arquitectura NoSQL en **MongoDB**, asegurando flexibilidad y tiempos de lectura óptimos. *Nota: Por cuestiones de ética y privacidad médica, la base de datos no se incluye en este repositorio público.*
* **Preprocesamiento:** Limpieza de anomalías, imputación por mediana y estandarización Z-Score.
* **Modelo Predictivo:** Red Neuronal Profunda (Perceptrón Multicapa) construida con `TensorFlow` y `Keras`, optimizada con capas de `Dropout`.
* **Visualización:** Dashboard generado con `Matplotlib` y `Seaborn` para entornos clínicos.

## Requisitos y Dependencias
Para ejecutar el entorno del prototipo, se requieren las siguientes librerías de Python:
* `pandas`
* `numpy`
* `scikit-learn`
* `tensorflow`
* `matplotlib`
* `seaborn`
* `pymongo`

## Instrucciones de Ejecución
1. Clonar este repositorio o descargar el archivo `.ipynb`.
2. Abrir el archivo en **Google Colab** o en un entorno local de Jupyter Notebook.
3. Conectar la base de datos (mediante la URI de MongoDB o cargando el archivo CSV de la muestra anonimizada).
4. Ejecutar las celdas secuencialmente para entrenar el modelo (Accuracy esperado: ~97.8%) y desplegar el Cuadro de Mando Predictivo.
