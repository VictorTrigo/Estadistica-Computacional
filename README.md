# Estadistica-Computacional

Estadística Computacional es una asignaura obligatoria en el programa de Doctorado en Estadística de la Universidad de Valparaiso, dictada por el profesor Ph. D. Rodrigo Salas.


# Contenido del curso

### 1. Introducción a lenguajes de programación

- Estructuras de datos y Estructuras de Control
- Programación orientada a objetos
- Manejo de archivos y base de datos

### 2. Métodos Numericos de Algebra Lineal

- Resolución de sistemas lineales
- Métodos de descomposición de matrices:
  - de Cholesky
  - LU y QR
  - Schur
- Aplicación de las  técnicas para la descomposicio de:
  - matriz de varianza-covarianza
  - valores singulares
- Análisis de Componentes Principales (PCA)

### 3. Métodos Númericos de optimización para la estimación de parámetros

- Metodo de Newton-Raphson
- Método de Levenberg-Marquardt
- Aplicación de problemas de mínimos cuadrados, estimadores máximo verosímil
- Algoritmo de Expectación-Maximización
- Regla del descenso del gradiente

### 4. Generación de números aleatorios y variables aleatorias

- Generador de números aleatorios uniformes
- Método de la transformada inversa
- Método de aceptación-rechazo

### 5. Funciones de densidades de probabilidad

- Problemas de estimación en una dimensión
- Histogramas
- Métodos basados en Kernel

### 6. Técnicas de remuestreo Bootstrap

- Aplicaciones de las técnicas de bootstrap para la obtención de estimadores
- Estimación del error estándar
- Obtención de intervalos de confianza

### 7. Cadenas de Markov

- Algoritmo de Metropolis-Hasting
- Muestreo de Gibbs


# Tecnologías

- [Python](https://www.python.org/)
: [Numpy](https://numpy.org/), [Scipy](https://scipy.org/), [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/), [Statsmodels](https://www.statsmodels.org/stable/index.html), [Scikit-Learn](https://scikit-learn.org/stable/), [Keras-Tensorflow](https://www.tensorflow.org/)

- [GitHub](https://github.com/VictorTrigo)
: Sistema de control de versiones

- [Colab](clase01.ipynb)
: Computo en la nube

- [Kaggle](https://www.kaggle.com/victortrigo)
: Repositorio de datos, Jupyter Notebooks, cursos y Challenges

- [Anaconda](https://www.anaconda.com/)
: Framework para Data Science


# [Lección 1](leccion01.ipynb): Programación en Python

- Tipos de datos: ()

- Operadores aritmeticos: (+, -, *, /, //, %)

- Operadores relacionales: (==, !=, <, >, <=, >=)

- Operadores lógicos: (and, or, not, xor) 

- Estructuras de datos: (dict, list, range, set, tuple, array, matrix, DataFrame)

- Estructuras de control: (if, elif, else, for, while)

- Funciones y Algoritmos: Uso de lo aprendido para crear funciones y algoritmos



# [Lección 2](leccion02.ipynb): Algoritmos

Algoritmos:
 - Primer algoritmo (desarrollado por Al-Juarismi)
 - Definición y caracteristicas de un algoritmo
 - Principales desafios con algritmos
 - Analisis de Algoritmos

Resolucion de problemas:
 - Ordenamiento
 - Busqueda
 - Procesamiento de cadenas de caracteres (string)
 - Problemas con graficos
 - Problemas conmbinatoriales
 - Problemas geometricos
 - Problemas numéricos

Análisis de Algoritmos
 - Correctitud
 - Eficiencia temporal
 - Eficiencia en almacenamiento

Estrategias de Diseño de Algoritmos:
 - Fuerza bruta
 - Divide y conquista
 - Disminuir y conquistar
 - Transformar y conquistar
 - Enfoque Greedy
 - Programación dinámica
 - Backtracking y branch-and-bound
 - Compromiso espacio y tiempo

Algoritmos de Ordenamiento:
 - Algoritmo por selección
 - Algoritmo por inserción
 - Algoritmo de Mezcla
 - Algoritmo Quickstort
 - Algoritmo Heap





# [Lección 3](leccion03.ipynb): Computación en Estadística

Programación de Medidas Estadísticas
 - Promedio Aritmetico
 - Varianza
 - Maximo y Minimo
 - Estadísticos de orden (algoritmo burbuja)
 - Cuartiles
 - Percentiles
 - Moda
 - Momentos Muestrales (y centrados)
 - Sesgo y Curtosis
 - Promedio Truncado
 - Median Absolute Deviation
 - Covarianza y Correlacion
 - Función de Distribución Empírica

Otros:
 - Histograma de Frecuencia
 - Grafico de barras
 - Grafico de dispersión
 - Tabla de Frecuencias


# [Lección 4](clase04.ipynb): Algoritmos de Búsqueda y Ordenamiento

Problema: Dada una lista de n ítemes ordenables, reubicar sus elementos de forma no-decreciente.

- Selection Sort: Se busca el elemento mas pequeño y se reemplaza por el primer elemento y se repite para el resto de posiciones.

- Bubble Sort: Se comparan los dos elementos adyacentes y se intercambian si están desordenados.

- Merge Sort: Divide una lista en dos mitades hasta obtener una lista simple de ordenar (dos elementos) y se procede a ordenar.

- Quick Sort (Algoritmo de Partición de Hoare): Se elige un elemento L de la lista divideindo la lista en dos; los elementos menores a L y los elementos mayores a L y L queda en su lugar, y repite.

Se requiere conocer complejidad temporal y espacial de los algoritmos para decidir cual es mas adecuado para x-problema.


# [Lección 5](clase05.ipynb): Análisis de la Complejidad de los Algoritmos

Análisis del Tiempo de Ejecución: 
 - Análisis del peor-caso, caso-promedio y mejor-caso
 - Tiempos de Ejecición para distintos tamaños de entrada

Funciones de Crecimiento
 - Notación Asintótica
 - Propiedades de las notaciones de crecimiento asintóticas
 - Comportamiento Asintótico de los Polinomios 

# [Lección 6](clase06.ipynb): Estategias de Diseños de Algoritmos

 - Fuerza Bruta
 - Búsqueda Exhaustiva
 - Decrece y Conquista
 - Divide y Conquista
 - Transforma y Conquistar


# [Lección 7](clase07.ipynb): Analisis de Error

Tipos de Error
 - Tipos y Fuentes de Error
 - Tipos de Análisis de Error
 - Exactitud vs Precisión

Errores de Redondeo
 - Definicioón de Redondeo
 - Definición de Error
 - Dígitos Significativos
 - Precisión de la Máquina

Aritmética del Punto Flotante

Problemas Bien Condicionados
 - Definiciones

Ejemplos Reales de Errores Numéricos
 - La Falla del Misil Patriot
 - La Explosión del Ariane 5


# [Lección 8](clase08.ipynb): Ecuaciones No Lineales

Solución Numérica de Ecuaciones No-Lineales

Métodos de Localización de Raíces
 - Método de la Bisección
 - Método de Regula Falsei
 - Método de Newton
 - Método de Diferencias Finitas de Newton
 - Método de la Secante

Criterios de Parada

Métoro del Punto Fijo

Scipy de Python


# [Lección 9](clase09.ipynb): Sistema de Ecuaciones No Lineales

 - Sistemas de Ecuaciones No-Lineales
 - Expansión de Taylor
 - Método de Newton
 - Método de Newton de Diferencias Finitas
 - Método de la Secante
 - Método de Broyden

















