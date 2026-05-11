## Modelos Entrenados y Checkpoints
Esta carpeta contiene los archivos correspondientes a los estados finales de los modelos desarrollados en este TFG. Estos archivos permiten cargar las redes neuronales ya entrenadas para realizar inferencia sobre nuevas moléculas de heliceno sin necesidad de repetir el proceso de optimización.

## Descripción de los archivos
**Modelos de PyTorch**
6puntos.pt: Pesos del modelo entrenado utilizando exclusivamente los seis parámetros discretos de la base de datos de espectroscopía.

mixto.pt: Pesos del modelo que implementa la arquitectura Physics-Informed (PINN) mediante la función de pérdida mixta.

**Modelo de TensorFlow / Keras**
envolventes.keras: Archivo que contiene la arquitectura y los pesos del modelo dedicado a la predicción del espectro completo reconstruido.

metadatos_envolventes.pkl: Archivo de datos serializado que contiene la configuración necesaria (escalado y parámetros de funciones gaussianas) para el correcto funcionamiento del modelo de envolventes.
