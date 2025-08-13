# TelecomX 1

Proyecto de análisis exploratorio para entender la evasión de clientes (churn) en Telecom X del Challenge 2 de Alura Latam.

Este proyecto incluye lo siguiente:  
- Carga de datos desde la API JSON "TelecomX_Data.json"
- Limpieza y tratamiento de datos  
- Análisis descriptivo y visualizaciones  
- Insights y recomendaciones preliminares

Herramientas usadas: Python, pandas, matplotlib, requests.

## Propósito del análisis
Este proyecto tiene como objetivo analizar la evasión de clientes (churn) en Telecom X mediante técnicas de análisis exploratorio de datos. A partir de la información demográfica, tipos de contrato, métodos de pago y consumo, se identifican patrones que ayudan a entender por qué algunos clientes cancelan sus servicios, para así proponer estrategias que reduzcan la tasa de abandono.

## Estructura del proyecto

- `TelecomX-1.ipynb`: Notebook principal con todo el código para la carga, limpieza, análisis y visualización de datos.
- `requirements.txt`: Listado de librerías necesarias para ejecutar el notebook.
- `README.md`: Documento que describe el proyecto, estructura y guía para su uso.
- `img/` (opcional): Carpeta con imágenes de gráficos generados en el análisis.

## Ejemplos de gráficos e insights obtenidos
- Distribución de la evasión (churn) global.
- Tasa de churn segmentada por tipo de contrato, método de pago y género.
- Comparación de variables numéricas como tiempo como cliente y monto mensual según estado de churn.

Estos analisis revelaron que clientes con contratos a corto plazo y ciertos métodos de pago presentan mayores tasas de cancelación, información clave para diseñar campañas de retención.

## Instrucciones para ejecutar el notebook

1. Clonar o descargar este repositorio en tu equipo.
2. Asegúrate de tener instalado Python 3 y las librerías listadas en `requirements.txt`.
   
Se puede instalar con:  
pip install -r requirements.txt

3. Abre el notebook `TelecomX-1.ipynb` en Google Colab o en tu entorno local (Jupyter Notebook).  
4. Ejecuta las celdas en orden para reproducir el análisis completo.  
5. Revisa los gráficos y completa el informe final según sea necesario.
