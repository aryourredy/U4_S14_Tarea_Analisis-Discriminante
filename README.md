# Comparación entre LDA y QDA utilizando el Wine Dataset

## Descripción

Este proyecto compara el desempeño del Análisis Discriminante Lineal (LDA) y el Análisis Discriminante Cuadrático (QDA) utilizando el Wine Dataset. Se realizó un análisis exploratorio de los datos, el entrenamiento de ambos modelos y la comparación de sus resultados mediante diferentes métricas de evaluación.

## Contenido del repositorio

- `U4_S14_Tarea_Análisis_Discriminante_(LDA_y_QDA).ipynb`: Notebook desarrollado en Google Colab.
- `Wine dataset.csv`: Conjunto de datos utilizado en el proyecto.
- `README.md`: Instrucciones para ejecutar el proyecto y resumen de los resultados.

## Requisitos

Para ejecutar el proyecto se necesita Python 3 y las siguientes librerías:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Si es necesario, pueden instalarse con el siguiente comando:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Cómo ejecutar el proyecto

1. Clonar o descargar este repositorio.
2. Abrir el archivo `U4_S14_Tarea_Análisis_Discriminante_(LDA_y_QDA).ipynb` en Google Colab o Jupyter Notebook.
3. Verificar que el archivo `Wine dataset.csv` se encuentre en la misma carpeta del notebook o subirlo al entorno de Colab.
4. Ejecutar todas las celdas del notebook en orden.

## Dataset

Se utilizó el **Wine Dataset**, que contiene información química de tres tipos de vino.

Características principales:

- 178 observaciones.
- 13 variables predictoras.
- 1 variable objetivo (`class`).
- 3 clases.

## Principales hallazgos

- LDA obtuvo un accuracy aproximado de **98.15 %**, mostrando un excelente desempeño en la clasificación.
- QDA obtuvo un **100 % de accuracy**, clasificando correctamente todas las muestras del conjunto de prueba.
- Ambos modelos presentaron valores muy altos de precisión, recall y F1-score.
- QDA logró un mejor ajuste debido a que permite una matriz de covarianza diferente para cada clase.
- Las fronteras de decisión mostraron que LDA genera límites lineales, mientras que QDA produce fronteras curvas más flexibles.

## Autor

Nombre: Pablo Alejandro Espinoza Pérez
Curso: Aprendizaje Automatico
Fecha: 6 de Julio de 2026
