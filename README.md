# README - Proyecto de Investigación de Análisis de Datos

Este proyecto tiene como objetivo la aplicación de técnicas de análisis de datos sobre un conjunto de datos determinado, utilizando un enfoque supervisado y no supervisado, aplicando varios algoritmos y métodos de optimización para mejorar los resultados. A continuación, se describe la estructura y las actividades realizadas a lo largo de este trabajo.

---

## 0. **Objetivo del Proyecto**

El objetivo principal de este proyecto es investigar y aplicar técnicas de análisis de datos en un conjunto de datos elegido, utilizando diversos métodos estadísticos y algoritmos de aprendizaje automático. El propósito es explorar cómo estas técnicas pueden mejorar la precisión y la eficiencia en la clasificación y predicción de datos. 

### **Objetivos específicos**:
- Realizar un análisis de datos mediante preprocesamiento, balanceo y selección del clasificador adecuado.
- Aplicar técnicas de reducción de dimensionalidad (PCA) para mejorar los resultados obtenidos con los clasificadores.
- Explorar tanto enfoques supervisados como no supervisados para comprender la relación entre las variables del conjunto de datos.
- Resolver el problema de las N-reinas usando el algoritmo de **Simulated Annealing**, comparando su rendimiento con enfoques de análisis combinatorio.

---

## 1. **Parte 1: Proceso Básico de Análisis de Datos**

### **Preprocesamiento y Balanceo de Datos**:
- **Preprocesamiento**: Se aplica un proceso básico de limpieza de datos, eliminando valores nulos, normalizando y estandarizando características según sea necesario. En algunos casos, el balanceo de clases se realiza para asegurar que el clasificador no se vea sesgado por clases desbalanceadas.
- **Balanceo de Datos**: Se lleva a cabo un balanceo para asegurar que el conjunto de datos tenga una distribución equilibrada entre las clases, utilizando técnicas como **SMOTE** o **undersampling** cuando es necesario.

### **Selección del Clasificador**:
- El clasificador elegido depende de la naturaleza del problema (supervisado o no supervisado). En este caso, se emplea un enfoque supervisado para la clasificación.
- **Justificación del Clasificador**: Se selecciona un clasificador adecuado (por ejemplo, regresión logística, SVM, o árboles de decisión), basado en las características del dataset y los resultados esperados. Se justifica la elección del clasificador según literatura y fuentes confiables (ISBN, DOI).

### **Primera Ejecución**:
- **Confiabilidad y Evaluación del Modelo**: En esta fase, se ejecutan el clasificador sobre un conjunto de datos de entrenamiento y se evalúa utilizando métricas como la **precisión**, **recall**, **F1-score** y la **matriz de confusión**.
- **División de Datos**: Se dividen los datos en dos conjuntos: 80% para entrenamiento y 20% para prueba, con el fin de evaluar el rendimiento del modelo.
- **Splits**: Se realizan al menos 100 asignaciones aleatorias, y se calcula la mediana de la confiabilidad en estas ejecuciones.

---

## 2. **Parte 2: Optimización del Modelo y Análisis No Supervisado**

### **Aplicación de PCA (Análisis de Componentes Principales)**:
- **PCA**: Se implementa la técnica de PCA para reducir la dimensionalidad del dataset, eliminando características irrelevantes mientras se preserva la mayor varianza posible.
- **Determinación de la cantidad óptima de componentes**: Se realiza un análisis para determinar cuántos componentes principales son necesarios para mantener un rendimiento adecuado en el clasificador. Se evalúan ejecuciones con 12, 10, 9, 5 y 3 componentes.
- **Explicación de PCA**: Se proporciona una explicación matemática de cómo funciona PCA, utilizando álgebra lineal para describir cómo se proyectan los datos en un espacio de menor dimensión.

### **Aprendizaje No Supervisado**:
- **Análisis No Supervisado**: Sin considerar la variable objetivo (“y” o la clase), se realiza un análisis exploratorio utilizando técnicas de aprendizaje no supervisado, como el **k-means clustering** o **algoritmos de reducción de dimensionalidad** para descubrir patrones en los datos.

### **Segundo Código**:
- Se utiliza plataformas como **GitHub**, **Kaggle** y **Colab** para almacenar y ejecutar los códigos utilizados en este proceso.

---

## 3. **Parte 3: Resumen y Artículo Final**

### **Artículo de Investigación**:
- Se escribe un artículo académico de al menos **4 páginas** que detalla todo el proceso realizado en el proyecto, desde la elección del dataset y la justificación del clasificador, hasta la implementación de PCA y el análisis no supervisado.
  
### **Resumen**:
- El artículo incluye un resumen de los resultados obtenidos con los clasificadores, la mejora de la precisión mediante el uso de PCA, y las observaciones sobre los métodos de optimización utilizados.
- Se incluye una discusión sobre el rendimiento comparativo entre el análisis combinatorio y **Simulated Annealing** para el problema de las N-reinas, destacando sus ventajas y desventajas.

---

## 4. **Parte 4: Resolución del Problema de las N-Reinas**

### **Resolución con Simulated Annealing**:
- El algoritmo de las **N-reinas** se resuelve utilizando el algoritmo **Simulated Annealing**, que es un enfoque heurístico que busca una solución de manera eficiente sin necesidad de evaluar todas las combinaciones posibles.
- **Comparación con Análisis Combinatorio**: Se comparan los resultados del enfoque de Simulated Annealing con el análisis combinatorio tradicional, demostrando que el primero es más eficiente en términos de tiempo, especialmente cuando el tamaño del tablero aumenta.

---

## 5. **Conclusiones**

Este proyecto abarca varias técnicas de análisis de datos, desde el preprocesamiento y selección de clasificadores, hasta la optimización de modelos mediante PCA y análisis no supervisado. También se incluye una exploración sobre la resolución de problemas de optimización, como el problema de las N-reinas, utilizando Simulated Annealing.

El enfoque utilizado demuestra ser eficaz para obtener soluciones de clasificación y optimización, con resultados comparativos que permiten observar las ventajas de los métodos heurísticos frente a los enfoques combinatorios.

---

### **Estructura de Archivos**:
- **0.Objetivo.pdf**: Documento que describe el objetivo del proyecto y las actividades realizadas.
- **3.Resumen.pdf**: Artículo final que resume todo el trabajo y presenta los resultados obtenidos.
- **Código**: Los códigos correspondientes a cada fase del proyecto están disponibles en los siguientes repositorios de GitHub, Kaggle y Colab.

