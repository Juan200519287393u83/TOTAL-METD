

# 📘 Métodos Numéricos

Este repositorio reúne una colección completa de ejercicios, teoría y ejemplos prácticos relacionados con los **Métodos Numéricos**, fundamentales para resolver problemas matemáticos complejos mediante algoritmos computacionales.

Diseñado como un recurso educativo, está dirigido a estudiantes, docentes y profesionales en matemáticas aplicadas, ingeniería, informática y disciplinas afines. Aquí encontrarás código comentado, explicaciones teóricas, enlaces útiles y una estructura clara por temas.

---

## 🌐 ¿Qué son los Métodos Numéricos?

Los métodos numéricos son técnicas matemáticas utilizadas para encontrar soluciones aproximadas a problemas que no se pueden resolver de forma exacta mediante métodos analíticos. Gracias a estos métodos, es posible abordar desde simples ecuaciones algebraicas hasta complejos modelos de simulación.

Estas técnicas se aplican ampliamente en áreas como:
- 🔬 Física y simulación de sistemas dinámicos
- 🏗️ Ingeniería estructural y mecánica computacional
- 💹 Modelado financiero y económico
- 🌍 Predicción del clima y modelado ambiental
- 🧠 Ciencia de datos e inteligencia artificial

---

## 🎯 Objetivos del Repositorio

- Explicar los fundamentos matemáticos y computacionales de cada método.
- Proporcionar implementaciones limpias y funcionales en **Java**.
- Ofrecer ejercicios resueltos, pseudocódigo, y enlaces a recursos adicionales.
- Fomentar la comprensión aplicada, con enfoque en resolución de problemas reales.

---

## 🗂️ Índice de Contenidos

Cada módulo incluye teoría, ejemplos comentados, diagramas y código. A continuación se muestra la estructura principal del repositorio:

### 🔹 Fundamentos

- T1. Introducción a los Métodos Numéricos
  - Definición y clasificación
  - Error absoluto, relativo, y propagación de errores
  - Redondeo y truncamiento
  - Representación numérica y límites

### 🔹 Ecuaciones No Lineales

- T2. Métodos de Solución de Ecuaciones
  - Método de bisección
  - Método de la falsa posición
  - Método de Newton-Raphson
  - Método de la secante
  - Comparación de convergencia

### 🔹 Sistemas de Ecuaciones Lineales

- T3. Solución Numérica de Sistemas Lineales
  - Eliminación de Gauss
  - Eliminación de Gauss-Jordan
  - Método de Jacobi
  - Método de Gauss-Seidel
  - Condicionamiento de matrices

### 🔹 Cálculo Diferencial e Integral

- T4. Diferenciación e Integración Numérica
  - Derivación hacia adelante, atrás y centrada
  - Reglas de integración: Trapecio, Simpson 1/3 y 3/8
  - Error de integración

### 🔹 Interpolación y Ajuste

- T5. Interpolación y Ajuste de Funciones
  - Interpolación de Newton
  - Interpolación de Lagrange
  - Ajuste por mínimos cuadrados
  - Regresiones polinomiales y lineales

### 🔹 Ecuaciones Diferenciales

- T6. Solución de EDOs
  - Método de Euler
  - Método de Runge-Kutta de orden 2 y 4
  - Comparación de métodos

---

| Tema   | Enlace al Pseudocódigo                                                |
| ------ | --------------------------------------------------------------------- |
| Tema 1 | [pseudocodigos\_tema1.md](Tema1/pseudocódigos/pseudocodigos_tema1.md) |
| Tema 2 | [pseudocódigos\_tema2.md](Tema2/pseudocódigos/pseudocódigos_tema2.md) |
| Tema 3 | [pseudocódigos\_tema3.md](Tema3/pseudocódigos/pseudocódigos_tema3.md) |
| Tema 4 | [pseudocódigos\_tema4.md](Tema4/pseudocódigos/pseudocódigos_tema4.md) |
| Tema 5 | [pseudocódigos\_tema5.md](Tema5/pseudocodigos/pseudocódigos_tema5.md) |
| Tema 6 | [pseudocódigos\_tema6.md](Tema6/pseudocodigos/pseudocódigos_tema6.md) |

## 🔹 Tema 1 – Métodos Básicos

### 🌀 Overflow

| # | Ejercicio | Archivo |
|:-:|-----------|---------|
| 1 | Implementación 1 | [📄 Imple (1).java](./Tema1/Overflow/Imple%20(1).java) |
| 2 | Implementación 2 | [📄 Imple (2).java](./Tema1/Overflow/Imple%20(2).java) |
| 3 | Implementación 3 | [📄 Imple (3).java](./Tema1/Overflow/Imple%20(3).java) |
| 4 | Implementación 4 | [📄 Imple (4).java](./Tema1/Overflow/Imple%20(4).java) |
| 5 | Implementación 5 | [📄 Imple (5).java](./Tema1/Overflow/Imple%20(5).java) |

### 🌀 Redondeo
|  #  | Ejercicio        | Archivo                                              |
| :-: | ---------------- | ---------------------------------------------------- |
|  1  | Redondeo 1 | [📄 Codigo1.java](./Tema1/Redondeo/Codigo1.java) |
|  2  | Redondeo 2 | [📄 Codigo2.java](./Tema1/Redondeo/Codigo2.java) |
|  3  | Redondeo 3 | [📄 Codigo3.java](./Tema1/Redondeo/Codigo3.java) |
|  4  | Redondeo 4 | [📄 Codigo4.java](./Tema1/Redondeo/Codigo4.java) |
|  5  | Redondeo 5 | [📄 Codigo5.java](./Tema1/Redondeo/Codigo5.java) |

### 🌀 Truncamiento
|  #  | Ejercicio        | Archivo                                              |
| :-: | ---------------- | ---------------------------------------------------- |
|  1  | Truncamiento 1 | [📄 Imple (1).java](./Tema1/Truncamiento/Imple%20(1).java) |
|  2  | Truncamiento 2 | [📄 Imple (2).java](./Tema1/Truncamiento/Imple%20(2).java) |
|  3  | Truncamiento 3 | [📄 Imple (3).java](./Tema1/Truncamiento/Imple%20(3).java) |
|  4  | Truncamiento 4 | [📄 Imple (4).java](./Tema1/Truncamiento/Imple%20(4).java)|
|  5  | Truncamiento 5 | [📄 Imple (5).java](./Tema1/Truncamiento/Imple%20(5).java) |


## 🔹 Tema 2 – Métodos de Solución de Ecuaciones

### 🌀 Método de la secante 

|  #  | Ejercicio | Archivo                                                                 |
| :-: | --------- | ----------------------------------------------------------------------- |
|  1  | Secante 1 | [📄 Imple (1).java](./Tema2/M%C3%A9todo%20Secante/Imple%20%281%29.java) |
|  2  | Secante 2 | [📄 Imple (2).java](./Tema2/M%C3%A9todo%20Secante/Imple%20%282%29.java) |
|  3  | Secante 3 | [📄 Imple (3).java](./Tema2/M%C3%A9todo%20Secante/Imple%20%283%29.java) |
|  4  | Secante 4 | [📄 Imple (4).java](./Tema2/M%C3%A9todo%20Secante/Imple%20%284%29.java) |
|  5  | Secante 5 | [📄 Imple (5).java](./Tema2/M%C3%A9todo%20Secante/Imple%20%285%29.java) |

### 🌀 Método de bisección

|  #  | Ejercicio   | Archivo                                                                             |
| :-: | ----------- | ----------------------------------------------------------------------------------- |
|  1  | Bisección 1 | [📄 Imple (1).java](./Tema2/M%C3%A9todo%20de%20bisecci%C3%B3n/Imple%20%281%29.java) |
|  2  | Bisección 2 | [📄 Imple (2).java](./Tema2/M%C3%A9todo%20de%20bisecci%C3%B3n/Imple%20%282%29.java) |
|  3  | Bisección 3 | [📄 Imple (3).java](./Tema2/M%C3%A9todo%20de%20bisecci%C3%B3n/Imple%20%283%29.java) |
|  4  | Bisección 4 | [📄 Imple (4).java](./Tema2/M%C3%A9todo%20de%20bisecci%C3%B3n/Imple%20%284%29.java) |
|  5  | Bisección 5 | [📄 Imple (5).java](./Tema2/M%C3%A9todo%20de%20bisecci%C3%B3n/Imple%20%285%29.java) |

### 🌀 Método de la falsa posición

|  #  | Ejercicio        | Archivo                                                                                    |
| :-: | ---------------- | ------------------------------------------------------------------------------------------ |
|  1  | Falsa Posición 1 | [📄 Imple (1).java](./Tema2/M%C3%A9todo%20de%20falsa%20posici%C3%B3n/Imple%20%281%29.java) |
|  2  | Falsa Posición 2 | [📄 Imple (2).java](./Tema2/M%C3%A9todo%20de%20falsa%20posici%C3%B3n/Imple%20%282%29.java) |
|  3  | Falsa Posición 3 | [📄 Imple (3).java](./Tema2/M%C3%A9todo%20de%20falsa%20posici%C3%B3n/Imple%20%283%29.java) |
|  4  | Falsa Posición 4 | [📄 Imple (4).java](./Tema2/M%C3%A9todo%20de%20falsa%20posici%C3%B3n/Imple%20%284%29.java) |
|  5  | Falsa Posición 5 | [📄 Imple (5).java](./Tema2/M%C3%A9todo%20de%20falsa%20posici%C3%B3n/Imple%20%285%29.java) |

### 🌀 Método de Newton-Raphson

|  #  | Ejercicio        | Archivo                                                                                |
| :-: | ---------------- | -------------------------------------------------------------------------------------- |
|  1  | Newton-Raphson 1 | [📄 Imple (1).java](./Tema2/M%C3%A9todos%20de%20Newton%20Raphson/Imple%20%281%29.java) |
|  2  | Newton-Raphson 2 | [📄 Imple (2).java](./Tema2/M%C3%A9todos%20de%20Newton%20Raphson/Imple%20%282%29.java) |
|  3  | Newton-Raphson 3 | [📄 Imple (3).java](./Tema2/M%C3%A9todos%20de%20Newton%20Raphson/Imple%20%283%29.java) |
|  4  | Newton-Raphson 4 | [📄 Imple (4).java](./Tema2/M%C3%A9todos%20de%20Newton%20Raphson/Imple%20%284%29.java) |
|  5  | Newton-Raphson 5 | [📄 Imple (5).java](./Tema2/M%C3%A9todos%20de%20Newton%20Raphson/Imple%20%285%29.java) |


## 🔹 Tema 3 – Solución Numérica de Sistemas Lineales

### 🌀 Eliminación de Gauss

|  #  | Ejercicio               | Archivo                                                           |
| :-: | ----------------------- | ----------------------------------------------------------------- |
|  1  | Eliminación Gaussiana 1 | [📄 Imple 1.java](./Tema3/Eliminación%20Gaussiana/Imple%201.java) |
|  2  | Eliminación Gaussiana 2 | [📄 Imple 2.java](./Tema3/Eliminación%20Gaussiana/Imple%202.java) |
|  3  | Eliminación Gaussiana 3 | [📄 Imple 3.java](./Tema3/Eliminación%20Gaussiana/Imple%203.java) |
|  4  | Eliminación Gaussiana 4 | [📄 Imple 4.java](./Tema3/Eliminación%20Gaussiana/Imple%204.java) |
|  5  | Eliminación Gaussiana 5 | [📄 Imple 5.java](./Tema3/Eliminación%20Gaussiana/Imple%205.java) |

### 🌀 Eliminación de Gauss-Jordan

|  #  | Ejercicio      | Archivo                                                                           |
| :-: | -------------- | --------------------------------------------------------------------------------- |
|  1  | Gauss-Jordan 1 | [📄 Imple (1).java](./Tema3/M%C3%A9todo%20de%20Gauss-Jordan/Imple%20%281%29.java) |
|  2  | Gauss-Jordan 2 | [📄 Imple (2).java](./Tema3/M%C3%A9todo%20de%20Gauss-Jordan/Imple%20%282%29.java) |
|  3  | Gauss-Jordan 3 | [📄 Imple (3).java](./Tema3/M%C3%A9todo%20de%20Gauss-Jordan/Imple%20%283%29.java) |
|  4  | Gauss-Jordan 4 | [📄 Imple (4).java](./Tema3/M%C3%A9todo%20de%20Gauss-Jordan/Imple%20%284%29.java) |
|  5  | Gauss-Jordan 5 | [📄 Imple (5).java](./Tema3/M%C3%A9todo%20de%20Gauss-Jordan/Imple%20%285%29.java) |

### 🌀 Método de Gauss-Seidel

|  #  | Ejercicio      | Archivo                                                                           |
| :-: | -------------- | --------------------------------------------------------------------------------- |
|  1  | Gauss-Seidel 1 | [📄 Imple (1).java](./Tema3/M%C3%A9todo%20de%20Gauss-Seidel/Imple%20%281%29.java) |
|  2  | Gauss-Seidel 2 | [📄 Imple (2).java](./Tema3/M%C3%A9todo%20de%20Gauss-Seidel/Imple%20%282%29.java) |
|  3  | Gauss-Seidel 3 | [📄 Imple (3).java](./Tema3/M%C3%A9todo%20de%20Gauss-Seidel/Imple%20%283%29.java) |
|  4  | Gauss-Seidel 4 | [📄 Imple (4).java](./Tema3/M%C3%A9todo%20de%20Gauss-Seidel/Imple%20%284%29.java) |
|  5  | Gauss-Seidel 5 | [📄 Imple (5).java](./Tema3/M%C3%A9todo%20de%20Gauss-Seidel/Imple%20%285%29.java) |

### 🌀 Método de Jacobi
|  #  | Ejercicio | Archivo                                                                     |
| :-: | --------- | --------------------------------------------------------------------------- |
|  1  | Jacobi 1  | [📄 Imple (1).java](./Tema3/M%C3%A9todo%20de%20Jacobi/Imple%20%281%29.java) |
|  2  | Jacobi 2  | [📄 Imple (2).java](./Tema3/M%C3%A9todo%20de%20Jacobi/Imple%20%282%29.java) |
|  3  | Jacobi 3  | [📄 Imple (3).java](./Tema3/M%C3%A9todo%20de%20Jacobi/Imple%20%283%29.java) |
|  4  | Jacobi 4  | [📄 Imple (4).java](./Tema3/M%C3%A9todo%20de%20Jacobi/Imple%20%284%29.java) |
|  5  | Jacobi 5  | [📄 Imple (5).java](./Tema3/M%C3%A9todo%20de%20Jacobi/Imple%20%285%29.java) |

## 🔹 Tema 4 – Diferenciación e Integración Numérica

### 🌀 Método de Cuadratura Gaussiana

|  #  | Ejercicio              | Archivo                                                             |
| :-: | ---------------------- | ------------------------------------------------------------------- |
|  1  | Cuadratura Gaussiana 1 | [📄 Imple 1.java](./Tema4/MetodoCuadraturaGaussiana/Imple%201.java) |
|  2  | Cuadratura Gaussiana 2 | [📄 Imple 2.java](./Tema4/MetodoCuadraturaGaussiana/Imple%202.java) |
|  3  | Cuadratura Gaussiana 3 | [📄 Imple 3.java](./Tema4/MetodoCuadraturaGaussiana/Imple%203.java) |
|  4  | Cuadratura Gaussiana 4 | [📄 Imple 4.java](./Tema4/MetodoCuadraturaGaussiana/Imple%204.java) |
|  5  | Cuadratura Gaussiana 5 | [📄 Imple 5.java](./Tema4/MetodoCuadraturaGaussiana/Imple%205.java) |

### 🌀 Método de  Simpson 1/3

|  #  | Ejercicio                 | Archivo                                                                 |
| :-: | ------------------------- | ----------------------------------------------------------------------- |
|  1  | Simpson 1/3 - Ejercicio 1 | [📄 Imple (1).java](./Tema4/MetodoReglaSimpson1_3/Imple%20%281%29.java) |
|  2  | Simpson 1/3 - Ejercicio 2 | [📄 Imple (2).java](./Tema4/MetodoReglaSimpson1_3/Imple%20%282%29.java) |
|  3  | Simpson 1/3 - Ejercicio 3 | [📄 Imple (3).java](./Tema4/MetodoReglaSimpson1_3/Imple%20%283%29.java) |
|  4  | Simpson 1/3 - Ejercicio 4 | [📄 Imple (4).java](./Tema4/MetodoReglaSimpson1_3/Imple%20%284%29.java) |
|  5  | Simpson 1/3 - Ejercicio 5 | [📄 Imple (5).java](./Tema4/MetodoReglaSimpson1_3/Imple%20%285%29.java) |

### 🌀 Método de  Simpson 3/8

|  #  | Ejercicio                 | Archivo                                                                 |
| :-: | ------------------------- | ----------------------------------------------------------------------- |
|  1  | Simpson 3/8 - Ejercicio 1 | [📄 Imple (1).java](./Tema4/MetodoReglaSimpson3_8/Imple%20%281%29.java) |
|  2  | Simpson 3/8 - Ejercicio 2 | [📄 Imple (2).java](./Tema4/MetodoReglaSimpson3_8/Imple%20%282%29.java) |
|  3  | Simpson 3/8 - Ejercicio 3 | [📄 Imple (3).java](./Tema4/MetodoReglaSimpson3_8/Imple%20%283%29.java) |
|  4  | Simpson 3/8 - Ejercicio 4 | [📄 Imple (4).java](./Tema4/MetodoReglaSimpson3_8/Imple%20%284%29.java) |
|  5  | Simpson 3/8 - Ejercicio 5 | [📄 Imple (5).java](./Tema4/MetodoReglaSimpson3_8/Imple%20%285%29.java) |

### 🌀 Método de Trapecio

|  #  | Ejercicio              | Archivo                                                          |
| :-: | ---------------------- | ---------------------------------------------------------------- |
|  1  | Trapecio - Ejercicio 1 | [📄 Imple (1).java](./Tema4/MetodoTrapecio/Imple%20%281%29.java) |
|  2  | Trapecio - Ejercicio 2 | [📄 Imple (2).java](./Tema4/MetodoTrapecio/Imple%20%282%29.java) |
|  3  | Trapecio - Ejercicio 3 | [📄 Imple (3).java](./Tema4/MetodoTrapecio/Imple%20%283%29.java) |
|  4  | Trapecio - Ejercicio 4 | [📄 Imple (4).java](./Tema4/MetodoTrapecio/Imple%20%284%29.java) |
|  5  | Trapecio - Ejercicio 5 | [📄 Imple (5).java](./Tema4/MetodoTrapecio/Imple%20%285%29.java) |

## 🔹 Tema 5 – Interpolación y Ajuste de Funciones

### 🌀 Método de Interpolación Lineal

|  #  | Ejercicio              | Archivo                                                                |
| :-: | ---------------------- | ---------------------------------------------------------------------- |
|  1  | Interpolación Lineal 1 | [📄 Imple (1).java](./Tema5/Interpolación_Lineal/Imple%20%281%29.java) |
|  2  | Interpolación Lineal 2 | [📄 Imple (2).java](./Tema5/Interpolación_Lineal/Imple%20%282%29.java) |
|  3  | Interpolación Lineal 3 | [📄 Imple (3).java](./Tema5/Interpolación_Lineal/Imple%20%283%29.java) |
|  4  | Interpolación Lineal 4 | [📄 Imple (4).java](./Tema5/Interpolación_Lineal/Imple%20%284%29.java) |
|  5  | Interpolación Lineal 5 | [📄 Imple (5).java](./Tema5/Interpolación_Lineal/Imple%20%285%29.java) |

### 🌀 Método de Interpolación de Minimos Cuadrado

|  #  | Ejercicio           | Archivo                                                                             |
| :-: | ------------------- | ----------------------------------------------------------------------------------- |
|  1  | Mínimos Cuadrados 1 | [📄 Imple (1).java](./Tema5/Interpolación_de_Mínimos_Cuadrado/Imple%20%281%29.java) |
|  2  | Mínimos Cuadrados 2 | [📄 Imple (2).java](./Tema5/Interpolación_de_Mínimos_Cuadrado/Imple%20%282%29.java) |
|  3  | Mínimos Cuadrados 3 | [📄 Imple (3).java](./Tema5/Interpolación_de_Mínimos_Cuadrado/Imple%20%283%29.java) |
|  4  | Mínimos Cuadrados 4 | [📄 Imple (4).java](./Tema5/Interpolación_de_Mínimos_Cuadrado/Imple%20%284%29.java) |
|  5  | Mínimos Cuadrados 5 | [📄 Imple (5).java](./Tema5/Interpolación_de_Mínimos_Cuadrado/Imple%20%285%29.java) |

### 🌀 Método de Interpolación de Lagrange

|  #  | Ejercicio  | Archivo                                                                     |
| :-: | ---------- | --------------------------------------------------------------------------- |
|  1  | Lagrange 1 | [📄 Imple (1).java](./Tema5/Interpolación_de_lagrange/Imple%20%281%29.java) |
|  2  | Lagrange 2 | [📄 Imple (2).java](./Tema5/Interpolación_de_lagrange/Imple%20%282%29.java) |
|  3  | Lagrange 3 | [📄 Imple (3).java](./Tema5/Interpolación_de_lagrange/Imple%20%283%29.java) |
|  4  | Lagrange 4 | [📄 Imple (4).java](./Tema5/Interpolación_de_lagrange/Imple%20%284%29.java) |
|  5  | Lagrange 5 | [📄 Imple (5).java](./Tema5/Interpolación_de_lagrange/Imple%20%285%29.java) |


### 🌀 Método de Interpolación de Newton

|  #  | Ejercicio | Archivo                                                                   |
| :-: | --------- | ------------------------------------------------------------------------- |
|  1  | Newton 1  | [📄 Imple (1).java](./Tema5/Interpolación_de_newton/Imple%20%281%29.java) |
|  2  | Newton 2  | [📄 Imple (2).java](./Tema5/Interpolación_de_newton/Imple%20%282%29.java) |
|  3  | Newton 3  | [📄 Imple (3).java](./Tema5/Interpolación_de_newton/Imple%20%283%29.java) |
|  4  | Newton 4  | [📄 Imple (4).java](./Tema5/Interpolación_de_newton/Imple%20%284%29.java) |
|  5  | Newton 5  | [📄 Imple (5).java](./Tema5/Interpolación_de_newton/Imple%20%285%29.java) |

### 🌀 Método de Correlación

|  #  | Ejercicio     | Archivo                                                                 |
| :-: | ------------- | ----------------------------------------------------------------------- |
|  1  | Correlación 1 | [📄 Imple (1).java](./Tema5/Método_de_Correlación/Imple%20%281%29.java) |
|  2  | Correlación 2 | [📄 Imple (2).java](./Tema5/Método_de_Correlación/Imple%20%282%29.java) |
|  3  | Correlación 3 | [📄 Imple (3).java](./Tema5/Método_de_Correlación/Imple%20%283%29.java) |
|  4  | Correlación 4 | [📄 Imple (4).java](./Tema5/Método_de_Correlación/Imple%20%284%29.java) |
|  5  | Correlación 5 | [📄 Imple (5).java](./Tema5/Método_de_Correlación/Imple%20%285%29.java) |

### 🌀 Método de Regresión

|  #  | Ejercicio   | Archivo                                                               |
| :-: | ----------- | --------------------------------------------------------------------- |
|  1  | Regresión 1 | [📄 Imple (1).java](./Tema5/Método_de_regresion/Imple%20%281%29.java) |
|  2  | Regresión 2 | [📄 Imple (2).java](./Tema5/Método_de_regresion/Imple%20%282%29.java) |
|  3  | Regresión 3 | [📄 Imple (3).java](./Tema5/Método_de_regresion/Imple%20%283%29.java) |
|  4  | Regresión 4 | [📄 Imple (4).java](./Tema5/Método_de_regresion/Imple%20%284%29.java) |
|  5  | Regresión 5 | [📄 Imple (5).java](./Tema5/Método_de_regresion/Imple%20%285%29.java) |

## 🔹 Tema 6 – Solución de EDOs

### 🌀 Método de Euler

|  #  | Ejercicio | Archivo                                                 |
| :-: | --------- | ------------------------------------------------------- |
|  1  | Euler 1   | [📄 Imple (1).java](./Tema6/Euler/Imple%20%281%29.java) |
|  2  | Euler 2   | [📄 Imple (2).java](./Tema6/Euler/Imple%20%282%29.java) |
|  3  | Euler 3   | [📄 Imple (3).java](./Tema6/Euler/Imple%20%283%29.java) |
|  4  | Euler 4   | [📄 Imple (4).java](./Tema6/Euler/Imple%20%284%29.java) |
|  5  | Euler 5   | [📄 Imple (5).java](./Tema6/Euler/Imple%20%285%29.java) |

### 🌀  Método de Runge-Kutta

|  #  | Ejercicio     | Archivo                                                       |
| :-: | ------------- | ------------------------------------------------------------- |
|  1  | Runge-Kutta 1 | [📄 Imple (1).java](./Tema6/Runge-Kutta/Imple%20%281%29.java) |
|  2  | Runge-Kutta 2 | [📄 Imple (2).java](./Tema6/Runge-Kutta/Imple%20%282%29.java) |
|  3  | Runge-Kutta 3 | [📄 Imple (3).java](./Tema6/Runge-Kutta/Imple%20%283%29.java) |
|  4  | Runge-Kutta 4 | [📄 Imple (4).java](./Tema6/Runge-Kutta/Imple%20%284%29.java) |
|  5  | Runge-Kutta 5 | [📄 Imple (5).java](./Tema6/Runge-Kutta/Imple%20%285%29.java) |

### 🌀  Método de Taylor

|  #  | Ejercicio | Archivo                                                  |
| :-: | --------- | -------------------------------------------------------- |
|  1  | Taylor 1  | [📄 Imple (1).java](./Tema6/Taylor/Imple%20%281%29.java) |
|  2  | Taylor 2  | [📄 Imple (2).java](./Tema6/Taylor/Imple%20%282%29.java) |
|  3  | Taylor 3  | [📄 Imple (3).java](./Tema6/Taylor/Imple%20%283%29.java) |
|  4  | Taylor 4  | [📄 Imple (4).java](./Tema6/Taylor/Imple%20%284%29.java) |
|  5  | Taylor 5  | [📄 Imple (5).java](./Tema6/Taylor/Imple%20%285%29.java) |
















































