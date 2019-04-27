# Clasificación de dígitos usando Redes Convolucionales y Keras

Código fuente de [este](https://youtu.be/SGoxsBgp3WM) video, en donde se muestra la clasificación del set MNIST usando la red convolucional LeNet-5 y las librerías Tensorflow y Keras.

El set MNIST (Modified National Institute of Standards and Technology) contiene un total de 70.000 imágenes en escala de gris, cada una con un tamaño de 28x28 pixeles y que contiene un dígito (entre 0 y 9) escrito a mano por diferentes personas. Los sets de entrenamiento y validación tienen 60.000 y 10.000 imágenes respectivamente.

La precisión obtenida usando la red LeNet-5 (una de las precursoras de las redes convolucionales actuales) es cercana al 99%.

## Dependencias
numpy==1.15.1, matplotlib==2.2.3, scikit-learn==0.19.2, Keras==2.2.4, tensorflow==1.11.0