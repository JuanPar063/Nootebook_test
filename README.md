# SVM Classifier - Kubeflow Testing Notebook

Notebook de prueba para integración con la plataforma **Kubeflow**. Entrena un clasificador SVM sobre el dataset Iris y está diseñado para ser ejecutado dentro de un pipeline de Kubeflow Pipelines.

## Descripción

Este repositorio contiene el notebook `svm_classifier_notebook.ipynb` que implementa un clasificador SVM (Support Vector Machine) sobre el dataset Iris de scikit-learn. El notebook sirve como prueba de la integración con Kubeflow para ejecutar notebooks de machine learning de forma orquestada.

## Tecnologías Utilizadas

- **Python**
- **scikit-learn** – Entrenamiento del modelo SVM
- **Jupyter Notebook** – Entorno de desarrollo interactivo
- **Kubeflow** – Plataforma MLOps de orquestación

## Contenido del Notebook

El notebook `svm_classifier_notebook.ipynb` incluye:

- Carga y exploración del dataset Iris
- Preprocesamiento de datos
- Entrenamiento de un clasificador SVM
- Evaluación del modelo

## Requisitos

```bash
pip install scikit-learn jupyter
```

## Ejecución Local

```bash
jupyter notebook svm_classifier_notebook.ipynb
```

## Autor

Juan Sebastian Pardo Anzola – [@JuanPar063](https://github.com/JuanPar063)
