# 📊 Titanic Data Analysis App with Streamlit

Este proyecto es una aplicación web interactiva desarrollada como parte del módulo de **Streamlit**.  
Permite explorar, visualizar y predecir datos del histórico **dataset del Titanic**, utilizando herramientas de análisis de datos e inteligencia artificial.

---

## 🚀 ¿Qué puedes hacer con esta app?

🔍 Explorar los datos con filtros dinámicos:  
- Edad, clase, tarifa, sexo, embarque, etc.

📊 Generar gráficos personalizados con Plotly:  
- Barras, pasteles, treemaps, heatmaps y más

📈 Consultar estadísticas descriptivas  
🧠 Predecir si un pasajero habría sobrevivido usando un modelo de Machine Learning (Random Forest)

---

## 🛠️ Tecnologías utilizadas

- [Python](https://www.python.org/)  
- [Streamlit](https://streamlit.io/) – para construir la app web  
- [Pandas](https://pandas.pydata.org/) – para manipulación de datos  
- [Plotly](https://plotly.com/python/) y [Seaborn](https://seaborn.pydata.org/) – para visualización  
- [Scikit-learn](https://scikit-learn.org/) – para el modelo predictivo  
- Dataset cargado desde AWS S3

---

## 📦 Requisitos

- Python 3.8+
- pip
- Recomendado: entorno virtual (venv)

---

## 🔧 Instalación y ejecución

1. Clona este repositorio:

```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
Crea y activa un entorno virtual:

bash

# Windows
python -m venv env
env\Scripts\activate

# macOS / Linux
python3 -m venv env
source env/bin/activate

Instala las dependencias:

bash
pip install -r requirements.txt

Ejecuta la app:

bash
streamlit run Streamlit_Titanic.py

🗂 Estructura del proyecto

├── Streamlit_Titanic.py                    # Script principal de la app
├── titanic_ai_model.py                     # Módulo con el modelo de IA
├── html_titanic_table_description.html     # HTML con descripción del dataset
├── requirements.txt                        # Dependencias del proyecto

📁 Dataset utilizado
La app carga automáticamente el dataset desde esta URL:

https://conquerblocks-streamlit.s3.eu-west-2.amazonaws.com/titanic-train.csv

![Stre](https://github.com/user-attachments/assets/11deee6c-77a2-4a15-be20-e2ad7d95d5d7)
![Stre](https://github.com/user-attachments/assets/c2738a98-4ee6-4651-81f5-078d4cad8948)

📚 Autor
Desarrollado por Jorge Juan Moscoso Chacón como parte del módulo de aprendizaje de Streamlit en el Máster de Programación Full Stack de Conquer Block.

“Ver cómo de una tabla plana puedes sacar tanto valor me ha parecido brutal. Y lo visual y entendible que puede hacerse de una aburrida lista de datos es lo que más me ha sorprendido.”

