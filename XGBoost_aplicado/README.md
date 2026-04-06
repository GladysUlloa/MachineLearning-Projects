# 📱 XGBoost Aplicado: Predicción de Precio de Smartphones

![XGBoost](https://img.shields.io/badge/Algorithm-XGBoost-orange?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Field-Machine_Learning-blue?style=for-the-badge)

Este repositorio contiene un caso práctico avanzado donde se aplica el algoritmo **XGBoost (Extreme Gradient Boosting)** para predecir el precio de lanzamiento de smartphones basándose en sus especificaciones técnicas. 

El proyecto conecta la implementación técnica con los fundamentos matemáticos del algoritmo, como la **Aproximación de Taylor de segundo orden** y la **Regularización L1/L2**.

---

## 🎯 Objetivo del Proyecto
Desarrollar un modelo de regresión capaz de estimar el precio en USD de dispositivos móviles utilizando un dataset real de 2025. Se busca demostrar por qué los modelos basados en árboles siguen dominando el análisis de datos tabulares frente a otras arquitecturas.

## 🗂️ Estructura del Notebook
1. **Fundamentos Matemáticos**: Breve repaso de la función objetivo y optimización.
2. **Exploración de Datos (EDA)**: Análisis de marcas, RAM, cámaras y batería.
3. **Preprocesamiento**: Limpieza y preparación de variables para el modelo.
4. **Entrenamiento con XGBoost**: Implementación de `XGBRegressor`.
5. **Evaluación**: Análisis de métricas (R², MAE, MSE).
6. **Ejercicios Prácticos**: Desafíos para profundizar en el ajuste de hiperparámetros.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías principales:**
  * `xgboost`: Modelado de alto rendimiento.
  * `pandas` & `numpy`: Manipulación y limpieza de datos.
  * `scikit-learn`: División de datos (Split) y métricas de evaluación.
  * `seaborn` & `matplotlib`: Visualización estadística.

## 📊 Conceptos Clave Implementados
* **Función Objetivo con Regularización**: Control del *overfitting* mediante parámetros $\gamma$ y $\lambda$.
* **Optimización mediante Gradiente**: Uso de derivadas de primer y segundo orden ($g_i$ y $h_i$).
* **Criterio de División (Gain)**: Cálculo de la ganancia para la estructura del árbol.

---

## ✍️ Autora
Gladys Choque Ulloa Data Scientist | PhD Student en Ciencias de la Computación (USP) Fundadora de Women in DataLab.
