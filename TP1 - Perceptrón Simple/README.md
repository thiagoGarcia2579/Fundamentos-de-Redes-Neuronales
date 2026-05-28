# TP1 - Perceptrón Simple

## Objetivo

Implementar distintos modelos de perceptrón simple para analizar problemas de clasificación lineal y no lineal, evaluando además la capacidad de generalización de los modelos.

---

## Desarrollo del práctico

Durante este trabajo práctico se realizó:

* Implementación de un perceptrón simple con función de activación escalón
* Resolución de compuertas lógicas utilizando aprendizaje supervisado
* Evaluación de separación lineal y no lineal
* Implementación de perceptrón lineal
* Implementación de perceptrón no lineal
* Análisis de error cuadrático medio (MSE)
* Evaluación de generalización mediante conjuntos de entrenamiento y test
* Comparación entre modelos lineales y no lineales

---

## Problemas analizados

### Función lógica AND

Se entrenó un perceptrón simple utilizando entradas binarias para aprender la compuerta lógica AND.

El modelo logró converger correctamente, alcanzando error igual a cero y encontrando un hiperplano capaz de separar las clases.

---

### Función lógica XOR

Se evaluó el comportamiento del perceptrón simple frente al problema XOR.

El modelo no logró converger debido a que el problema no es linealmente separable, demostrando las limitaciones del perceptrón monocapa con activación escalón.

---

### Perceptrón lineal y no lineal

Se entrenaron modelos lineales y no lineales utilizando conjuntos de datos numéricos.

El modelo lineal presentó limitaciones para representar relaciones complejas, mientras que el modelo no lineal obtuvo un desempeño significativamente mejor.

---

### Generalización

Se dividieron los datos en subconjuntos de entrenamiento y test para evaluar la capacidad de generalización del modelo.

Los resultados mostraron errores bajos tanto en entrenamiento como en test, indicando que el modelo logró aprender la función subyacente sin memorizar las muestras.

---

## Resultados obtenidos

* El perceptrón simple resolvió correctamente la compuerta AND.
* El modelo no pudo resolver la función XOR debido a la falta de separabilidad lineal.
* El perceptrón no lineal obtuvo un error considerablemente menor que el lineal.
* Se observó una buena capacidad de generalización utilizando conjuntos de entrenamiento y test.
* Los gráficos permitieron analizar la evolución del aprendizaje y el comportamiento del error.

---

## Conceptos aplicados

* Redes neuronales artificiales
* Perceptrón simple
* Aprendizaje supervisado
* Separabilidad lineal
* Clasificación no lineal
* Funciones de activación
* Error cuadrático medio (MSE)
* Generalización
* Machine Learning

---

## Informe

El informe completo del trabajo práctico se encuentra en el archivo adjunto:

**[Informe_TP1.pdf](./Informe_TP1.pdf)**
