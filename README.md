# Death Metal Classifier Notebook - Version 1

Este notebook presenta una versión inicial del proyecto de modelado para clasificar canciones como pertenecientes o no al género de Death Metal. Se aborda el desafío de un gran desbalance de clases en la variable objetivo, utilizando la técnica de sobremuestreo SMOTE (Synthetic Minority Over-sampling Technique) para mejorar la capacidad del modelo para captar la clase positiva.

## Uso en Google Colab

Puede ejecutar este notebook directamente en Google Colab sin necesidad de instalar ninguna biblioteca adicional. Todos los datos necesarios están almacenados en un Google Drive público, y las bibliotecas requeridas están preinstaladas en el entorno de Google Colab.

1. Abra el notebook en Google Colab: [Clasificador_deathmetal.ipynb](https://github.com/AdolfoFGP/Clasificador_deathmetal/blob/main/Clasificador_deathmetal.ipynb).

2. Asegúrese de estar conectado a Google Drive para acceder a los conjuntos de datos almacenados.

3. Ejecute cada celda paso a paso para cargar datos, realizar preprocesamiento y entrenar modelos.

4. Explore los resultados y las métricas de precisión obtenidas durante el proceso de entrenamiento.

## Contenido del Notebook

1. **Carga de Datos:**
   - Obtención de datos desde la API de Spotify a través de conjuntos de datos almacenados en Google Drive.

2. **Preprocesamiento de Datos:**
   - Limpieza y transformación de datos para prepararlos para el modelado.
   - Aplicación de SMOTE para abordar el desbalance de clases.

3. **Entrenamiento de Modelos:**
   - Utilización de algoritmos de clasificación para entrenar modelos.
   - Optimización de hiperparámetros para maximizar la precisión.

4. **Evaluación del Modelo:**
   - Evaluación del rendimiento del modelo en el conjunto de prueba.
   - Análisis de métricas como precisión, recall y F1-score.


## Notas Importantes

- Este notebook es una versión inicial y se ha abordado el desbalance de clases mediante la técnica de SMOTE.
- Los datos están almacenados en un Google Drive público, y no se requiere configuración adicional.
- Se recomienda revisar el código para comprender cada paso y ajustarlo según sea necesario.

¡Disfrute explorando el mundo del Death Metal a través de la clasificación automática de canciones! 🤘
