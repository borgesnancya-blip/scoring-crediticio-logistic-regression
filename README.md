# 📊 Proyecto: Scoring Predictivo para Riesgo Crediticio

### 🎯 Objetivo del Proyecto
Desarrollar un modelo de Machine Learning capaz de clasificar clientes según su probabilidad de impago, optimizando la detección de deudores para reducir la cartera vencida en instituciones financieras.

---

### 🚀 Fases de Desarrollo y Optimización

#### 1. Preprocesamiento y Limpieza (Data Cleaning)
* **Tratamiento de Outliers:** Aplicación del método **IQR** (Rango Intercuartílico) para eliminar ruido en variables críticas como Ingresos y Monto del Préstamo.
* **Feature Engineering:** Análisis de la relación Deuda/Ingreso (LTI) como predictor clave.

#### 2. Modelo Base (Regresión Logística)
Se obtuvo una excelente estabilidad inicial con un **95% de Accuracy**. Sin embargo, se identificó la necesidad de mejorar la sensibilidad hacia los clientes de alto riesgo.

#### 3. Optimización Técnica (Respuesta a Negocio) 💡
Para alinear el modelo con una política de riesgos conservadora, se aplicaron dos mejoras críticas:
* **Estandarización (StandardScaler):** Normalización de escalas de variables financieras para asegurar una convergencia óptima del algoritmo.
* **Balanceo de Clases (SMOTE):** Implementación de sobremuestreo sintético para compensar el desbalance de la clase morosa.

---

### 📈 Resultados Finales y Métricas de Impacto

Tras la optimización, el modelo alcanzó un desempeño superior para el área de riesgos:

| Métrica | Resultado | Impacto en el Negocio |
| :--- | :--- | :--- |
| **Recall (Clase 1)** | **98%** | Identificación casi total de clientes con riesgo de default. |
| **Accuracy** | **93%** | Alta tasa de acierto global del modelo optimizado. |
| **Precision (Clase 0)** | **100%** | Seguridad total al aprobar clientes solventes. |

**Conclusión:** Se priorizó el **Recall (98%)** sobre el Accuracy general, entendiendo que en el sector bancario el costo de un "Falso Negativo" (no detectar a un deudor) es significativamente mayor al de revisar un falso positivo.

---

### 🛠️ Stack Tecnológico
* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, Scikit-Learn, Imbalanced-learn, Seaborn, Matplotlib.


