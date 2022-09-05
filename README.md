# Clasificador de tipos de carnes que se utiliza en la industria real.

- Este repositorio está enfocado a la creación de un clasificador de tipos de carnes que se utiliza en la industria real, es un ejemplo simplificado, el modelo real utiliza imágenes de mayor resolución y el conjunto de entrenamiento es mucho mayor (requiriendo días para su entrenamiento). 


# El link para la descarga de las imágenes se encuentra disponible en el siguiente link:

   (https://drive.google.com/file/d/1Z5DJ-MVS1TQV1kow9mIFWTec-ZdOLRLF/view?usp=sharing) 

Tras descomprimir el archivo de drive obtendremos dos carpetas, la carpeta de entrenamiento y la carpeta de test. 

# OBJETIVOS:

1. Obtener un clasificador de imágenes de forma que dada una nueva imagen se pueda obtener la clase correspondiente.
2) Obtener las matrices de confusión del modelo, la matriz de confusión del error en training y la de test.

# REQUERIMIENTOS:
IMPORTAR LIBRERIAS BASADAS EN TENSORFLOW Y KERAS

- import sys
- import os
- from tensorflow.keras.preprocessing.image import ImageDataGenerator
- from tensorflow.keras import optimizers
- from tensorflow.keras.models import Sequential
- from tensorflow.keras.layers import Dropout, Flatten, Dense, Activation
- from tensorflow.keras.layers import  Convolution2D, MaxPooling2D
- from tensorflow.keras import backend as K
