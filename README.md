# Predicción y Segmentación de Churn – Model Fitness

## Project Overview
A data-driven project for the gym chain **Model Fitness**.  
Goal: predict customer churn, understand the main drivers, and design actionable retention strategies.  

## Key Objectives
- Predict the **probability of churn** (next month).  
- Build **customer segments** through clustering.  
- Identify **top churn drivers**.  
- Provide **retention recommendations** to reduce attrition.  

## Tools
Python · Pandas · Scikit-learn · Matplotlib · Logistic Regression · Random Forest · KMeans  

## Approach
1. **EDA** → explored dataset, checked distributions, correlations, and churn differences.  
2. **Modeling** → trained Logistic Regression and Random Forest; evaluated accuracy, precision, recall.  
3. **Clustering** → applied KMeans (k=5) to profile customer groups and compare churn rates.  

## Results
- **Best model**: Logistic Regression (Accuracy 0.926 · Precision 0.884 · Recall 0.830).  
- **Top churn drivers**:  
  - Short contracts, low months left.  
  - Decline in visit frequency.  
  - Low engagement in additional services.  
- **Clusters (5 segments)**:  
  - C3: High risk (57% churn).  
  - C2: Very loyal (2%).  
  - C1: Active, short contract (9%).  
  - C0: Social, medium use (25%).  
  - C4: Low contact, disengaged (27%).  

## Conclusion
Churn is strongly linked to **contract length** and **engagement frequency**.  
Targeted actions (early renewal offers, engagement nudges, loyalty upgrades) can significantly reduce attrition.  

---

# Versión en Español

## Descripción
Proyecto de análisis de datos para la cadena de gimnasios **Model Fitness**.  
Objetivo: predecir la pérdida de clientes (churn), identificar causas y diseñar estrategias de retención.  

## Objetivos
- Predecir la **probabilidad de churn** (próximo mes).  
- Segmentar clientes mediante **clustering**.  
- Identificar los **principales factores de cancelación**.  
- Proponer **acciones para reducir la fuga** de clientes.  

## Herramientas
Python · Pandas · Scikit-learn · Matplotlib · Regresión Logística · Random Forest · KMeans  

## Metodología
1. **EDA** → exploración de datos, distribuciones, correlaciones, diferencias churn vs no churn.  
2. **Modelado** → entrenamiento con Regresión Logística y Random Forest; métricas de accuracy, precision y recall.  
3. **Clustering** → segmentación con KMeans (k=5), análisis de tasas de churn por grupo.  

## Resultados
- **Mejor modelo**: Regresión Logística (Accuracy 0.926 · Precision 0.884 · Recall 0.830).  
- **Drivers principales**:  
  - Contratos cortos y pocos meses restantes.  
  - Descenso en frecuencia de visitas.  
  - Bajo gasto en servicios adicionales.  
- **Clústeres (5 segmentos)**:  
  - C3: Riesgo alto (57% churn).  
  - C2: Muy leales (2%).  
  - C1: Activos, contrato corto (9%).  
  - C0: Sociales, uso medio (25%).  
  - C4: Poco contacto, baja interacción (27%).  

## Conclusión
La cancelación se relaciona con **contratos cortos** y **baja frecuencia de uso**.  
Acciones dirigidas como **renovaciones anticipadas, programas de lealtad y campañas de reactivación** pueden reducir significativamente la fuga de clientes.
