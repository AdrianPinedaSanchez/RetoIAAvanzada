# AdrianPineda_RegresionLogistica_Week02_Challenge1

## Descripción
Este proyecto implementa un modelo de regresión logística desde cero, sin utilizar frameworks o bibliotecas externas, para resolver un problema de clasificación binaria. Se cumplen los requisitos del desafío especificado, entrenando el modelo por un mínimo de 100 iteraciones, seleccionando tasas de aprendizaje adecuadas y generando predicciones sobre un conjunto de prueba.

## Archivos en el repositorio

### 1. `AdrianPineda_RegresionLogistica_Week02_Challenge1.ipynb`
- **Descripción**: Este es el archivo principal del proyecto. Contiene todo el desarrollo del modelo de regresión logística, incluyendo la implementación, entrenamiento, validación y evaluación de las métricas. También incluye comentarios detallados para facilitar la revisión y comprensión del código.
- **Uso**: Puede abrirse y ejecutarse en Google Colab o cualquier entorno compatible con Jupyter Notebooks.

### 2. `AdrianPineda_RegresionLogistica_Week02_Challenge1.html`
- **Descripción**: Este archivo es la versión exportada del notebook en formato HTML. Es una copia exacta del contenido del notebook `.ipynb`, pero en un formato más fácil de visualizar en un navegador web.
- **Uso**: Se puede abrir en cualquier navegador web para revisar el contenido sin necesidad de ejecutar código.

### 3. `RegresionLogistica_ImagenReto_Week02Challenge01.png`
- **Descripción**: Esta es la imagen del problema planteado, la cual se utilizó como referencia para la implementación del modelo. Contiene las instrucciones y los datos necesarios para realizar el reto.
- **Uso**: Proporciona contexto visual del problema a resolver.

## Sección de Cambios Implementados
En este proyecto, se realizaron los siguientes cambios basados en la retroalimentación del docente:

- **Ajuste de la tasa de aprendizaje**: Se realizaron pruebas para encontrar el learning rate óptimo, lo cual mejoró significativamente el rendimiento del modelo.
- **Implementación de gráficos comparativos**: Se añadieron gráficos para comparar las predicciones del modelo con los valores reales del conjunto de prueba.
- **Cálculo de métricas de desempeño**: Se calcularon métricas clave (Accuracy, Precision, Recall, F1 Score) para validar la efectividad del modelo y comparar contra la referencia proporcionada.

## Instrucciones para la Revisión
1. Abra el archivo `AdrianPineda_RegresionLogistica_Week02_Challenge1.ipynb` en Google Colab o Jupyter Notebook para revisar el código y las ejecuciones.
2. Alternativamente, puede revisar el archivo `AdrianPineda_RegresionLogistica_Week02_Challenge1.html` en su navegador para ver el mismo contenido en un formato estático.
3. Consulte la imagen `RegresionLogistica_ImagenReto_Week02challenge01.png` para entender el problema inicial planteado.

## Criterios de Evaluación
Este proyecto cumple con los siguientes criterios:
- El modelo se implementó desde cero sin utilizar frameworks.
- Se entrenó por un mínimo de 100 iteraciones.
- Se seleccionaron valores para la tasa de aprendizaje y los parámetros iniciales.
- Se generaron predicciones y se compararon con los valores reales mediante gráficos.
- Se calcularon métricas de desempeño tanto para el entrenamiento como para el conjunto de prueba.

