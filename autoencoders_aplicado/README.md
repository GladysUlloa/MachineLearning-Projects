# Detección de Fraude en Seguros Médicos con Autoencoders
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24.2-green?logo=scikitlearn) ![Estado](https://img.shields.io/badge/Estado-En%20progreso-orange)

**Autora:** PhD(c). Gladys Choque Ulloa in Computer Science

---

## Introducción
Este notebook presenta una solución avanzada de **Detección de Anomalías** aplicada al sector salud (*Healthcare*). El objetivo principal es identificar reclamaciones de seguros potencialmente fraudulentas mediante el uso de **Autoencoders** (redes neuronales no supervisadas).

A diferencia de los métodos de clasificación tradicionales, este enfoque entrena al modelo para aprender el comportamiento "normal" de las transacciones legítimas, permitiendo que cualquier desviación significativa en la reconstrucción sea marcada como un posible fraude.

A lo largo del análisis se realiza:
* **Ingeniería de Características:** Transformación de datos complejos de proveedores y beneficiarios.
* **Arquitectura de Red Neuronal:** Implementación de un Autoencoder con capas densas y regularización (Dropout) en Keras/TensorFlow.
* **Estrategia de Entrenamiento:** Aprendizaje basado únicamente en datos no fraudulentos para definir la frontera de normalidad.
* **Optimización de Umbral:** Uso de curvas Precision-Recall para determinar el punto crítico de detección.
* **Evaluación Robusta:** Medición del desempeño mediante AUC-ROC, AUC-PR y matrices de confusión.

---

## Objetivos del Análisis
* Construir un modelo de aprendizaje profundo capaz de comprimir y reconstruir datos médicos con alta fidelidad.
* Utilizar el **Error de Reconstrucción** como métrica principal para la detección de fraude.
* Maximizar el *Recall* para capturar la mayor cantidad de eventos fraudulentos sin saturar el sistema con falsos positivos.
* Proporcionar un resumen ejecutivo con métricas de negocio claras (F1-Score, Precisión, AUC).

---

## Datos Utilizados
* **Dataset:** Healthcare Fraud Detection (Datos de proveedores, beneficiarios e instituciones). https://www.kaggle.com/datasets/nudratabbas/healthcare-fraud-detection-dataset
* **Variables clave:** Montos de reclamación, códigos de diagnóstico, deducibles, y duración de la hospitalización.
* **Naturaleza:** Datos altamente desbalanceados, característica típica en escenarios de fraude real.

---

## Tecnologías y Librerías
* **Lenguaje:** Python 3.x
* **Deep Learning:** TensorFlow / Keras
* **Procesamiento:** Pandas, NumPy, Scikit-learn (RobustScaler, PowerTransformer)
* **Visualización:** Matplotlib, Seaborn, Plotly
* **Métricas:** AUC-ROC, Precision-Recall Curve, Confusion Matrix

---

## Archivo Principal
* **Notebook:** `autoencoder_fraude_healthcare.ipynb`

---

## Resumen de Resultados
El modelo logra una separación clara entre transacciones legítimas y sospechosas:
* **Arquitectura:** Red Neuronal con dimensión latente optimizada para capturar la esencia de los datos.
* **Detección:** Capacidad de identificar patrones de fraude que no son detectables mediante reglas de negocio simples o regresiones lineales.
* **Escalabilidad:** Diseñado para procesar grandes volúmenes de reclamaciones en tiempo real.

---

## Licencia
Este proyecto se publica bajo la **licencia MIT**. Consulta el archivo `LICENSE` para más detalles.

---
**Desarrollado por Gladys Choque Ulloa** | Ciencia de Datos & Machine Learning

**Conecta conmigo:** [linktr.ee/gladyschoqueulloa](https://linktr.ee/gladyschoqueulloa)
