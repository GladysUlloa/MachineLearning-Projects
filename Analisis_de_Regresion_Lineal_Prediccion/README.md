# Análisis de Regresión Lineal para Predicción de Valores de Viviendas en California

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24.2-green?logo=scikitlearn) ![Estado](https://img.shields.io/badge/Estado-En%20progreso-orange)

**Autora:** Gladys Choque Ulloa

---

## Introducción

Este notebook presenta un análisis completo de **Regresión Lineal** aplicado al conjunto de datos de viviendas en California.  
El objetivo principal es construir un modelo que prediga el **valor mediano de las viviendas** (`median_house_value`) a partir de distintas características demográficas y geográficas.

A lo largo del análisis se realiza:

- Carga y exploración inicial de datos (**EDA**).  
- Preprocesamiento, incluyendo tratamiento de valores faltantes y codificación de variables categóricas.  
- División en conjuntos de entrenamiento y prueba.  
- Entrenamiento y evaluación de un modelo de regresión lineal simple.  
- Interpretación de los coeficientes para entender la influencia de cada variable.  
- Visualización dinámica de los resultados mediante animaciones para facilitar la comprensión.

Este trabajo ha sido desarrollado por Gladys Choque Ulloa con el objetivo de **compartir buenas prácticas en análisis y modelado de datos reales**, integrando visualizaciones avanzadas y técnicas robustas de preprocesamiento.

---

📌 **Objetivos del Análisis**

- Explorar las características del dataset de viviendas en California.  
- Analizar correlaciones entre variables numéricas y categóricas. 
- Construir un modelo de **Regresión Lineal** para predecir el valor medio de las viviendas.
- Evaluar el desempeño del modelo con métricas como RMSE y R².
- Visualizar los resultados mediante gráficos estáticos y animaciones GIF comparando valores reales vs. predicciones.

---

🗃️ **Datos utilizados**

- Carpeta: `data/`  
- Fuente original: [California Housing Dataset - sklearn.datasets](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)  
- Variables clave: `median_house_value`, `median_income`, `housing_median_age`, `total_rooms`, `total_bedrooms`, `population`, `households`, `latitude`, `longitude`.

---

🛠️ **Tecnologías y librerías**

- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook
- Matplotlib.animation

---

🧪 **Archivo principal**

📓 Notebook:
- [`CASO_APLICADO_Analisis_de_Regresion_Lineal_para_Prediccion.ipynb`](https://github.com/GladysUlloa/MachineLearning-Projects/blob/1fd3e78560a469e676a6476d320af547a329cc35/Analisis_de_Regresion_Lineal_Prediccion/Analisis_de_Regresion_Lineal_para_Prediccion.ipynb)
  
---

🎞️ **Animación generada**  
Una animación en formato GIF que compara **predicciones vs valores reales**, mostrando el ajuste del modelo y la línea ideal (`y=x`) para facilitar la interpretación visual.  

![Animación de predicciones](https://github.com/GladysUlloa/MachineLearning-Projects/blob/5fec83cbdca7fbe7a02453fbeb58d9bd1409a24b/Analisis_de_Regresion_Lineal_Prediccion/valores_reales_vs_predicciones.gif)

---

💬 **Notas adicionales**

- Proyecto ideal para quienes aprenden análisis de datos, predicción y visualización avanzada.  
- Desarrollado con enfoque didáctico, incluyendo comentarios y explicaciones paso a paso.

---

⚖️ **Licencia**

Este proyecto se publica bajo la **licencia MIT**.  
Consulta el archivo `LICENSE` para más detalles.

---

📚 **Desarrollado por Gladys Choque Ulloa | Ciencia de Datos & Estadística Aplicada**  
🔗 Sígueme en mis Redes Sociales: [linktr.ee/gladyschoqueulloa](https://linktr.ee/gladyschoqueulloa)


