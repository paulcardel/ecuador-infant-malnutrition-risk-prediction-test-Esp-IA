# Predicción de Alerta de Desnutrición Infantil

## Contenido de la entrega

Este repositorio contiene la solución desarrollada para la prueba técnica de Especialista en Inteligencia Artificial.

### Archivos principales

* `Prueba técnica – Especialista en Inteligencia Artificial - Paul Cardenas.pdf`: análisis técnico completo y resultados.
* `Propuesta de Implementacion - Paul Cardenas.pdf`: propuesta de despliegue y operación institucional.
* `Predicción de riesgo de desnutrición infantil.ipynb`: notebook con todo el proceso de análisis, entrenamiento y generación de predicciones.
* `submissions/`: archivos generados para Kaggle.

---

## Reproducción de resultados

1. Abrir el notebook `Predicción de riesgo de desnutrición infantil.ipynb` en Google Colab (para garantizar que corran todas las librerías se solicita abrir en Google Colab y no de forma local).
2. Cargar los archivos:

   * `X_train.csv`
   * `y_train.csv`
   * `X_test.csv`
   * *`sample_submission_malnutrition.csv`
3. Ejecutar todas las celdas secuencialmente.
4. El notebook generará automáticamente los archivos de predicción.
5. Se envía como respaldo un enlace a Google Drive con todos los entregables: https://drive.google.com/drive/folders/1XptQNEGOBzcWFVmNzZDv05r2EQ9RK8_l?usp=sharing

Nota: Se suben varios archivos para predicciones sample_submission.csv con el objetivo de mostrar diferentes pruebas realizadas, si se considerará la metrica de Accuracy se pide usar submission_threshold_070.csv, si se considera otra métrica como Recall (según lo explicado en el informe) se pide usar submission_threshold_060.csv

---

## Modelo seleccionado

* Logistic Regression
* Escenario B (corrección de pesos extremos)
* Variable sexo excluida
* Threshold optimizado según el objetivo de evaluación

---

## Autor

Paul Cárdenas Delgado





