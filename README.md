# Tarea 2 - IEE2714: Fundamentos de Procesamiento de Imágenes

**Estudiante:** Tomás Ferrada Contreras  
**Profesor:** Carlos Milovic  
**Fecha:** 09 de octubre de 2026  

## Descripción General
Este directorio contiene los archivos correspondientes a la entrega de la Tarea 2 del curso Fundamentos de Procesamiento de Imágenes. La tarea aborda la implementación y análisis de algoritmos para el manejo de Ruido Poisson mediante filtrado Gaussiano adaptativo, así como la reducción de ruido mediante Difusión Anisotrópica y Variación Total.

## Estructura de la Entrega

*   **`Tarea_2_IEE_2714.pdf` (Informe):** Contiene toda la justificación teórica, el análisis matemático, la interpretación de los resultados experimentales y las respuestas a las preguntas guiadas del enunciado. 
*   **Jupyter Notebook (`.ipynb`):** Contiene todo el código fuente en Python, incluyendo la definición de las funciones solicitadas y los bloques de experimentación.

## Instrucciones de Ejecución

El código ha sido estructurado en un único Jupyter Notebook para facilitar su revisión y evaluación. Está diseñado para ejecutarse de principio a fin sin requerir configuraciones adicionales.

Para ejecutar el código:
1. Abra el archivo `.ipynb` en su entorno de preferencia (Jupyter Notebook, JupyterLab, VS Code, Google Colab, etc.).
2. Asegúrese de contar con las librerías estándar de procesamiento y cálculo numérico en Python (como `numpy`, `matplotlib` y `scipy`).
3. En el menú superior de su entorno, seleccione la opción **"Run All"** (Ejecutar todo) o reinicie el kernel y ejecute todas las celdas secuencialmente.

El *notebook* se encargará de ejecutar las funciones, procesar las imágenes y generar todas las figuras referenciadas en el informe.

## Notas Adicionales
Toda la explicación sobre el "porqué" de las decisiones de diseño, el comportamiento de los parámetros (como el $\Delta t$ o el pre-suavizado en el Laplaciano) y el análisis comparativo de los algoritmos **se encuentra exclusivamente en el informe en PDF**. El *notebook* se enfoca netamente en la implementación práctica y la visualización de datos.
