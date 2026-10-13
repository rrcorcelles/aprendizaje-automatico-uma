# Aprendizaje Automático y Análisis Visual de Datos

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Nota](https://img.shields.io/badge/Calificación-9.9%2F10-brightgreen)

Prácticas resueltas del curso **Aprendizaje Automático y Análisis Visual de Datos** de la
**Universidad de Málaga (UMA)**, superado con una calificación final de **9,9 / 10**.

Cada práctica es un notebook de Jupyter completamente ejecutado, con el código comentado
y el análisis de los resultados obtenidos.

**Autor:** Jaime Rodrigo Roldán Corcelles

---

## 📚 Contenido

| # | Práctica | Temas principales | Notebook |
|---|----------|-------------------|----------|
| 1 | [Algoritmos básicos de clasificación](01-clasificacion-basica) | Perceptrón, Adaline (batch y estocástico), tasa de aprendizaje decreciente, visualización con Matplotlib | [`clasificacion_basica.ipynb`](01-clasificacion-basica/clasificacion_basica.ipynb) |
| 2 | [Algoritmos avanzados de clasificación](02-clasificacion-avanzada) | Regresión logística, SVM, árboles de decisión, k-NN, regiones de decisión | [`clasificacion_avanzada.ipynb`](02-clasificacion-avanzada/clasificacion_avanzada.ipynb) |
| 3 | [Calidad y preprocesado de datos](03-preprocesado-datos) | Datos incompletos, codificación de variables categóricas, estandarización, selección de rasgos, series temporales | [`preprocesado_datos.ipynb`](03-preprocesado-datos/preprocesado_datos.ipynb) |
| 4 | [Evaluación de modelos y métricas avanzadas](04-evaluacion-modelos) | Pipelines, validación cruzada, curvas de aprendizaje y validación, GridSearch, curva ROC, F1, clases desbalanceadas | [`evaluacion_modelos.ipynb`](04-evaluacion-modelos/evaluacion_modelos.ipynb) |
| 5 | [Algoritmos de regresión](05-regresion) | Análisis exploratorio, regresión lineal, RANSAC, Lasso, árboles de regresión, MSE y R² | [`regresion.ipynb`](05-regresion/regresion.ipynb) |

## 🗂️ Estructura del repositorio

```
aprendizaje-automatico-uma/
├── 01-clasificacion-basica/
│   ├── clasificacion_basica.ipynb   # Práctica resuelta
│   ├── data/                        # Conjuntos de datos utilizados
│   └── README.md
├── 02-clasificacion-avanzada/
├── 03-preprocesado-datos/
├── 04-evaluacion-modelos/
├── 05-regresion/
├── requirements.txt
└── README.md
```

## 🚀 Cómo ejecutarlo

```bash
git clone https://github.com/<tu-usuario>/aprendizaje-automatico-uma.git
cd aprendizaje-automatico-uma

python -m venv .venv
# Windows: .venv\Scripts\activate   |   Linux/macOS: source .venv/bin/activate
pip install -r requirements.txt

jupyter notebook
```

Los notebooks cargan los datos con rutas relativas (`data/...`), así que deben abrirse
desde su propia carpeta.

## 📊 Conjuntos de datos

Los datos utilizados son públicos y se incluyen solo con fines educativos:

- **Iris, Glass, Wine Quality, Credit Approval (crx), Ionosphere, Zoo, Breast Cancer Wisconsin, Real Estate Valuation**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- **Población y viviendas**: [Instituto Nacional de Estadística (INE)](https://www.ine.es/)
- **Datos históricos de S&P 500, Euro Stoxx 50 y EUR/USD**: series bursátiles públicas

## ⚖️ Nota

Los enunciados y el material docente pertenecen a la Universidad de Málaga y no se incluyen
en este repositorio. El código y las soluciones son trabajo propio.
