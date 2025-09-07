# 🚲 Análisis Exploratorio de Datos - Cyclistic

Este proyecto realiza un **Análisis Exploratorio de Datos (EDA)** sobre los viajes de bicicletas compartidas de **Cyclistic**.  
El notebook `bicycles.ipynb` contiene la carga, limpieza, combinación de archivos y análisis de los datos.
---
## 📦 Requisitos previos

1. **Clonar este repositorio**
   ```bash
   git clone https://github.com/CarolinaYepesV/Cyclistic_EDA.git
   cd <NOMBRE_DEL_REPO>
Crear y activar un entorno virtual

---
# Crear ambiente virtual
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
Instalar las dependencias
---
# Instalar dependencias
pip install -r requirements.txt
Configurar la API de Kaggle

Crea un token desde tu perfil de Kaggle.

Descarga el archivo kaggle.json.

Ubícalo en:

Linux/Mac: ~/.kaggle/kaggle.json

Windows: C:\Users\<USUARIO>\.kaggle\kaggle.json

📥 Descarga de los datos
Ejecuta el primer bloque de codigo del notebook:
Esto descargará y extraerá los archivos de Kaggle en la carpeta data/.

📊 Ejecución del notebook
Abre VS Code o Jupyter Notebook.

Selecciona el kernel de Python correspondiente a tu entorno virtual (venv).

Abre bicycles.ipynb y ejecuta las celdas en orden.

El notebook:

Realiza limpieza y transformación de datos.

Explora patrones de uso de bicicletas compartidas.

Genera visualizaciones para comprender mejor el comportamiento de usuarios.

⚠️ Notas importantes
Los datasets son grandes (~1 GB en total) y no se incluyen en este repositorio por limitaciones de GitHub.

El script get_data.py permite obtenerlos automáticamente desde Kaggle.

Para pruebas rápidas puedes trabajar con un sample de los datos (ej. sample_data.csv).