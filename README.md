##  Análisis de Clientes - ConnectaTel

##  Descripción del proyecto
Este proyecto consiste en un análisis exploratorio de datos de una empresa de telecomunicaciones (ConnectaTel), con el objetivo de identificar patrones de uso, segmentar clientes y generar insights estratégicos para la toma de decisiones.


## Objetivo
Analizar el comportamiento de los usuarios para:
- Identificar patrones de uso
- Detectar valores atípicos (outliers)
- Segmentar clientes por nivel de uso y edad
- Generar recomendaciones de negocio


##  Dataset
El dataset contiene información de usuarios, incluyendo:
- Edad (`age`)
- Cantidad de mensajes (`cant_mensajes`)
- Cantidad de llamadas (`cant_llamadas`)
- Minutos de llamada (`cant_minutos_llamada`)
- Tipo de plan (`plan`)


##  Análisis realizado

### 1. Análisis exploratorio
- Resumen estadístico de variables
- Distribución de planes

### 2. Visualización de datos
- Histogramas para analizar distribuciones
- Comparación por tipo de plan

### 3. Detección de outliers
- Uso de boxplots
- Aplicación del método IQR

### 4. Segmentación de clientes
- Por nivel de uso:
  - Bajo uso
  - Uso medio
  - Alto uso
- Por edad:
  - Joven
  - Adulto
  - Adulto Mayor


##  Hallazgos clave
- La mayoría de los usuarios presenta un nivel de uso medio.
- Existen usuarios con consumo alto (outliers), especialmente en minutos de llamada.
- El grupo predominante de clientes es el de adultos (<60 años).
- Los usuarios jóvenes representan una menor proporción.


##  Recomendaciones
- Crear planes premium para usuarios de alto consumo.
- Diseñar estrategias para atraer usuarios jóvenes.
- Optimizar planes actuales para usuarios de uso medio.


##  Cómo ejecutar el proyecto
1. Descargar el archivo `.ipynb`
2. Abrirlo en Google Colab o Jupyter Notebook
3. Ejecutar las celdas en orden


## 👤 Autor
Luis Mario Bermudez
