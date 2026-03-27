# HW6_Multilayer_NeuronalNetwork_w_hyperparameter_optimisation
En esta actividad, se llevó a cabo una red neuronal profunda donde se usa la optimización de hiperparámetros para el entrenamiento del modelo

Este proyecto implementa una red neuronal para clasificar teléfonos móviles en distintas categorías (Low, Mid_Low, Mid, High) a partir de sus características técnicas.

---------------
Jupyter Notebook
---------------

El desarrollo se realizó utilizando Jupyter Notebook, donde se llevó a cabo todo el flujo del modelo: carga de datos, limpieza, preprocesamiento, entrenamiento y evaluación.

Para ejecutar el proyecto, es necesario abrir el notebook y correr las celdas en orden. Esto permitirá observar paso a paso cómo se procesan los datos y cómo evoluciona el modelo durante el entrenamiento.

-------------
Modelo
-------------

El modelo consiste en una red neuronal multilayer donde:
  * Se utilizan las características del dataset como entrada
  * Se entrena el modelo para clasificar en múltiples clases
  * Se evalúa el desempeño mediante métricas de validación

Durante el entrenamiento se aplican técnicas como ajuste de hiperparámetros y early stopping para mejorar el rendimiento del modelo.

------------
Ejecución del programa
------------

Para ejecutar el proyecto:

 1- Abrir Jupyter Notebook

 2- Cargar el archivo .ipynb
 
 3- Ejecutar todas las celdas en orden

Es importante tomar en cuenta el orden de las celdas ya que esto afecta el flujo del proyecto desde el procesamiento de datos hasta los resultados finales.

---------Dependencias necesarias-----------
-------------------------------------------
python3
jupyter
numpy
pandas
matplotlib
tensorflow / keras
scikit-learn

Forma posible para su instalación:

python3 -m pip install numpy pandas matplotlib scikit-learn tensorflow jupyter
