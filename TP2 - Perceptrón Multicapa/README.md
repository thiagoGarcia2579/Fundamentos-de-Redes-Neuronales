# TP2 - Perceptrón Multicapa

## Objetivo

Implementar un perceptrón multicapa para resolver problemas de clasificación no lineal y reconocimiento de patrones utilizando redes neuronales artificiales.

---

## Desarrollo del práctico

Durante este trabajo práctico se realizó:

* Implementación de un perceptrón multicapa (MLP)
* Entrenamiento mediante algoritmo de Backpropagation
* Resolución de problemas no lineales
* Clasificación de imágenes de dígitos
* Evaluación de capacidad de generalización
* Pruebas de robustez utilizando ruido sobre los datos de entrada

---

## Problemas analizados

### Función lógica XOR

Se entrenó un perceptrón multicapa para resolver la función lógica XOR.

A diferencia del perceptrón simple, el modelo multicapa logró aprender correctamente el problema gracias a su capacidad para representar relaciones no lineales.

---

### Clasificación par/impar de dígitos

Se utilizaron imágenes de dígitos representadas mediante matrices de 5x7 píxeles.

La red fue entrenada utilizando un subconjunto de los datos y posteriormente evaluada con muestras no vistas para analizar su capacidad de generalización.

---

### Reconocimiento de dígitos con ruido

Se implementó una red neuronal con diez neuronas de salida, una para cada dígito decimal.

Luego del entrenamiento, se agregaron alteraciones aleatorias en los píxeles de entrada para evaluar la robustez del modelo frente a ruido.

---

## Resultados obtenidos

* El perceptrón multicapa resolvió correctamente la función XOR.
* La red logró clasificar correctamente dígitos pares e impares.
* Se observó una buena capacidad de generalización utilizando conjuntos de entrenamiento y test.
* El modelo mantuvo un rendimiento estable aun con presencia de ruido en las entradas.
* Los gráficos permitieron visualizar el aprendizaje y desempeño de la red neuronal.

---

## Conceptos aplicados

* Redes neuronales artificiales
* Perceptrón multicapa (MLP)
* Backpropagation
* Clasificación de patrones
* Reconocimiento de imágenes
* Generalización
* Aprendizaje supervisado
* Machine Learning

---

## Informe

El informe completo del trabajo práctico se encuentra en el archivo adjunto:

**[Informe_TP2.pdf](./Informe_TP2.pdf)**
