# ProyectoFinal_DataScience
Análisis y creación de modelo de predicción del precio del Bitcoin utilizando Machine Learning

Este proyecto tiene como objetivo predecir el precio de cierre del Bitcoin utilizando diversas técnicas de análisis de datos y modelado predictivo. A continuación se describen los pasos realizados, las herramientas utilizadas y los resultados obtenidos.

1. Descripción del Proyecto

Este proyecto aborda la predicción del precio de cierre del Bitcoin a través de la aplicación de técnicas de análisis exploratorio de datos (EDA), transformación de datos, reducción de dimensionalidad, y el uso de múltiples modelos de regresión y técnicas de stacking.

2. Estructura del Proyecto

1 - Motivación.  
2 - Audiencia.  
3 - Adquisición de la información.  
4 - Dependencias del proyecto.
4.1 - Librerías.  
4.1.1 - Instalación.  
4.1.2 - Importaciones.  
4.2 - Paleta de colores.  
5 - EDA (Exploratory Data Analysis).  
5.1 - Preparación del dataset.  
5.1.1 - Nueva creación de variables: "Range" y "Difference".  
5.2 - Análisis Gráficos.  
5.2.1 - HEATMAP.  
5.2.1.1 - Análisis de resultados:  
5.2.2 - BOXPLOT.  
5.2.2.1 - Análisis de resultados:  
5.3 - Análisis temporal.  
5.3.1 - Descomposición Estacional:  
5.3.1.1 - Análisis del gráfico de Descomposición Estacional:  
5.3.2 - Análisis de Autocorrelación:  
5.3.2.1 - Análisis del gráfico de Autocorrelación (ACF).  
5.4 - Análisis por Hora Día de la Semana.  
5.4.1 - Análisis del resultado:  
5.5 - Análisis de Volatilidad.  
5.5.1 - Volatilidad Mensual:  
5.5.1.1 - Análisis del gráfico:  
5.5.2 - Heatmap de la volatilidad mensual:  
5.5.2.1 - Análisis del Gráfico:  
5.6 Análisis de Distribución.  
5.6.1 - Histograma y KDE:  
5.6.1.1 - Análisis del Gráfico:  
5.6.2 - Boxplot por Mes:  
5.6.2.2 - Análisis del Gráfico:  
6 - Contexto comercial.  
7 - Problema comercial.  
8 - Hipótesis.  
8.1 - Evolución del precio del bitcoin.  
Análisis del Gráfico:  
8.2 - Variación diaria del precio del Bitcoin.  
Análisis del Gráfico:  
8.3 - Relación entre Volumen de operaciones y variación del precio.  
Análisis del Gráfico:  
8.4 - Comportamiento del mercado durante diferentes días de la semana.  
Análisis del Gráfico:  
8.5 - Días con mayor caída de precio.  
8.6 - Días con mayor aumento de precio.  
Conclusión:  
8.7 - Evolución del precio diario en los años considerados.  
Análisis del Gráfico:  
8.8 - Semanas o meses en los que el bitcoin varia más.  
Análisis del Gráfico:  
8.9 - Patrón de cabeza y hombros.  
8.10 - Histograma: Rendimientos diarios.  
Análisis del Gráfico:  
8.11 - Dispersión precio de cierre vs volumen de negociación.  
Análisis del Gráfico:  
8.12 - Volatilidad a lo largo del tiempo.  
8.13 - Gráficos de medías móviles 9, 20 y 200.  
9 - Modelo de Predicción.  
9.1 - Transformación Logaritma de los Datos.  
9.2 - Visualización de la transformación Logaritmica.  
9.3 - Análisis de Componentes Principales (PCA).  
9.3.1 - Escalado de los Datos.  
9.3.2 - Aplicación de PCA y Visualización.  
9.4 - Reducción de la Colinealidad.  
9.6 - División del Conjunto de Datos.  
9.7 - Escalado y PCA.  
9.8 - Entrenamiento y Evaluación del Modelo.  
9.8.1 - Modelo de Regresión Lineal.  
9.8.2 - Validación Cruzada.  
9.9 - Evaluación de Modelos Adicionales.  
10 - Modelo de Predicción.  
10.1 - Ajuste de Hiperparámetros y Modelo de Ensamble.  
10.2 - Guardar el modelo.  
10.3 - Cargar el modelo.  
10.4 Gráfico de valores reales vs predichos.  
11 - Futura implementación con datos nuevos.  
12 - Conclusiones.  

3. Requisitos

Google Colab  
Bibliotecas:  
pandas  
numpy  
scikit-learn  
matplotlib  
seaborn  
xgboost  
scikit-optimize  

4. Análisis de Datos

Se realizó un análisis exploratorio de datos (EDA) para comprender la distribución y las características del precio de cierre del Bitcoin. Se visualizaron histogramas, gráficos de caja y gráficos de líneas para identificar patrones y tendencias.

5. Modelos Predictivos

Se entrenaron varios modelos de regresión, incluyendo Linear Regression, DecisionTreeRegressor, RandomForestRegressor, SVR, XGBRegressor y Gradient Boosting. También se aplicó PCA para reducir la dimensionalidad y se utilizó stacking de modelos para mejorar el rendimiento predictivo.

6. Evaluación de Modelos

Se evaluaron los modelos utilizando métricas como el Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE) y el coeficiente de determinación (R²). Los modelos se evaluaron tanto en la escala logarítmica como en la escala original.

7. Resultados

El modelo de stacking mostró el mejor rendimiento con un R² muy alto, aunque hubo indicios de overfitting en algunos modelos. Se logró una alta precisión en las predicciones del precio de cierre del Bitcoin.

8. Conclusiones

El proyecto demostró la efectividad de combinar múltiples técnicas de análisis y modelado para predecir el precio de cierre del Bitcoin. La transformación logarítmica, la creación de características adicionales y el uso de técnicas avanzadas como PCA y stacking permitieron capturar mejor la complejidad del mercado de Bitcoin.
