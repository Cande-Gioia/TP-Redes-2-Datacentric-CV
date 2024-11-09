

# TP2-Redes3-Datacentric-CV
En el siguiente repositorio se encuentra el Trabajo Práctico N°2 de Redes Neuronales 3.

El objetivo es realizar una búsqueda de hiperparámetros usando como dataser ImageNet tomando 20 clases con 100 imágenes cada una. El modelo usado se basó en una ResNet50. 
Una vez realizada esa búsqueda de hiperparámetros, se guardaron esto parámetros para luego realizar algumentation con la librería albumentations de python y volver a entrenar la red. Se utilizaron 5 tipos de pipelines para el algumentation, cada uno con sus respectivas funciones. Al final se muestra cuál pipeline presentó mejor accuracy.

## Integrantes:
- Juan Pablo Cilfone
- Bruno Di Sanzo
- Candela Gioia

##Código:
El repositorio contiene dos archivos. El primero correspondiente a la búsqueda de hiperámetros, mientras que el segundo corresponde a la parte de algumentations
