# Clasificador-de-Digitos-MNIST
Este repo contiene un notebook Colab que implementa un flujo profesional completo de clasificación de imágenes usando el dataset MNIST (dígitos manuscritos). Está orientado a proyectos universitarios y másteres de IA, presentando buenas prácticas y código reproducible, entrenando y comparando modelos de Scikit-learn (Random Forest, SVM) y una red neuronal sencilla con PyTorch.

## Características principales

- Limpieza y estandarización de datos con `StandardScaler`.
- Visualización interactiva con Matplotlib y Seaborn.
- Comparación de diversos clasificadores (Random Forest: búsqueda automática de hiperparámetros, SVM y MLP con PyTorch).
- Evaluación avanzada usando matriz de confusión y métricas como precision, recall y f1-score.
- Código modular y listo para adaptarse a otros datasets o algoritmos.

## ¿Qué hace el notebook?
1. **Prepara los datos**: carga y limpia el dataset MNIST.
2. **Visualiza ejemplos** de los datos para exploración visual.
3. **Entrena múltiples clasificadores**: realiza tuning y ajuste para Random Forest, y entrena un modelo SVM y una red neuronal MLP en PyTorch.
4. **Evalúa cuantitativamente** cada modelo usando métricas académicas estándar y visualización de la matriz de confusión.
5. **Presenta conclusiones** con una comparación final de resultados para fundamentar posibles mejoras o trabajos futuros.
