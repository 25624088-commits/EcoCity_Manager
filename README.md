# 🏙️ Sistema de Monitoreo y Análisis de Microclima Urbano
### Proyecto de Ciencia de Datos Ambiental y Sistemas AIoT

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Hardware-ESP32%20%7C%20ESP8266-red?logo=espressif&logoColor=white" alt="Hardware">
  <img src="https://img.shields.io/badge/Data%20Science-Pandas%20%7C%20Numpy%20%7C%20Sklearn-orange" alt="Data Science">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</p>

---

## 👨‍🔬 Información del Autor
* **Autor:** Macx Berdeja Guerrero
* **Institución:** Universidad Autónoma de Guerrero
* **Laboratorio:** AIoT CyTI
* **Rol:** Estudiante de Ciencia de Datos

---

## 🌎 Descripción del Proyecto
Este proyecto desarrolla una infraestructura digital de monitoreo microclimático urbano basada en **sensores ambientales**, **ciencia de datos** y **análisis estadístico**. 

A diferencia de los modelos meteorológicos regionales, este sistema captura variaciones térmicas locales, permitiendo identificar patrones microclimáticos urbanos y detectar condiciones de calor extremo para una gestión climática precisa.



---

## 🧠 Fundamentos Científicos

### 📐 Álgebra Lineal
La organización de los datos se estructura en matrices de diseño:
$$A \in \mathbb{R}^{n \times p}$$
Donde:
* $n$: Número de mediciones (instancias temporales).
* $p$: Variables ambientales (Temperatura, Humedad, Hora, Fecha).

**Aplicaciones:**
* **PCA (Análisis de Componentes Principales):** Reducción de dimensionalidad para identificar variables dominantes.
* **SVD (Descomposición en Valores Singulares):** Extracción de patrones climáticos latentes.

### 🎲 Probabilidad y Estadística
Modelamos las variables ambientales como variables aleatorias continuas para realizar:
* Análisis de distribuciones de probabilidad.
* Inferencia estadística para detección de anomalías térmicas.
* Modelado predictivo de series temporales.

---

## 🌡️ Arquitectura del Sistema (AIoT)
El hardware está diseñado para la adquisición y transmisión robusta de datos:
* **Nodos Sensores:** ESP32 y ESP8266.
* **Instrumentación:** Sensores DHT22 y DHT11 (Alta precisión en Temp/Hum).
* **Conectividad:** Transmisión vía WiFi para almacenamiento en la nube y análisis posterior.

---

## 📊 Stack Tecnológico de Ciencia de Datos
Se utiliza el ecosistema de Python para el procesamiento científico:
* **Procesamiento:** `pandas`, `numpy`.
* **Modelado:** `scikit-learn`.
* **Visualización:** `matplotlib`, `plotly`, `seaborn`.



---

## 📁 Estructura del Repositorio

```bash
EcoCity_Manager/
├── data/           # Datasets climáticos (CSV/JSON)
├── notebooks/      # Documentación en Google Colab / Jupyter
├── sensors/        # Firmware para ESP32/ESP8266 (.ino / .py)
├── analysis/       # Scripts de procesamiento y limpieza
├── visualization/  # Gráficas y assets experimentales
└── README.md       # Documentación principal
