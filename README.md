# analysis-everpeak
# Análisis de Movilidad Urbana y Productividad Económica en América Latina

Este repositorio contiene el análisis realizado para evaluar la relación entre la **movilidad urbana** (congestión vehicular, retrasos y tiempos de viaje) y la **productividad económica** (PIB per cápita, desempleo y población) en las principales ciudades de Latinoamérica durante el año 2024.

El estudio combina datos reales de **TomTom Traffic Index** y **OECD Cities** para identificar cuellos de botella estructurales y determinar en qué ciudades es prioritario invertir en infraestructura de transporte.

---

## 📂 Contenido del repositorio

- `notebooks/urban_mobility_analysis.ipynb`  
  → Notebook principal que incluye limpieza de datos, análisis exploratorio (EDA), unión de datasets (tráfico + economía), visualizaciones y el resumen ejecutivo con recomendaciones.
- `data/tomtom_traffic.csv`  
  → Dataset con registros de tráfico y congestión vial.
- `data/oecd_city_economy.csv`  
  → Dataset con indicadores socioeconómicos y demográficos de las ciudades.
- `data/ladb_mobility_economy_2024_clean.csv`  
  → Dataset limpio y unificado con los promedios anuales de movilidad y economía para el año 2024.

---

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/angelica-ariza/analysis-everpeak/blob/main/S5%20ladb_mobility_economy_project_student%20(1).ipynb)

O:

1. Abre el archivo `.ipynb` ubicado en la carpeta `notebooks/` dentro de GitHub.
2. Haz clic en **Open in Colab** en la parte superior del archivo.

---

## 📘 Cómo reproducir el análisis

1. Clona este repositorio o descarga los archivos.
2. Asegúrate de instalar las librerías necesarias:
   ```bash
   pip install pandas numpy seaborn matplotlib
