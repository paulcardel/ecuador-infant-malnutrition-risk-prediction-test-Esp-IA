# Predicción de Alerta de Desnutrición Infantil

## Contenido de la entrega

Este repositorio contiene la solución desarrollada para la prueba técnica de Especialista en Inteligencia Artificial.

### Archivos principales

* `Informe.pdf`: análisis técnico completo y resultados.
* `Propuesta_Implementacion.pdf`: propuesta de despliegue y operación institucional.
* `Prediccion_Desnutricion.ipynb`: notebook con todo el proceso de análisis, entrenamiento y generación de predicciones.
* `submissions/`: archivos generados para Kaggle.

---

## Reproducción de resultados

1. Abrir el notebook `Prediccion_Desnutricion.ipynb` en Google Colab.
2. Cargar los archivos:

   * `X_train.csv`
   * `y_train.csv`
   * `X_test.csv`
3. Ejecutar todas las celdas secuencialmente.
4. El notebook generará automáticamente los archivos de predicción.

---

## Modelo seleccionado

* Logistic Regression
* Escenario B (corrección de pesos extremos)
* Variable sexo excluida
* Threshold optimizado según el objetivo de evaluación

---

# Estructura del repositorio

```text
├── data/
│   ├── X_train.csv
│   ├── y_train.csv
│   ├── X_test.csv
│
├── notebooks/
│   ├── Prediccion_Desnutricion.ipynb
│
├── submissions/
│   ├── submission_final.csv
│   ├── submission_threshold_060.csv
│   ├── submission_threshold_070.csv
│
├── report/
│   ├── Informe.pdf
│   ├── Propuesta_Implementacion.pdf
│
├── README.md
```

## Autor

Paul Cárdenas Delgado





