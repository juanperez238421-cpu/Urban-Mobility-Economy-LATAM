<p align="center">
  <img src="Gif.gif" alt="Movilidad Urbana" width="100%" />
</p>


# 🏙️ Movilidad Urbana y Desarrollo Económico en LATAM

Este proyecto analiza la relación entre la eficiencia de la movilidad urbana (tráfico) y la productividad económica en las principales ciudades de América Latina.

**Rol:** Analista de Datos para el Latin American Development Bank.
**Objetivo:** Identificar patrones que justifiquen la inversión en infraestructura de transporte.

## 📊 Fuentes de Datos
El dataset final es el resultado de la **fusión y limpieza (Data Wrangling)** de dos fuentes dispares:
1.  **TomTom Traffic Index:** Datos de congestión en tiempo real, retrasos y tiempos de viaje.
2.  **OECD Cities:** Indicadores macroeconómicos (PIB per cápita, Desempleo, Población).

## ⚙️ Metodología de Procesamiento (ETL)
Utilizando **Python y Pandas**, se realizó el siguiente flujo de trabajo:
1.  **Limpieza:** Estandarización de nombres de ciudades (ej. "bogota" vs "Bogotá") para permitir el cruce de datos.
2.  **Transformación:** Agregación de millones de registros de tráfico para obtener promedios anuales por ciudad.
3.  **Fusión (Merge):** Unificación de las tablas de Tráfico y Economía en un dataset maestro.
4.  **Análisis:** Correlación entre el tiempo perdido en tráfico y el PIB per cápita.

## 💡 Hallazgos Clave
*   **Costo de la Congestión:** Se identificó una tendencia donde las ciudades con mayores tiempos de viaje tienden a tener desafíos en productividad, aunque ciudades con muy alto PIB también presentan saturación vehicular por alta demanda.
*   **Infraestructura Crítica:** Ciudades con sistemas de transporte masivo eficientes mostraron mejores indicadores de movilidad relativa a su población.

## 🛠 Herramientas Utilizadas
*   **Python:** Pandas (manipulación de DataFrames), NumPy.
*   **Visualización:** Matplotlib, Seaborn.
*   **Técnicas:** Data Cleaning, String Matching, Merging & Joining, Exploratory Data Analysis (EDA).

---
*Este proyecto es parte del Sprint de Procesamiento de Datos con Python.*
