# Semana 3 – Aprendizaje No Supervisado

## Descripción

Este proyecto corresponde a la actividad de las Semanas 2, 3 y 4 de la materia Aprendizaje Automático de la Maestría en Inteligencia Artificial – UEES.

El objetivo del trabajo fue aplicar técnicas de aprendizaje no supervisado para segmentar perfiles estudiantiles utilizando modelos de clustering y reducción de dimensionalidad, finalizando con técnicas de gobernanza de datos, eliminación de sesgo y explicabilidad del modelo.

---

## Dataset utilizado

Archivo:
`student_performance.csv`

Características:
- 500 registros
- Variables académicas y de comportamiento estudiantil
- Variables numéricas y categóricas
  

---

## Técnicas aplicadas

- Análisis exploratorio de datos (EDA)
- Tratamiento de valores nulos y escalado con StandardScaler
- Modelado Supervisado (Regresión Lineal, Ridge, Decision Tree, Random Forest)
- Modelado No Supervisado (K-Means, DBSCAN, PCA, t-SNE)
- **Auditoría de Equidad (Fairlearn): Paridad Demográfica e Igualdad de Oportunidades**
- **Explicabilidad del Modelo (XAI con SHAP y LIME): Impactos Globales y Locales**

---

## Estructura del repositorio

```text
data/           -> Dataset utilizado
imageness/      -> Visualizaciones exportadas
notebooks/      -> Notebooks principales del análisis S2 y S3, para esta tarea es S4_Gobernanza_XAI_y_Mitigacion_Sesgos.ipynb
presentacion/   -> Presentación PowerPoint
