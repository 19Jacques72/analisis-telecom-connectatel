# Análisis de Comportamiento de Clientes - ConnectaTel 📱

## 1. Objetivo del Proyecto
Analizar los patrones de uso de servicios móviles (llamadas y mensajes) para identificar segmentos de valor, detectar comportamientos atípicos y proponer recomendaciones estratégicas para los planes Básico y Premium de ConnectaTel.

## 2. Datasets Utilizados
*   **plans.csv**: Detalles de los beneficios y costos de los planes.
*   **users_latam.csv**: Información demográfica y fechas de registro de los clientes.
*   **usage.csv**: Registro de la actividad real (mensajes y duración de llamadas).

## 3. Etapas del Análisis Realizadas
1.  **Carga y exploración:** Inspección de datos y verificación de tipos.
2.  **Limpieza de datos:** Corrección de sentinels (-999), estandarización de nulos y fechas.
3.  **Estadística descriptiva:** Análisis de promedios y comportamiento por usuario.
4.  **Detección de outliers:** Uso de Boxplots e IQR para identificar usuarios extremos.
5.  **Segmentación:** Clasificación por niveles de uso y grupos de edad.
6.  **Conclusiones:** Hallazgos principales y recomendaciones de negocio.

## 4. Cómo Ejecutar el Notebook
*   **En Google Colab:** Sube el archivo `.ipynb` a tu cuenta de Drive y ábrelo directamente.
*   **En Local:** Instala Anaconda y abre el archivo desde Jupyter Notebook o VS Code.

## 5. Guía de Reproducción
1. Descarga el repositorio completo desde GitHub.
2. Asegúrate de que los archivos CSV estén en la ruta `/datasets/`.
3. Ejecuta las celdas en orden secuencial.
