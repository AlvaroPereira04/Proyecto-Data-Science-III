# Proyecto Final — Análisis de Reseñas de Netflix (NLP & Deep Learning)

**Autor:** Álvaro Vargas  
**Stack:** Python · Jupyter/Colab · pandas · NumPy · Matplotlib · Seaborn · scikit-learn · NLTK · spaCy · TensorFlow/Keras

Repositorio del proyecto final con **EDA** y **modelo de clasificación de sentimiento** sobre reseñas de la app de **Netflix**.

## 📦 Datos
- **Archivo:** `data/netflix_reviews.csv`  
- **Delimitador:** `,`  
- **Filas/Columnas:** **138957** / **8**  

**Carga rápida en pandas:**
```python
import pandas as pd
df = pd.read_csv("data/netflix_reviews.csv")
```

## 🗂 Estructura del repositorio
```
.
├─ data/
│  └─ netflix_reviews.csv
├─ notebooks/
│  ├─ Entrega_Final_NLP_DL_Netflix_Alvaro_Vargas.ipynb
│  └─ Entrega_Final_NLP_DL_Netflix_Alvaro_Vargas.html
├─ requirements.txt
├─ .gitignore
├─ LICENSE
└─ README.md
```

## ▶️ Ejecución
**Colab:** subí el CSV o montá Drive y ejecutá las celdas en orden.  
**Local (venv):**
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```
