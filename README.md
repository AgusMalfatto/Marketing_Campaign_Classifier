# Marketing Campaign Classifier

## 📘 Introducción
Este proyecto tiene como objetivo construir un modelo de Machine Learning capaz de predecir la respuesta de los clientes ante campañas de marketing.  
El trabajo forma parte del curso de **Machine Learning de EducaciónIT** y está orientado al aprendizaje práctico: exploración, análisis, preprocesamiento, construcción y evaluación de modelos supervisados.

---

## 🔄 Flujo del Proyecto
El desarrollo se organizó siguiendo un pipeline típico de Machine Learning:

### 1. **Exploración del dataset (EDA inicial)**
- Carga del dataset y verificación de su estructura.
- Revisión de tipos de variables, distribución de datos y valores únicos.
- Identificación de outliers, correlaciones y comportamiento general de las variables.

### 2. **Análisis estadístico**
- Evaluación de métricas descriptivas para variables numéricas y categóricas.
- Cálculo de correlaciones.
- Insights sobre variables relevantes para el objetivo final.

### 3. **Tratamiento de valores faltantes**
- No se identificaron Nulls en este proceso por lo que no se requirió intervención.

### 4. **Preparación de variables**
- Codificación de variables categóricas.
- No se requirió escalado de variables.
- División en conjuntos de entrenamiento y prueba.
- No se requirió balanceo de variables.

### 5. **Entrenamiento de modelos**
Se entrenaron múltiples algoritmos para comparar performance:
- **Decision Tree Classifier**
- **K-Nearest Neighbors (KNN)**

### 6. **Evaluación de modelos**
- Accuracy
- Precision
- Recall
- F1-Score
- Matriz de confusión
- **Curva ROC y AUC**
- Comparación final entre modelos

---

## 🧰 Técnicas Aplicadas
El proyecto incorpora una variedad de técnicas de análisis y modelado:

- **EDA (Exploratory Data Analysis)**
- **Feature Engineering básico**
- **Limpieza y manipulación de datos**
- **Codificación de variables**
- **GridSearchCV para optimización de hiperparámetros**
- **Visualización con Matplotlib / Seaborn**
- **Matriz de confusión**
- **Curva ROC y cálculo del AUC**
- **Comparación de modelos**

---

## 📊 Comparación de Métricas de los Modelos

| Model | Accuracy | Precision | Recall | F1 Score |
|-|-|-|-|-|  
| KNN | 0.93 | 0.89 | 0.99 | 0.93 |
| Tree | 0.93 | 0.89 | 0.99 | 0.94 |

---

## 📚 Tecnologías utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Joblib

---

## 📁 Estructura del Repositorio

├── Mod3.ipynb                # Notebook principal del proyecto
├── Models/                   # Carpeta para almacenar el dataset procesado y los modelos entrenados
├── Datasets/                 # Dataset original
├── requirements.txt          # Dependencias del proyecto
└── README.md                 # Documentación del proyecto