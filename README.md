# "Más allá del F1: auditoría de un modelo de predicción de pobreza"

Este repositorio contiene todo el flujo de trabajo necesario para replicar, las tablas, las gráficas y los cálculos usados en la redacción de la entrega final del documento 
"Más allá del F1: auditoría de un modelo de predicción de pobreza" en la asignatura "IA más allá del poder predictivo: equidad, interpretabilidad, privacidad, e incertidumbre" 
en la Bogotá Summer School in Economics 2026.

Este repo contiene dos carpetas principales:

- notebook: Esta carpeta guarda el cuaderno "00_main_notebook.ipynb" el cual genera todas las tablas, gráficas y cálculos usados para el documento final.

- stores: Esta carpeta guarda todos los archivos usados para el análisis, así como todos los resultados derivados. Esta tiene dos subcarpetas:
  - input: Esta carpeta guarda los archivos insumos usados para la auditoría, estos son los archivos originales de las particiones de las muestras de entrenamiento, validación y prueba. Así como el modelo original usado en la competencia.
  - output: Esta carpeta guarda todos los archivos usados en el documento de la auditoría, todas las tablas, gráficas, modelos y bases empleadas. 

Warning:

Para poder ejecutar de manera correcta el notebook es necesario, que en la sección "5. Mitigación por cortes diferenciales", es necesario instalar el modulo "error-parity" el cual puede dar errores en función de la versión de Python, para que este funcione es necesario usar el modulo Numpy en una versión anterior a la 2.0.0.
