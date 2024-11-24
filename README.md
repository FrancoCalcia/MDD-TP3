# Predicción de la Estación del Año con Modelos de Machine Learning

Este repositorio contiene el código desarrollado para un trabajo práctico cuyo objetivo es predecir la estación del año a partir de atributos meteorológicos. Se utilizaron diferentes modelos de machine learning y técnicas de validación cruzada para evaluar su desempeño.

## Objetivo del Proyecto

Aplicar los conocimientos adquiridos en las unidades 5 y 6 para resolver un problema real utilizando modelos de predicción. 

### Modelos Evaluados
1. **Máquinas de Vectores de Soporte (SVM)** con:
   - Kernel lineal (análisis del parámetro de costo).
   - Kernel gaussiano (análisis de los parámetros costo y gamma).
2. **Random Forest** (análisis de la cantidad de estimadores y la máxima profundidad de los árboles).

### Métricas de Evaluación
Los modelos fueron evaluados utilizando validación cruzada con `k=5`, y se calcularon las siguientes métricas:
- Precisión
- Exhaustividad
- Exactitud

## Dataset

El análisis se realizó sobre el conjunto de datos **dxWeather.csv1**, que contiene atributos meteorológicos y la estación correspondiente. Se llevó a cabo un preprocesamiento para analizar las distribuciones, detectar valores atípicos, y verificar los tipos de datos.

## Requisitos

- **Google Colab** (Recomendado para ejecutar el proyecto).

## Ejecución del Proyecto

1. Clona este repositorio o descarga los archivos necesarios.
2. Abre el archivo principal del proyecto en Google Colab.
3. Asegúrate de tener instalado el entorno de ejecución de Colab con las bibliotecas requeridas.
4. Ejecuta el código directamente desde Colab.

**Nota**: La ejecución de los modelos puede tardar hasta **20 minutos**, especialmente el modelo con kernel gaussiano.

## Resultados Obtenidos

1. **SVM con kernel lineal**:
   - Análisis del impacto del parámetro de costo.
   - Métricas promedio sobre los conjuntos de test.
2. **SVM con kernel gaussiano**:
   - Análisis conjunto de los parámetros costo y gamma.
   - Métricas promedio sobre los conjuntos de test.
3. **Random Forest**:
   - Análisis del impacto de la cantidad de estimadores y la profundidad máxima.
   - Métricas promedio sobre los conjuntos de test.

## Estructura del Repositorio

- `dxWeather.csv1`: Conjunto de datos utilizado para el análisis.
- `main.ipynb`: Notebook principal con el desarrollo del trabajo práctico.
- `README.md`: Descripción del proyecto y guía de uso.

