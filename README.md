# Práctica 1 - Inteligencia Computacional
## Implementación de redes neuronales para el reconocimiento óptico de caracteres MNIST

### Redes neuronales simples
Red neuronal simple que consta de una capa de entrada y una capa de salida de tipo softmax. Este tipo de red es adecuada para tareas básicas de clasificación, como la categorización de dígitos en el conjunto de datos MNIST.

### Redes neuronales multicapa
Red neuronal multicapa, compuesta por una capa oculta con 256 unidades logísticas y una capa de salida de tipo softmax. Este tipo de arquitectura introduce mayor profundidad en comparación con una red simple, lo que le permite aprender representaciones más complejas de los datos.

### Redes neuronales convolutivas/convolucionales
Red neuronal convolutiva entrenada utilizando el método de gradiente descendente estocástico. Este tipo de red está especialmente diseñada para procesar datos en forma de imágenes y utiliza una arquitectura en la que se aplican filtros a las imágenes de entrenamiento con diferentes resoluciones. Estos filtros, también conocidos como kernels, realizan operaciones de convolución, lo que permite extraer características relevantes de las imágenes, como patrones o texturas importantes. La salida generada por cada operación de convolución se emplea como entrada para la siguiente capa de la red, creando una jerarquía de características.

### DeepLearning
Red neuronal usando ‘Deep Learning’: pre-entrenamiento de autoencoders para extraer caracteŕısticas de las imágenes usando técnicas no supervisadas y una red neuronal simple con una capa de tipo softmax.

### Redes neuronales más complejas
Red neuronal convolutiva integrada con técnicas de Deep Learning. Las redes convolutivas son especialmente eficaces en el procesamiento de datos espaciales como imágenes, ya que aplican filtros que permiten extraer características locales de manera eficiente. Esto se combina con el poder del Deep Learning, que incrementa la profundidad del modelo y permite la extracción jerárquica de características más complejas y relevantes para la tarea.
