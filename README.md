# 📊 Datathon - Predicción de Ventas de Panadería

Este repositorio contiene mi proyecto individual del **Datathon** del Bootcamp de Data Analyst, Data Science + IA en Codespace Academy. El objetivo principal es **analizar y predecir las ventas** de productos de una panadería, aplicando técnicas de análisis exploratorio y modelos de machine learning.

## 🧠 Objetivo

Realizar una predicción de ventas futuras para un producto específico de panadería (código **3960**), utilizando datos históricos. El proyecto se ha desarrollado en Python y complementado con visualizaciones en Power BI.

## 🗂️ Archivos del proyecto
(Hay archivos que no se subiran por privacidad a la empresa que nos facilita los datos)
- `Datathon.pdf`: Enunciado del reto.
- `Cargar_y_Obtener_datos.ipynb`: Notebook con la carga de la base de datos y la obtención de estos.
- `EDA.ipynb`: Notebook con EDA con los datos que nos han facilitado y como me ha salido a mi.
- `MLOps.ipynb`: Notebook en el que desplegamos un modelo registrado en MLFlow y hacemos predicciones con este.
- `Dashboard_Panaderia.pbix`: Dashboard interactivo en Power BI.

## 🔍 Etapas del proyecto

### 1. Carga de Datos y Análisis Exploratorio (EDA)
- Integración de los diferentes archivos en un único DataFrame.
- Limpieza de datos, tratamiento de nulos y exploración de columnas relevantes.
- Visualización de patrones temporales y análisis de la estacionalidad.

### 2. Modelo Predictivo
- Selección del producto con código **3960**.
- Creación de un modelo de regresión.
- Evaluación del modelo con métricas como MAE y RMSE.

### 3. Producción
- Exportación del modelo entrenado.
- Simulación de uso en producción: predicción de ventas futuras para fechas específicas.
- Integración con el dashboard de Power BI. (Sin conseguir con mi propio modelo)

## 📈 Power BI Dashboard

El dashboard muestra:
- Evolución histórica de ventas.
- Comparativa de ventas semanales y mensuales.
- Predicción de ventas futuras con el modelo desarrollado.

## 💻 Tecnologías usadas

- Python (pandas, matplotlib, scikit-learn...)
- Visual Studio Code / Jupyter Notebook
- Power BI
