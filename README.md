# Employee Attrition Prediction

Este repositorio contiene el código y los recursos desarrollados para mi Trabajo de Fin de Grado (TFG), cuyo objetivo es predecir el nivel de *attrition* (deserción) de empleados utilizando varios modelos de aprendizaje automático. El proyecto se basa en un dataset obtenido de Kaggle.

## Descripción del Proyecto

El objetivo principal de este TFG es analizar y predecir la probabilidad de que un empleado abandone una empresa utilizando diferentes técnicas de *machine learning*. Se exploran varios modelos para identificar cuáles son más efectivos en la predicción de la deserción laboral.

### Dataset

El dataset utilizado en este proyecto proviene de [Kaggle](https://www.kaggle.com/) y contiene información sobre empleados, incluyendo características como la satisfacción laboral, la antigüedad en la empresa, el nivel de salario, entre otros factores relevantes.

### Modelos Utilizados

Los siguientes modelos de aprendizaje automático se implementaron y compararon en este proyecto:

- **Regresión Logística**
- **Árboles de Decisión**
- **Bosques Aleatorios (Random Forest)**
- **Máquinas de Soporte Vectorial (SVM)**
- **Redes Neuronales Artificiales**

## Estructura del Repositorio

El repositorio está organizado en las siguientes carpetas y archivos:

- **notebooks/**: Contiene los Jupyter Notebooks con el análisis exploratorio de datos (EDA), el preprocesamiento de los datos y la implementación de los modelos de *machine learning*.
- **data/**: Incluye el dataset utilizado para el proyecto (no subido al repositorio debido a políticas de privacidad de datos).
- **models/**: Modelos entrenados y guardados para su reutilización.
- **reports/**: Documentación del TFG, incluyendo el informe final y presentaciones.
- **README.md**: Este archivo con la descripción del proyecto.

## Requisitos

Para ejecutar el código en este repositorio, necesitas tener instaladas las siguientes herramientas:

- **Python 3.x**
- **Jupyter Notebook**
- **Librerías Python**: Puedes instalar las dependencias necesarias utilizando el archivo `requirements.txt`:

  ```bash
  pip install -r requirements.txt
