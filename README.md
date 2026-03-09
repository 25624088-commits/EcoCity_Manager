# 🏙️ Sistema de Monitoreo y Análisis de Microclima Urbano
### Proyecto de Ciencia de Datos Ambiental y Sistemas AIoT

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Hardware-ESP32%20%7C%20ESP8266-red?logo=espressif&logoColor=white" alt="Hardware">
  <img src="https://img.shields.io/badge/Data%20Science-Pandas%20%7C%20Numpy%20%7C%20Sklearn-orange" alt="Data Science">
  <img src="https://img.shields.io/badge/Open%20In%20Colab-F9AB00?logo=googlecolab&logoColor=white" alt="Colab">
</p>

---

## 👨‍🔬 Información del Autor
* **Autor:** Macx Berdeja Guerrero
* * **Profesor:** Juan Miguel Hernandez Ramirez
* **Rol:** Estudiante de Ciencia de Datos / Laboratorio AIoT CyTI
* **Institución:** Universidad Autónoma de Guerrero

---

## 🌎 Descripción del Proyecto
Este proyecto desarrolla una infraestructura digital de monitoreo microclimático urbano basada en **sensores ambientales**, **ciencia de datos** y **análisis estadístico**. A diferencia de los modelos regionales, este sistema captura variaciones térmicas locales para identificar patrones microclimáticos y detectar momentos de estrés térmico extremo.

---

## 🔬 Sesión 01: Anatomía de Objetos y Gestión de Memoria
Como parte fundamental de la ingeniería de software en ciencia de datos, se exploró la administración de memoria en Python:
* **Identidad (ID):** Uso de `id()` y el operador `is` para validar direcciones únicas en memoria.
* **Interning:** Comprensión de la pre-asignación de enteros (-5 a 256) para optimización.
* **Garbage Collector:** Gestión del ciclo de vida de objetos huérfanos.
* **Integridad de Datos:** Implementación de `copy.deepcopy()` para proteger datasets originales durante simulaciones de "Eco-City".



---

## 🧠 Fundamentos Científicos del Análisis

### 📐 Álgebra Lineal
Organización de los datos en matrices de diseño:
$$A \in \mathbb{R}^{n \times p}$$
Donde $n$ es el número de mediciones y $p$ las variables ambientales. Aplicamos **PCA** y **SVD** para reducir dimensionalidad e identificar patrones climáticos dominantes.

### 🎲 Probabilidad y Estadística
Modelado de temperatura y humedad como variables aleatorias continuas para realizar inferencia estadística, detección de anomalías térmicas y modelos predictivos de series temporales.

---

## 📈 Ejemplo de Análisis
El sistema procesa variables críticas para entender el comportamiento del entorno:
* **Variabilidad Térmica Diaria:** Identificación de la inercia térmica urbana.
* **Comportamiento de Humedad Relativa:** Correlación con el confort térmico.
* **Patrones Horarios:** Análisis de ciclos circadianos locales.



---

## 🌡️ Arquitectura del Sistema (AIoT)
* **Hardware:** Nodos sensores basados en **ESP32** y **ESP8266**.
* **Instrumentación:** Sensores **DHT22** y **DHT11** de alta precisión.
* **Conectividad:** Transmisión vía WiFi para almacenamiento y análisis en tiempo real.



---

## 📚 Bitácora Científica (Google Colab)
Toda la investigación, desde la limpieza de datos hasta el modelado estadístico, está documentada de forma interactiva.

👉 **Acceso a la Bitácora:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dwD2P9T70hsxgvEho_zgtZt3s7eCWhVS)

---

## 📁 Estructura del Repositorio
```bash
EcoCity_Manager/
├── data/           # Datasets climáticos (Hoja1.csv)
├── notebooks/      # Documentación en Google Colab / Jupyter
├── sensors/        # Firmware para ESP32/ESP8266 (.ino)
├── analysis/       # Scripts de procesamiento (clima.py e identidad.py)
├── visualization/  # Gráficas y reportes experimentales
└── README.md       # Documentación principal
