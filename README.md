# Taxi Demand Forecasting

✅ Project Description
Sweet Lift Taxi aims to anticipate taxi demand at airports in order to attract more drivers during peak hours.
The goal of this project is to predict the number of taxi orders for the next hour using historical data and machine learning models.
The target metric was defined as RMSE ≤ 48 on the test set.

✅ Objective
Build and evaluate regression models that allow:
Forecasting hourly taxi demand.
Capturing temporal patterns such as trend and seasonality.
Meeting the business-defined error threshold.

✅ Methodology
1. Data preparation.
2. Date conversion and resampling to hourly intervals.
3. Exploratory analysis of the time series.
4. Feature engineering: hour, day of the week, lags, and rolling averages.

✅ Modeling
Training and comparison of different regression models.
Performance evaluation using the RMSE metric.

✅ Technologies Used
  - Python
  - Pandas
  - NumPy
  - Scikit-learn
  - LightGBM
  - Random Forest
  - Statsmodels
  - Matplotlib

✅ Results
Three main models were evaluated:
  - Linear Regression: RMSE (test) = 45.21
  - Random Forest: RMSE (test) = 49.66
  - LightGBM: RMSE (test) = 45.92
The Linear Regression model showed the best balance between simplicity and generalization, successfully meeting the business requirement (RMSE < 48).


# Predicción de Demanda de Taxis 

✅ Descripción del proyecto Sweet Lift Taxi busca anticipar la demanda de taxis en aeropuertos para atraer más conductores durante las horas pico. El objetivo de este proyecto es predecir la cantidad de pedidos de taxi para la siguiente hora, utilizando datos históricos y modelos de machine learning. La métrica objetivo establecida fue que la RECM (RMSE) en el conjunto de prueba no superara 48. 

✅ Objetivo Construir y evaluar modelos de regresión que permitan: - Predecir la demanda horaria de taxis. - Capturar patrones temporales como tendencia y estacionalidad. - Cumplir con el umbral de error definido por el negocio. 

✅ Metodología 
1. Preparación de datos
2. 2. Conversión de fechas y remuestreo a intervalos de una hora.
3. Análisis exploratorio de la serie temporal.
4. Creación de features temporales: hora, día de la semana, retardos (lags) y medias móviles. 

✅ Modelado 
Entrenamiento y comparación de distintos modelos de regresión. Evaluación del desempeño con la métrica RECM (RMSE). 

✅ Tecnologías utilizadas 
  - Python
  - Pandas
  - NumPy
  - Scikit-learn
  - LightGBM
  - Random Forest
  - Statsmodels
  - Matplotlib 

✅ Resultados Se evaluaron tres modelos principales: 
  - Regresión Lineal: RECM (test) = 45.21
  - Random Forest: RECM (test) = 49.66
  - LightGBM: RECM (test) = 45.92

El modelo de Regresión Lineal presentó el mejor equilibrio entre simplicidad y capacidad de generalización, cumpliendo con el objetivo del negocio (RECM < 48).
