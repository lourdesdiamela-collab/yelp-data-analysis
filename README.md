<h1 align="center">⚙️ Data Engineering Pipeline & Analysis</h1>

<h3 align="center">Análisis de Datos de Yelp usando Ingeniería de Datos</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/API-REST-005571?style=for-the-badge&logo=postman&logoColor=white"/>
</p>

## 📌 Sobre el Proyecto

Este proyecto (Módulo 1 de Data Science en Henry) se enfoca en los fundamentos de la **Ingeniería de Datos y el Análisis Exploratorio**. 

El objetivo principal fue extraer datos desde la API de Yelp, realizar un proceso de limpieza (ETL), y posteriormente ejecutar un Análisis Exploratorio de Datos (EDA) para generar *insights* y recomendaciones de negocio.

## 📁 Estructura del Repositorio

La arquitectura del proyecto está diseñada para reflejar el flujo de trabajo de datos:

*   **`notebooks/`**: Cuadernos Jupyter con todo el código Python empleado:
    *   `Avance_API_Yelp.ipynb`: Script utilizado para conectarse a la API de Yelp, extraer la información en crudo y estructurarla.
    *   `Avance_EDA.ipynb`: Análisis Exploratorio de Datos. Limpieza, detección de outliers y visualizaciones univariadas/bivariadas.
    *   `Avance_Analisis_Final.ipynb`: Conclusiones y modelado básico estadístico.
*   **`docs/`**: Documentación formal del proyecto solicitada como entregables:
    *   `README.pdf`: Documento original con las directrices del proyecto.
    *   `Recomendaciones.pdf`: Hallazgos de negocio detectados tras el análisis de la data de Yelp.
*   **`data/`**: (Ignorado en Git por tamaño) Contiene de manera local los archivos JSON y CSV crudos extraídos de la API.

## 🛠️ Metodología (Pipeline)

1.  **Extracción (API REST):** Conexión segura a la API de Yelp usando la librería `requests` en Python para traer datos masivos en formato JSON sobre comercios locales.
2.  **Transformación (Pandas):** Anidado y desanidado de diccionarios JSON a DataFrames estructurados. Tratamiento de nulos, eliminación de columnas redundantes y casting de tipos de datos.
3.  **Exploración (EDA):** Uso de `matplotlib` y `seaborn` para encontrar correlaciones (ej. relación entre la calificación por estrellas y la cantidad de reseñas).
4.  **Reporting:** Extracción de *insights* convertidos en recomendaciones de negocio accionables, compiladas en los reportes PDF.

## 🚀 Cómo ejecutarlo

1. Para ver el análisis de datos, simplemente abre los archivos dentro de la carpeta `notebooks/`. GitHub renderiza los cuadernos Jupyter de manera nativa.
2. Si deseas replicar la abstracción de datos, recuerda que debes solicitar tu propia *API Key* en la plataforma de desarrolladores de Yelp y configurarla localmente.

---
*Desarrollado por **Lourdes Diamela Alarcon** como parte de las entregas de Data Science.*
