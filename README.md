# Análisis Predictivo de Fuga de Clientes (Churn)

## 📌 Objetivo del Proyecto
Predecir el riesgo de abandono de los clientes para mejorar la retención y fomentar la lealtad. 
Para lograrlo, se desarrolló un modelo de Machine Learning de clasificación supervisada capaz de predecir si un cliente tiene una alta probabilidad 
de abandonar la empresa, permitiendo el diseño de estrategias preventivas.

## 🛠️ Herramientas Utilizadas
* **Python:** Lenguaje principal utilizado para el análisis.
* **Pandas y Numpy:** Utilizados para el procesamiento, limpieza de datos y tratamiento de valores nulos (imputación mediante mediana y moda).
* **Scikit-Learn:** Empleado para la división de datos (70% Train / 30% Test), estandarización y la creación del modelo predictivo mediante Regresión Logística.
* **Seaborn & Matplotlib:** Para la visualización de datos, incluyendo histogramas, matrices de correlación y curvas de aprendizaje.

## 📊 Hallazgos Principales
* Se determinó que variables como la Edad (EDAD), la Morosidad (M_MOROSO) y el Monto poseen una relación real y fuerte con la fuga de clientes.
* El análisis de datos confirmó que la morosidad actúa como un predictor fuerte de fuga dentro del modelo.
* El modelo de clasificación logró una exactitud (Accuracy) del 69%, demostrando que existe una relación lineal clara entre las características evaluadas y la variable objetivo.
* Se comprobó mediante análisis de sensibilidad que limpiar los datos y corregir los sesgos de medición disminuye drásticamente el error, generando un algoritmo predictivo mucho más confiable.
