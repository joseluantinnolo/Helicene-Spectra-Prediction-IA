El proyecto implementa tres arquitecturas de Redes Neuronales para predecir propiedades moleculares basándose en datos de intensidad de emisión:

1.  **Modelo de Parámetros:** Basado en los 6 parámetros fundamentales de la base de datos (PyTorch).
2.  **Modelo de Envolventes:** Predicción del espectro reconstruido mediante funciones gaussianas a partir de parámetros físico-químicos (TensorFlow/Keras).
3.  **Modelo Mixto (Physics-Informed):** Una aproximación **PINN** que utiliza una función de pérdida mixta para integrar el conocimiento físico con el aprendizaje de datos (PyTorch).
