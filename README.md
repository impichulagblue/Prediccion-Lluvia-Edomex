# Prediccion-Lluvia-Edomex

# Predicción de Precipitación Mensual: Integración Clima-Contaminación (Edomex)

## 📊 Descripción del Proyecto
Este proyecto desarrolla un sistema de Machine Learning para predecir la lluvia mensual en Acolman y Atenco, Estado de México. Se utilizaron datos históricos de **CONAGUA** y **SEMARNAT**.

## 🛠️ Proceso de Ingeniería de Datos
El dataset maestro se construyó desde cero a partir de fuentes oficiales con diferentes formatos:
* **Archivos de Texto Plano (.txt):** Se realizó la lectura técnica de datos de Precipitación y Normales Climatológicas Nacionales.
* **Archivos de Excel (.xlsx):** Se extrajeron variables de Radiación Solar y Emisiones Contaminantes.
* **Dataset Final:** Consolidación de todas las variables en un archivo de **3,112 registros** para el entrenamiento de modelos.

## 🚀 Modelado Híbrido
Utilicé dos enfoques para validar los resultados:
1. **Python:** Implementación de XGBoost, Random Forest y Redes Neuronales alcanzando un **80% de Accuracy**.
2. **Orange Data Mining:** Validación visual y comparativa de 4 modelos (Logistic Regression, Random Forest, Neural Network y Gradient Boosting).

## 📈 Conclusiones
* Se logró una precisión global del **80%** y un **F1-Score de 0.89**.
* Se identificó que la **Temperatura Máxima (Tmax)** es el factor con mayor peso predictivo.
* El proyecto demuestra que la integración de variables ambientales multifuente genera modelos robustos para el análisis climático.
