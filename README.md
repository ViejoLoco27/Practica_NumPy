# NumPy | Análisis numérico
##### Este documento contiene un ejercicio recuperado del Plan de Estudios Tech Foundation - Especialización en Data Science de la plataforma Alura Latam.
##### El dataset que se usa para el ejercicio fue obtenido de Kaggle. <https://www.kaggle.com/datasets/joshmcadams/oranges-vs-grapefruit>

## 👨‍💻Objetivos:
- 🎯Cargar archivo: Oranges V.S Grapefruits
- 🎯 Importar librería NumPy.
- 🎯Generar gráficos.
- 🎯 Calcular el coeficiente angular.
- 🎯 Calcular coeficiente lineal.


## Descripción de la base de datos 

### 🍊Naranja v.s. toronjas

Este conjunto de datos toma el color, peso y diámetro de una naranja y una toronja "promedio" y genera un conjunto de datos más grande con una amplia variedad de valores clasificados como "naranjas" y "toronjas".

### 📂 Contenido

El conjunto de datos es mayormente ficticio. Me encantaría recopilar datos reales, pero por ahora, medir frutas iniciales y generar muestras artificiales a partir de ellas parece suficiente.

## Step by step

### Regresión lineal

$$\alpha = pendiente$$
$$\beta = interseccion$$
$$n = observaciones$$
$$y = precio$$
$$x = fecha$$


La solución para la pendiente es:

$$\alpha = \frac{n \sum xy - \sum x \sum y}{n \sum x^2 - (\sum x)^2} $$

Y para la intersección:
 $$\beta = \frac{\sum y - \alpha \sum x}{n} $$

Y obtenemos la ecuación de la recta:

$$y = \alpha x + \beta $$


## Conclusión

Los diagramas de dispersión de ambos frutos( naranjas y toronjas) muestran una correlación entre el peso y el diámetro de cada una de estas. 

