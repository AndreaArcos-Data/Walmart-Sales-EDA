# Walmart Sales – Exploratory Data Analysis

Este proyecto realiza un análisis exploratorio de las ventas semanales de Walmart entre 2010 y 2012.

## ESTRUCTURA DEL PROYECTO 

##  Objetivos del Proyecto
- Limpieza de datos 
- Feature Engineering inicial
- Análisis Exploratorio (EDA)
- Visualización de datos

##  Tecnologías
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn
  
##  Dataset Original
Los archivos originales pueden descargarse aquí (no se suben a GitHub por su gran tamaño y restricciones):
 [Walmart Dataset - Kaggle](https://www.kaggle.com/datasets/yasserh/walmart-dataset)

##  Dataset Limpio
El dataset final limpio utilizado en el análisis se encuentra en: [Google Drive](https://drive.google.com/drive/folders/14gCFJv0g0G4ZwKyWcun3E7YPY5MplMBv?usp=drive_link)

## Limpieza de datos 
- Conversión de fechas a formato datetime  
- Corrección de tipos numéricos  
- Unión de los 3 datasets originales  
- Eliminación de duplicados  
- Imputación de valores nulos en las columnas MarkDown (0 = no hubo promoción)  
- Detección de outliers mediante boxplots  
- Verificación de consistencia y formato

 ## Feature Engineering
 - Variables temporales: Año, Mes, Semana, Día del Año, Trimestre, etc.
- Variable categórica de festividades `Holiday_Type`  
- Variables dummies para `Holiday_Type` y `Type`  

## Análisis exploratorio 
- Transformación logarítmica de `Weekly_Sales` (para normalizar distribución)
- Transformaciones de variables Markdown
- Ventas promedio por año  
- Media móvil de 4 semanas  
- Tendencias y estacionalidad
- Análisis por tipo de tienda
- Impacto de días festivos
- Impacto de cada festividad
- Análisis de correlaciones 

##  Resultados Principales
- Las tiendas tipo A presentan mayores ventas promedio.
- BlackFriday tiene el mayor impacto positivo en ventas.
- Weekly_Sales tiene fuerte asimetría, corregible con log.
- La correlación más fuerte con ventas es el tamaño de la tienda (Size).

  ## AUTOR
  Andrea Arcos
  Para posiciones de data cleaning/ exploratory data analyst 
