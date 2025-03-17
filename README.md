# Predicción de Salarios con Machine Learning

Este proyecto implementa un modelo de predicción de salarios usando técnicas avanzadas de **Machine Learning**, optimización y visualización interactiva.

## Estructura del Proyecto
- data: Datos originales y versionados con DVC.
- notebooks: Análisis exploratorio y experimentos.
- models: Modelos entrenados guardados con MLFlow.
- api: API con FastAPI para predicciones en tiempo real.
- README.md: Documentación del proyecto.

##  Características
 **Carga y Validación de Datos** : Polars, Pandera  
 **Datos Sintéticos** :SDV (GaussianCopula)  
 **Preprocesamiento Avanzado** : StandardScaler, OneHotEncoder  
 **Entrenamiento Optimizado** : XGBoost, LightGBM, MLPRegressor  
 **Seguimiento de Experimentos** : MLFlow  
 **Explicabilidad** : SHAP  
 **Visualización Interactiva** : Altair  
 **API con FastAPI** : Servidor para predicciones  
 **Base de Datos** : Predicciones almacenadas en SQLite 

##  Instalación
pip install -r requirements.txt

##  Ejecución
### 1° **Entrenar el Modelo**
python train.py

### 2° **Ejecutar la API**
uvicorn api.main:app --reload

##  Visualización de Resultados
Ejecutar el notebook en **notebooks** para analizar el desempeño del modelo y visualizar datos.



## 📌 Contribuciones
¡Sugerencias y mejoras son bienvenidas! 😊

## 📜 Licencia
Este proyecto está bajo la licencia MIT.

