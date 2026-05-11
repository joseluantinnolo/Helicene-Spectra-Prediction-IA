# IA para la Predicción de Propiedades Moleculares en Helicenos

Este repositorio contiene el desarrollo de modelos de Deep Learning destinados a predecir el espectro de emisión de luz circularmente polarizada en moléculas de Heliceno. El objetivo principal es optimizar el tiempo de computación frente a las técnicas analíticas tradicionales de **Espectroscopía de Dicroísmo Circular (EDC)**.

## 1. Descripción del Proyecto
El proyecto implementa tres arquitecturas de Redes Neuronales para predecir propiedades moleculares basándose en datos de intensidad de emisión:

1.  **Modelo de Parámetros:** Basado en los 6 parámetros fundamentales de la base de datos (PyTorch).
2.  **Modelo de Envolventes:** Predicción del espectro reconstruido mediante funciones gaussianas a partir de parámetros físico-químicos (TensorFlow/Keras).
3.  **Modelo Mixto (Physics-Informed):** Una aproximación **PINN** que utiliza una función de pérdida mixta para integrar el conocimiento físico con el aprendizaje de datos (PyTorch).

## 2. Tecnologías Utilizadas
*   **Lenguaje:** Python 3.x
*   **Deep Learning:** PyTorch, TensorFlow/Keras
*   **Procesamiento de Datos:** NumPy, Pandas, Scipy (para funciones gaussianas)
*   **Visualización:** Matplotlib, Seaborn

## 3. Instalación y Uso
Para replicar este entorno, se recomienda el uso de un entorno virtual:

```bash
git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
cd nombre-del-repo
pip install -r requirements.txt
