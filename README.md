ConectaTel — Customer Usage & Segmentation Analysis

Descripción del proyecto

Análisis exploratorio del comportamiento de clientes de ConectaTel, una empresa de telecomunicaciones con operaciones en Latinoamérica.

El objetivo es identificar patrones de consumo, evaluar la calidad de los datos, detectar valores atípicos y segmentar clientes para apoyar decisiones comerciales y estrategias de retención.

Datasets utilizados

plans.csv: información de los planes, tarifas y servicios incluidos.

users_latam.csv: información demográfica, planes contratados y registros de clientes.

usage.csv: registros de llamadas y mensajes.

El análisis utiliza información correspondiente al periodo de estudio hasta 2024.

Metodología

Exploración inicial y validación de los datasets.

Identificación y tratamiento de valores nulos, sentinels y fechas inconsistentes.

Consolidación del consumo por cliente.

Análisis estadístico de variables numéricas y categóricas.

Visualización de distribuciones e identificación de outliers mediante IQR.

Segmentación de clientes según edad y nivel de uso.

Elaboración de conclusiones y recomendaciones comerciales.

Herramientas utilizadas

Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

Principales hallazgos

Se identificaron problemas de calidad de datos, incluyendo edades inválidas, ciudades faltantes y fechas fuera del periodo de análisis.

Se construyeron métricas individuales de mensajes, llamadas y minutos de consumo.

Se establecieron segmentos de clientes por edad y nivel de uso.

Se desarrollaron visualizaciones para comparar patrones de consumo entre los planes Básico y Premium.

Cómo reproducir el análisis

Abrir ConectaTel_Analysis.ipynb en JupyterLab o Google Colab.

Instalar las bibliotecas de Python necesarias.

Obtener los tres archivos CSV de las fuentes autorizadas.

Ajustar las rutas de lectura de los datasets al entorno utilizado.

Ejecutar las celdas del Notebook en orden.

Nota: Las rutas /datasets/ utilizadas en el entorno educativo pueden no estar disponibles fuera de TripleTen.
