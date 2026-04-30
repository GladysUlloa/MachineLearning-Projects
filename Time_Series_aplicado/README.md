# Análisis de Series de Tiempo — HVAC AHU Blower 78: Consumo Energético en KWh

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24.2-green?logo=scikitlearn) ![Estado](https://img.shields.io/badge/Estado-En%20progreso-orange)

**Autora:** PhD(c). Gladys Choque Ulloa in Computer Science

---

## Introducción
Este proyecto presenta un **análisis de datos (Data-Driven)** completo aplicado al consumo eléctrico de un sistema **HVAC (Heating, Ventilation and Air Conditioning)**, específicamente del componente **AHU Blower 78**. 

El objetivo es identificar patrones de consumo, detectar anomalías operativas y entender la estructura temporal de la serie mediante técnicas avanzadas de estadística y ciencia de datos. El dataset registra el consumo en intervalos de 10-15 minutos capturados a través de dispositivos **IoT** durante los meses de enero y febrero de 2022.

A lo largo del análisis se realiza:
*   **Carga y unificación** de múltiples fuentes de datos CSV.
*   **Análisis Exploratorio de Datos (EDA)** con enfoque en distribución estadística (Skewness, Kurtosis) y estados operativos (ON/OFF).
*   **Visualización de Series Temporales** incluyendo medias móviles para suavizado de señales.
*   **Detección de Anomalías** utilizando métodos robustos como Z-Score e IQR.
*   **Pruebas de Estacionariedad** (ADF y KPSS) para validación analítica.
*   **Descomposición de la Serie** en sus componentes de tendencia, estacionalidad y residuo.
*   **Dashboard Interactivo** para la exploración dinámica de los insights energéticos.

---

## Objetivos del Análisis
*   Limpiar y preprocesar datos provenientes de sensores IoT.
*   Visualizar la serie temporal completa e identificar patrones diarios/semanales.
*   Detectar eventos anómalos (picos de consumo fuera de rango).
*   Verificar la estacionariedad de la serie para futuros modelos de pronóstico (Forecasting).
*   Generar recomendaciones accionables para la gestión y mantenimiento preventivo del sistema.

---

## Datos Utilizados
*   **Archivos:** `KwhConsumptionBlower78_1.csv`, `KwhConsumptionBlower78_2.csv`, `KwhConsumptionBlower78_3.csv`.
*   **Variables clave:** `Datetime`, `Consumption (KWh)`, `is_on` (umbral operativo >= 0.5 KWh).
*   **Rango temporal:** Enero – Febrero 2022.

---

## Tecnologías y Librerías
*   **Lenguaje:** Python 3.x
*   **Procesamiento:** Pandas, NumPy, Scipy
*   **Visualización Estática:** Matplotlib, Seaborn
*   **Visualización Interactiva:** Plotly
*   **Análisis Estadístico:** Statsmodels (ADF, KPSS, ACF, PACF, Seasonal Decompose).

---

## Estructura del Proyecto
*   📓 **Notebook Principal:** `analisis_series_tiempo_blower78.ipynb`
*   📂 **Data:** Carpeta que contiene los archivos CSV de consumo energético.
*   🖼️ **Graficas:** Visualizaciones generadas (Distribución, Anomalías, Descomposición).

---

## Insights Destacados
*   **Tasa de Operación:** Análisis del porcentaje de tiempo que el blower permanece encendido vs. apagado para eficiencia operativa.
*   **Perfil Horario:** Identificación de horas pico y valles de consumo para optimización de demanda.
*   **Diagnóstico Analítico:** Validación de la naturaleza estacionaria de la serie, permitiendo el uso de modelos avanzados como ARIMA/SARIMA.

---

## Licencia
Este proyecto se publica bajo la **licencia MIT**. Consulta el archivo `LICENSE` para más detalles.

---
**Desarrollado por Gladys Choque Ulloa | Ciencia de Datos & Estadística Aplicada**  
🔗 Sígueme en mis Redes Sociales: [linktr.ee/gladyschoqueulloa](https://linktr.ee/gladyschoqueulloa)
