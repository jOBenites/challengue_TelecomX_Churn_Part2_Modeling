# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

Este proyecto forma parte del desafío **"Churn de Clientes"** para la empresa ficticia **Telecom X**, cuyo objetivo es analizar los datos de clientes para identificar los factores que influyen en la cancelación de servicios y proponer estrategias para reducir la evasión.

## 📌 Objetivo
Realizar un análisis exploratorio de datos (**EDA**) y modelado predictivo usando **Python** en Google Colab para:
- Entender los patrones de cancelación de clientes.
- Identificar variables clave que afectan la retención.
- Proporcionar recomendaciones estratégicas para minimizar el *Churn*.

## 📂 Datos
El dataset utilizado se encuentra disponible en formato JSON:
- **Fuente:** [TelecomX_Data.json](https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_Data.json)
- Contiene información demográfica, de uso y de facturación de clientes.

## 🛠 Tecnologías y Librerías
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Requests (para cargar datos desde la API/URL)
- Google Colab

## 🔍 Proceso del Proyecto
1. **Extracción de Datos**
   - Carga directa desde la URL (GitHub raw content).
2. **Transformación y Limpieza**
   - Tratamiento de valores nulos.
   - Codificación de variables categóricas.
   - Escalado de variables numéricas.
3. **Análisis Exploratorio (EDA)**
   - Distribución de variables.
   - Relación entre características y churn.
   - Visualizaciones estratégicas.
4. **Modelado Predictivo**
   - Regresión Logística
   - KNN
   - Random Forest
   - SVM
   - Comparación de métricas de desempeño.
5. **Conclusiones e Insights**
   - Factores más relevantes que influyen en la cancelación.
   - Recomendaciones estratégicas.

## 📊 Resultados Clave
- Identificación de clientes con mayor riesgo de churn.
- Variables más influyentes: tipo de contrato, cargos mensuales, uso de servicios adicionales.
- Modelos con mejor rendimiento: **Random Forest** y **Regresión Logística**.

## 📈 Ejecución
Para ejecutar este análisis:
1. Abrir el archivo en Google Colab.
2. Instalar las librerías necesarias (si no están instaladas).
3. Ejecutar cada celda en orden.

📥 **Notebook:**  
[Descargar TelecomX_Churn_Analysis.ipynb](TelecomX_Churn_Analysis.ipynb)

## 📑 Informe Final Incluye:
- Introducción y contexto del problema.
- Proceso de limpieza y tratamiento de datos.
- Resultados del EDA con gráficos.
- Comparativa de modelos y métricas.
- Recomendaciones estratégicas.

## 📬 Autor
**Tu Nombre**  
*Data Analyst | Data Science Enthusiast*
