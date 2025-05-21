# forecast-temperatura-era5

# 🌡️ **Modelagem preditiva da temperatura média com Machine Learning e Séries Temporais**

Este projeto usa dados de reanálise climática do [ERA5](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels?tab=overview) para prever a temperatura mensal média de 2025 a 2050, utilizando modelos como Regressão Linear, Random Forest, XGBoost, ARIMAX e SARIMAX.

## 📄 Objetivo:

Criar uma pipeline preditiva com simulaçõs Monte Carlo para projetar a temperatura média mensal futura até 2050 em uma região de interesse, utilizando e não utilizando variávies exógenas.

## 📉 Modelos utilizados:

- Regressão Linear, considerando e não considerando variáveis exógenas
- Random Forest, considerando e não considerando variáveis exógenas
- XGBoost, considerando e não considerando variáveis exógenas
- ARIMAX
- SARIMAX com variáveis exógenas
- Simulações Monte Carlo para cenários futuros

## 📦 Bibliotecas
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost
- statsmodels

## 📊 Resultados

- Gráfico com a comparação entre os diferentes modelos;
- Gráfico com a previsão da temperatura média mensal de 2025 a 2050 considerando variáveis exógenas (Random Forest);
- Gráfico com a previsão da temperatura média mensal de 2025 a 2050 considerando variáveis exógenas (ARIMAX);
- Gráfico com a temperatura média anual de 2025 a 2050 e a diferença entre a média histórica da temperatura;

##  📁 Organização
- `notebooks/`: notebook principal
- `data/`: dados brutos
- `outputs/`: graficos
- `README.md`: este arquivo
- `.gitignore`: arquivos que devem ser ignorados


