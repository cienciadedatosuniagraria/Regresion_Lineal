# MODELO DE PREDICCIÓN: REGRESIÓN LINEAL EN PYTHON

Este repositorio contiene un **Jupyter Notebook** que implementa modelos básicos de predicción mediante **regresión lineal**. Usando datasets populares como Titanic, Tips e Iris, exploramos cómo predecir valores numéricos basados en variables independientes, analizar métricas de desempeño y visualizar los resultados.

---

## Contenido del Notebook

### **1. Dataset Titanic**
#### Objetivo: Predecir la tarifa (`fare`) en función de la edad (`age`).
- **Preparación de Datos:**
  - Selección de variables independientes (`age`) y dependientes (`fare`).
  - Tratamiento de valores faltantes: imputación con la mediana.
  - División del dataset en conjuntos de entrenamiento y prueba.

- **Entrenamiento del Modelo:**
  - Implementación de regresión lineal con `LinearRegression` de `sklearn`.
  - Entrenamiento del modelo con los datos de entrenamiento.

- **Evaluación del Modelo:**
  - Métricas de desempeño:
    - **Error Cuadrático Medio (MSE):** 1617.93
    - **Coeficiente de Determinación (R²):** 0.0125
  - Visualización de resultados:
    - Representación de la línea de regresión y datos de prueba.

---

### **2. Dataset Tips**
#### Objetivo: Predecir la propina (`tip`) en función de la factura total (`total_bill`).
- **Preparación de Datos:**
  - Selección de `total_bill` como variable independiente y `tip` como dependiente.
  - División de datos en entrenamiento y prueba.

- **Entrenamiento del Modelo:**
  - Creación y ajuste de un modelo de regresión lineal.

- **Evaluación del Modelo:**
  - Métricas de desempeño:
    - **Error Cuadrático Medio (MSE):** 0.569
    - **Coeficiente de Determinación (R²):** 0.545
  - Visualización:
    - Relación entre propina y factura total con la línea de regresión.

---

### **3. Dataset Iris**
#### Objetivo: Predecir la longitud del pétalo (`petal_length`) en función del ancho del pétalo (`petal_width`).
- **Preparación de Datos:**
  - Selección de `petal_width` como variable independiente y `petal_length` como dependiente.
  - División de datos en conjuntos de entrenamiento y prueba.

- **Entrenamiento del Modelo:**
  - Creación de un modelo de regresión lineal y ajuste con los datos de entrenamiento.

- **Evaluación del Modelo:**
  - Métricas de desempeño:
    - **Error Cuadrático Medio (MSE):** 0.234
    - **Coeficiente de Determinación (R²):** 0.929
  - Visualización:
    - Relación entre ancho y longitud del pétalo representada gráficamente.

---

## Requisitos

- **Python 3.x**
- Bibliotecas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

Instala las dependencias con:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
