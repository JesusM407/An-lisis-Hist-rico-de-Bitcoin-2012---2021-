# Analisis-Historico-de-Bitcoin-2012---2021-
Un estudio sobre la evolución del precio, volatilidad y tendencias utilizando Python y SQL.

## 📝 Descripción

Este proyecto analiza el conjunto de datos históricos de Bitcoin de Bitstamp. 
El objetivo es transformar datos crudos de alta frecuencia (minuto a minuto) 
en visualizaciones comprensibles y métricas clave para entender el comportamiento del mercado.

## 🛠️ Herramientas

* **Python** (Pandas, Matplotlib) - Para limpieza y visualización.
* **SQL (SQLite)** - Para la agregación de datos y consultas de promedios anuales.
* **Google Colab** - Entorno de desarrollo.

## 🔍 Hallazgos Principales

1. **Crecimiento Exponencial:** Gracias al uso de la escala logarítmica, se identificó que Bitcoin ha mantenido una tendencia alcista constante desde 2012, permitiendo visualizar los ciclos de mercado que en una escala lineal parecen imperceptibles.
2. **Máximos Históricos:** Mediante consultas SQL, se confirmó que el pico máximo de este dataset alcanzó los **$69,000.00 USD** el 10 de noviembre de 2021.
3. **Análisis de Tendencia:** Se observó que a partir de 2020, la volatilidad aumentó significativamente junto con el volumen, coincidiendo con la entrada de mayor adopción institucional reflejada en los datos.
