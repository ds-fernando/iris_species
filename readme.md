# 🏷️ Proyecto: Clustering de Especies de Iris con K-means

![Image_Alt](https://miro.medium.com/v2/resize:fit:1400/0*11IwZmSKXw77eYz5)

## 📌 Descripción

Análisis de clustering no supervisado utilizando el algoritmo **K-means** sobre el dataset Iris, que contiene medidas morfológicas de tres especies de flores:

- Iris setosa
- Iris versicolor
- Iris virginica


## 📊 Descripción de Columnas (Dataset Iris)

| Nombre Columna            | Tipo de Dato | Unidad | Descripción                                                                 | Rango Típico         |
|---------------------------|--------------|--------|-----------------------------------------------------------------------------|----------------------|
| **sepal length (cm)**     | float64      | cm     | Longitud del sépalo (estructura verde que soporta el pétalo)               | 4.3 - 7.9 cm        |
| **sepal width (cm)**      | float64      | cm     | Ancho del sépalo                                                           | 2.0 - 4.4 cm        |
| **petal length (cm)**     | float64      | cm     | Longitud del pétalo (parte colorida de la flor)                            | 1.0 - 6.9 cm        |
| **petal width (cm)**      | float64      | cm     | Ancho del pétalo                                                           | 0.1 - 2.5 cm        |
| **species**               | int32/object | -      | Especie de la flor (`0`: Iris setosa, `1`: Iris versicolor, `2`: Iris virginica) | 0, 1, 2 o nombres   |

### 🌸 Contexto Biológico:
- **Sépalo**: Parte exterior de la flor, protege el capullo antes de florecer.  
- **Pétalo**: Parte interior, atrae polinizadores por su color y forma.  
- **Especies**:  
  - **Iris setosa**: Sépalos anchos, pétalos pequeños.  
  - **Iris versicolor**: Características intermedias.  
  - **Iris virginica**: Sépalos estrechos, pétalos grandes.  

### 📌 Notas:
- Dataset balanceado: 50 muestras por especie.  
- Todas las medidas son **numéricas continuas** excepto `species` (categórica).  

## 🛠️ Tecnologías

- Python 3.10+
- Scikit-learn (K-means, métricas)
- Pandas (procesamiento)
- Matplotlib/Seaborn (visualización)
- Jupyter Notebook (análisis interactivo)ç
