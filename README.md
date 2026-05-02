# Análisis de Comportamiento de Clientes - ConnectaTel 📱

Este proyecto analiza los patrones de uso de servicios móviles en México y Colombia. El objetivo es identificar segmentos de clientes, detectar comportamientos atípicos y proponer estrategias comerciales basadas en datos.

## 📊 Resumen del Proyecto
Se integraron tres fuentes de datos (planes, usuarios y actividad real) para construir un perfil estadístico completo. Se aplicaron técnicas de limpieza de datos, tratamiento de valores nulos, detección de outliers y segmentación demográfica.

## 🛠️ Herramientas Utilizadas
*   **Python:** pandas, numpy.
*   **Visualización:** seaborn, matplotlib.
*   **Entorno:** Jupyter Notebook / Google Colab.

## 🚀 Hallazgos Principales
*   **Calidad de Datos:** Se corrigieron valores *sentinel* (-999 en edad) y se estandarizaron ciudades inconsistentes.
*   **Segmentación:** Se identificaron tres grupos de uso (Bajo, Medio, Alto). La mayoría de los usuarios se encuentran en el segmento de bajo consumo.
*   **Outliers:** Se detectaron "Heavy Users" con consumos extremos que representan oportunidades para planes de alta gama.

## 📈 Recomendaciones de Negocio
*   **Plan Ultra:** Crear una oferta para el segmento de "Alto Uso".
*   **Migración:** Incentivar a usuarios de "Uso Medio" a subir al plan Premium.
