# Telecom-X-Parte1

📑 Análisis de Retención de Clientes (Churn) - Telecom X
📌 Descripción del Proyecto
Este repositorio contiene un análisis exhaustivo sobre la evasión de clientes (Churn) para la empresa Telecom X. El objetivo principal es identificar los factores demográficos, financieros y contractuales que influyen en la pérdida de usuarios, permitiendo la creación de estrategias de retención basadas en evidencia.

🚀 Metodología Aplicada
El flujo de trabajo se dividió en las siguientes etapas técnicas:

ETL & Limpieza: Extracción de datos desde una fuente JSON, normalización de estructuras anidadas y tratamiento de valores nulos.

Ingeniería de Atributos: Creación de variables estratégicas como Cuentas_Diarias para analizar el gasto prorrateado.

Análisis Exploratorio (EDA): Visualización de patrones de comportamiento mediante gráficos de barras, boxplots y mapas de calor.

Análisis de Correlación: Identificación matemática de las variables con mayor impacto en la deserción.

📈 Hallazgos Clave (Insights)
Contratos: Los usuarios con contratos mensuales tienen una tasa de fuga significativamente mayor que los contratos a largo plazo.

Métodos de Pago: El uso de Electronic Check es un predictor fuerte de deserción.

Antigüedad (Tenure): Existe una "zona crítica" de deserción en los primeros 12 meses de servicio.

Cargos Mensuales: Se detectó una correlación positiva entre facturas elevadas y la probabilidad de Churn.

🛠️ Herramientas Utilizadas
Python: Lenguaje principal de análisis.

Pandas & NumPy: Manipulación y limpieza de datos.

Matplotlib & Seaborn: Generación de visualizaciones estadísticas.

Google Colab: Entorno de desarrollo en la nube.

📁 Estructura del Repositorio
TelecomX_Analysis.ipynb: Notebook principal con todo el código, visualizaciones e informe.

TelecomX_Data.json: Dataset original (vía enlace remoto).

README.md: Resumen del proyecto y guía de uso.

💡 Recomendaciones Estratégicas
Incentivar la migración de pagos manuales a Pagos Automáticos.

Fomentar la transición de contratos mensuales a Anuales mediante beneficios exclusivos.

Implementar un plan de acompañamiento para clientes de "alto valor" en sus primeros meses.
