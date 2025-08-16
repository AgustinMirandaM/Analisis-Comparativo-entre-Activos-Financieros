# Analisis-Comparativo-entre-Activos-Financieros
El objetivo principal de este proyecto es analizar y comparar el comportamiento de distintos activos financieros, en este caso —Bitcoin, Ethereum, S&amp;P 500 y MERVAL— desde el año 2019 hasta 2025.

Este proyecto forma parte de un trabajo final académico centrado en el análisis de inversiones utilizando Power BI. El objetivo fue comparar el comportamiento financiero de dos criptomonedas (Bitcoin y Ethereum) con dos índices del mercado tradicional (S&P 500 y MERVAL).

## Contenido del Proyecto

El archivo `.pbix` incluye un dashboard interactivo con visualizaciones para los siguientes activos:

- Bitcoin (BTC)
- Ethereum (ETH)
- S&P 500 
- MERVAL

##  Métricas Analizadas

Para cada activo se calcularon las siguientes métricas financieras:

- **Retorno Diario y Mensual**: mide la rentabilidad en distintos plazos.
- **Volatilidad Diaria y Mensual**: muestra la variabilidad del precio.
- **Sharpe Ratio Diario**: indica el rendimiento ajustado por riesgo.
- **Drawdown y Drawdown Máximo**: identifica caídas desde el máximo histórico.
- **Rendimiento Anual Acumulado**: resume la rentabilidad total por año.
- **Precio Máximo**: mayor valor histórico del activo.


## Funcionalidad del Dashboard

Cada página del informe está dedicada a un activo específico y contiene:

- Gráficos de líneas para retornos, Sharpe y volatilidad diaria.
- Gráficos de barras para volatilidad mensual.
- Visualización conjunta de precio y drawdown.
- KPIs destacados como Rendimiento Anual, Drawdown Máximo y Precio Máximo.
- Tabla de retornos mensuales con formato condicional.
- Filtros por año para análisis comparativo.

## Tecnologías utilizadas

- **Python** utilizando la libreria "Yfinance" para descargar los datos historicos de cada activo
- **Power BI Desktop**
- **Lenguaje DAX** (para crear las medidas financieras)
- **Transformación de datos** en Power Query
- Dataset propio con precios históricos de los activos
