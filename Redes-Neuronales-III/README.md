# Redes Neuronales III - Deep Learning

Prácticas de optimización, regularización y evaluación de redes neuronales sobre MNIST, basadas en la guía de las semanas 5, 6 y 7.

## Notebooks principales
1. **01_Datos_Baseline_Keras.ipynb** - MNIST, Train/Dev/Test, normalización, distribución y baseline.
2. **02_Optimizacion_Hiperparametros.ipynb** - SGD + Momentum, RMSprop, Adam y tres learning rates.
3. **03_Regularizacion.ipynb** - comparación sin regularización frente a L2, Dropout y Early Stopping; análisis bias/variance.
4. **04_Metricas_Evaluacion.ipynb** - Accuracy, Precision macro, Recall macro, F1 macro, classification report, matriz de confusión y error real.
5. **05_PyTorch_Opcional.ipynb** - implementación equivalente con PyTorch (opcional, no necesario para la ruta principal).

## Cómo ejecutarlos
Abre cada notebook en Google Colab y ejecuta todas las celdas en orden. Los notebooks principales usan TensorFlow/Keras y descargan MNIST mediante `keras.datasets.mnist.load_data()`.

## Dataset y método
MNIST contiene imágenes de dígitos 0-9, cada una de 28 x 28 píxeles. El conjunto original de 60.000 imágenes se divide estratificadamente en 48.000 Train y 12.000 Dev. Las 10.000 imágenes de Test quedan reservadas para la evaluación final. Los píxeles se normalizan dividiendo entre 255.

## Qué documentar
Registra las salidas reales de la ejecución. Compara optimizadores y learning rates usando Dev; compara las curvas Train/Dev para estudiar overfitting; reporta Accuracy, Precision, Recall, F1, clasificación por clase, matriz de confusión y un error concreto. No inventes métricas ni uses Test para seleccionar configuraciones.

## Informe
El informe PDF se entrega por la plataforma institucional junto con los notebooks. Completa el documento técnico editable incluido en el paquete de trabajo con métricas y capturas reales y añade la URL de este repositorio. Esta carpeta de GitHub guarda el código fuente y las instrucciones de ejecución.

**Repositorio:** https://github.com/2Alejo0/DeepLearning/tree/main/Redes-Neuronales-III
