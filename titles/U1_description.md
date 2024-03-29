# INTRODUCCIÓN AL MACHINE LEARNING

## ¿Qué es Machine Learning?  <br/>

**Definiciones básicas y aplicaciones típicas**:  [pdf](https://drive.google.com/file/d/1k8XDXGFka_LWfty32M8BcOT7rFtbpRkS/view?usp=sharing) <br/>Se introduce el concepto de Machine Learning y se discuten algunas aplicaciones típicas.

**Modelos controlados por datos**:   <br/>Se discuten los conceptos básicos de los modelos controaldos por datos que rigen a todos los modelos de ML.

**Tipos de aprendizaje automático**:  <br/> Se presentan los tipos de aprendizaje automático más comunes: supervisado, no supervisado, auto supervisado y por refuerzo, así como la nomenclatura matemática básica que se usa para representar los problemas supervisados y no supervisados.

**Aprendizaje supervisado: clasificación vs regresión**: <br/> Se explica la diferencia entre los problemas de aprendizaje supervisado conocidos como clasificación y regresión, así como sus formas de representación gráfica. 

**Componentes de un modelo de ML**: <br/> Se explican los tres componentes básicos que deben considerarse cuando se selecciona un modelo de ML y los diferentes niveles de abstracción en los que se puede aproximar una solución.


## Modelos básicos de aprendizaje  <br/>

**Regresión múltiple**: <br/> Se repasa el modelo de regresión múltiple y de los tres componentes básicos del modelo de acuerdo con las ideas discutidas en la sesión anterior, desde una perspectiva de alto nivel.

**Algoritmo de gradiente descendente**:  <br/> Se continúa con el análisis de la regresión múltiple desde perspectivas de mediano y bajo nivel, y para esta última se explica el funcionamiento del algoritmo de gradiente descendente.

**Regresión logística**:  <br/> Con base en un modelo de regresión y en el algoritmo de gradiente descedente se introduce el modelo de regresión logística que sirve para resolver problemas de clasificación y se explica su función de costo conocida como <em>cross-entropy</em>.

**Análisis del entrenamiento de una regresión logística**:  <br/> Se presentan algunos resultados de la ejecución del proceso de entrenamiento de un modelo de regresión logística, para ayudar a comprender el proceso de minimización de la función de costo a partir del algoritmo de gradiente descendente, la modificación iterativa de la frontera de decisión hasta alcanzar la ubicación óptima (de acuerdo con la función de costo) y su correspondiente interpretación en el espacio de búsqueda.

**Fronteras no lineales con regresión logística**:  <br/> Se discute cómo se pueden obtener fronteras de decisión no lineales usando el modelo de regresión logística y los ajustes que deben realizarse para su implementación.

## Modelos discriminativos vs modelos generativos   <br/>

**Funciones discriminantes Gausianas**: <br/> Se discuten los modelos generativos los cuales utilizan un principio de funcionamiento diferente para resolver los problemas de clasificación y se presenta el modelo de funcionaes discriminantes Gausianas, además se explica el criterio de Máxima Verosimilitud a partir del cual se estiman los parámetros del modelo.

**Modelos discriminante lineal, discriminante cuadrático y Naïve Bayes**:  <br/> Se presentan varios modelos derivados de las funciones discriminantes Gausianas a partir de diferentes configuraciones de la matriz de covarianza del modelo.
