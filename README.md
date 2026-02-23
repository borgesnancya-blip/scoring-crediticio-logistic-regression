
# 📊 Proyecto: Scoring Predictivo para Riesgo Crediticio

## 🎯 Objetivo del Proyecto
Desarrollar un modelo de **Machine Learning** capaz de clasificar clientes según su probabilidad de impago, optimizando la detección de deudores para reducir la **cartera vencida** en instituciones financieras.

---

## 🚀 Fases de Desarrollo y Optimización

###  Preprocesamiento y Limpieza
* **Tratamiento de Outliers:** Aplicación del método **IQR (Rango Intercuartílico)** para eliminar ruido en variables críticas como Ingresos y Monto del Préstamo.
   
###  Optimización Técnica (Garantía de Robustez) 💡
Para asegurar la confiabilidad del modelo y responder a los estándares más altos de la industria, se aplicaron tres mejoras críticas:

Categorización de Edad

Estandarización (StandardScaler)

Balanceo de Clases (SMOTE)


## 📈 Resultados Finales y Métricas de Impacto

Tras la optimización, el modelo alcanzó un desempeño superior para el área de riesgos:

| Métrica | Resultado | Impacto en el Negocio |
| :--- | :--- | :--- |
| **Recall (Clase 1)** | **98%** | Identificación casi total de clientes que cumplirán con sus pagos. |
| **Precisión (Clase 0)** | **100%** | Seguridad total al identificar clientes con riesgo de impago (cero falsos positivos de riesgo). |
| **Accuracy Total** | **95.74%** | Alta tasa de acierto global del modelo optimizado. |



> **📌 Conclusión:** Se priorizó el **Recall (98%)** sobre el Accuracy general, entendiendo que en el sector bancario el costo de un "Falso Negativo" (no detectar a un deudor) es significativamente mayor al de revisar un falso positivo.

---

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 3.x
* **Librerías:** Pandas, NumPy, Scikit-Learn, Imbalanced-learn, Seaborn, Matplotlib.
* **Despliegue:** Preparado para implementación en **Streamlit**.

---
