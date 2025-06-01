# 🌤️ EDA_API_OPEN-METEO

🔍 **Análisis Exploratorio de Datos Meteorológicos usando la API de Open-Meteo**

---

## 🧠 Descripción del Proyecto

Este proyecto consiste en un Análisis Exploratorio de Datos (EDA) sobre variables meteorológicas históricas obtenidas a través de solicitudes a la API gratuita de [Open-Meteo](https://open-meteo.com/).

📡 Los datos incluyen información diaria como la temperatura máxima, mínima, media y la precipitación acumulada para una ubicación específica durante un periodo determinado.

🎯 El objetivo es visualizar y analizar el comportamiento climático en una región a lo largo del tiempo, para comprender mejor la variabilidad de las temperaturas y precipitaciones.

---

## 🛠️ Herramientas Utilizadas

- 🌐 **Open-Meteo API**: Para obtener datos climáticos históricos.
- 🐍 **Python + Jupyter Notebook**: Para procesar, analizar y visualizar los datos.
- 🧮 **Pandas**: Para manipulación de datos en formato tabular.
- 📊 **Matplotlib** y **Seaborn**: Para gráficos e insights visuales.
- 🔗 **Requests**: Para realizar las peticiones HTTP a la API.

---

## 🎯 Objetivos del Análisis

- 📥 Obtener datos meteorológicos reales desde una API.
- 🧹 Procesar y limpiar los datos para su análisis.
- 📊 Visualizar variables como la temperatura y la precipitación.
- 🔍 Explorar patrones climáticos a lo largo del tiempo.
- 🌡️ Estudiar variabilidad térmica y eventos de lluvia.

---

## 💡 Valor que aporta el proyecto

Este análisis permite observar de forma clara cómo ha cambiado el clima en una localización concreta durante un periodo determinado. Puede ser útil para:

- 🌱 Estudios agrícolas.
- 🏙️ Planificación urbana o energética.
- 📘 Proyectos educativos sobre análisis de datos.
- 🧪 Prácticas con APIs en ciencia de datos.

---

```python
url = f"https://archive-api.open-meteo.com/v1/archive?latitude={lat}&longitude={lon}&start_date={inicio}&end_date={fin}&daily=temperature_2m_max,temperature_2m_min,temperature_2m_mean,precipitation_sum&timezone=Europe%2FBerlin"
