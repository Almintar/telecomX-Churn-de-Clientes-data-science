<h1> Telecom X - Análisis de Evasión de Clientes</h1>

Este proyecto realiza un análisis exploratorio de datos (**EDA**) y visualizaciones para identificar patrones relacionados con la evasión de clientes (**Churn**) en la empresa **TelecomX**.  
El objetivo es comprender el perfil de los clientes, analizar la facturación y encontrar factores clave que influyen en la cancelación del servicio.

## 📂 Estructura del Proyecto
<img width="779" height="121" alt="image" src="https://github.com/user-attachments/assets/99e89029-27b4-4c07-80e3-926dc6d3001a" />

## 🛠️ Tecnologías Utilizadas

- **Python 3.10**
- **Pandas** (procesamiento y limpieza de datos)
- **NumPy** (operaciones numéricas)
- **Matplotlib** y **Seaborn** (visualizaciones)
- **Jupyter Notebook** (desarrollo interactivo)
- **JSON** (lectura del archivo de datos)

## 📑 Flujo de Trabajo

1. **Carga y exploración de datos** desde `TelecomX_Data.json`.
2. **Limpieza y tratamiento**:
   - Conversión de columnas a tipos adecuados (`Charges.Total` a float).
   - Reemplazo de valores faltantes por la media.
   - Creación de variables derivadas (`Cuentas_Diarias`).
3. **Análisis Exploratorio de Datos (EDA)**:
   - Análisis de facturación.
   - Perfil sociodemográfico de los clientes.
   - Relación entre características y churn.
4. **Visualizaciones**:
   - Distribución de facturación mensual y total.
   - Perfil de clientes por edad, género, contrato, servicios.
   - Churn vs variables demográficas y contractuales.

## 📈 Principales Insights

- Los clientes con **contratos más largos** y **facturación más alta** tienen menor churn.
- El segmento **SeniorCitizen** presenta mayor tasa de cancelación.
- Tener **pareja y dependientes** está asociado a una mayor permanencia.
- El **género** no es un factor relevante en la cancelación.
- Los **servicios adicionales** ayudan a retener clientes.

## 🚀 Recomendaciones

- Diseñar campañas de retención específicas para **SeniorCitizen**.
- Ofrecer **paquetes familiares** a clientes sin pareja ni dependientes.
- Incentivar la contratación de **servicios combinados**.
- Implementar un **modelo predictivo de churn** para actuar de forma proactiva.

