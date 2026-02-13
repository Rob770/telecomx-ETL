README.md
#  Análisis de Evasión de Clientes (Churn Prediction)

##  Descripción del Proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en la evasión de clientes (Churn) en una empresa de telecomunicaciones.

Se realizó un análisis exploratorio de datos (EDA), limpieza de variables y análisis de correlación para identificar qué características tienen mayor impacto en la cancelación del servicio.

---

##  Objetivos

- Analizar la distribución de la variable churn
- Identificar variables con mayor relación con la cancelación
- Crear nuevas variables (como total de servicios contratados)
- Explorar correlaciones entre variables
- Generar insights de negocio

---

##  Tecnologías Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---
Estructura del proyecto
│── 📄 README.md
│── 📄 .ipynb
│── 📄 dataset.csv


---

##  Instalación y Uso

1. Clonar el repositorio: https://github.com/Rob770/telecomx-ETL
2. Instalar dependencias: pip install pandas numpy matplotlib seaborn
3. Ejecutar el notebook:  jupyter notebook churn_analysis.ipynb
 

---

## Principales Hallazgos

- Los clientes con mayor cargo mensual presentan mayor probabilidad de churn.
- El número total de servicios contratados tiene correlación negativa con la evasión.
- Clientes con menor antigüedad (tenure) tienen mayor probabilidad de cancelar.

---

## Análisis de Correlación

Se utilizó la función: df.corr()



Para identificar relaciones entre variables numéricas.

Se creó la variable: total_servicios = suma de servicios contratados


Esto permitió observar que los clientes con más servicios tienden a ser más fieles.

---

## Próximos Pasos

- Implementar modelo de regresión logística
- Probar Random Forest
- Evaluar métricas (Accuracy, Recall, F1-Score)
- Optimización de hiperparámetros

---

##  Autor

Tu Nombre  
[LinkedIn] victor-rodriguez 
[GitHub] Rob770

##  Impacto de Negocio

Este análisis permite identificar clientes en riesgo de desertar, 
lo que puede ayudar a la empresa a implementar estrategias de retención
y reducir pérdidas económicas.







