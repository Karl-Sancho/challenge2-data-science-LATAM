# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

Este proyecto tiene como objetivo analizar los factores que influyen en la pérdida de clientes en la empresa Telecom X, utilizando herramientas de análisis de datos en Python. A partir de los datos históricos, se identifican patrones y se proponen estrategias para reducir el churn.

---

## ⚙️ Instalación

### 1. Clona este repositorio
```bash
git clone [https://github.com/tu-usuario/TelecomX_Churn.git](https://github.com/Karl-Sancho/Proyect_TelecomX_LATAM.git)
cd TelecomX_Churn
```

### 2. Crea y activa un entorno virtual (opcional pero recomendado)
```bash
python -m venv env
source env/bin/activate      # Linux/macOS
env\Scripts\activate       # Windows
```

### 3. Instala las dependencias
```bash
pip install -r requirements.txt
```

---

## 🧪 Dependencias principales

- `pandas` (análisis de datos)
- `matplotlib`, `seaborn` (visualizaciones)
- `scikit-learn` (modelado y preprocesamiento)
- `numpy`

Si no tienes un archivo `requirements.txt`, puedes generarlo así:
```bash
pip freeze > requirements.txt
```

---

## 🚀 Cómo ejecutar el análisis

### 1. A través de Jupyter Notebook
Ejecuta los análisis exploratorios y gráficos desde:
```bash
jupyter notebook notebooks/analisis_churn.ipynb
```

### 2. Ejecutar el script principal (si está disponible)
```bash
python scripts/analisis_principal.py
```

Este script carga los datos, realiza limpieza, análisis y exporta resultados.

---

## 🐞 Posibles problemas y soluciones

| Problema | Solución |
|---------|----------|
| `ModuleNotFoundError` | Asegúrate de haber instalado las dependencias con `pip install -r requirements.txt`. |
| Error con datos | Verifica que los archivos en la carpeta `data/` estén en el formato correcto (CSV limpio). |
| Problemas al exportar visualizaciones | Asegúrate de tener permisos de escritura en la carpeta `outputs/`. |

---

## 📬 Contacto

Para dudas o mejoras, contacta a: [carlossanchezpalacios2@gmail.com]
