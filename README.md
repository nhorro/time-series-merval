# Comparación de Métodos de Predicción de Series Temporales aplicados a Acciones de MERVAL

Se comparan distintos métodos de predicción de series temporales para un caso de Acciones de MERVAL obtenidas del servicio Yahoo Finance!.

![aluar_prophet](/home/nhorro/github/time-series-merval/assets/aluar_prophet.png)

![aluar_lstm](assets/aluar_lstm.png)

El objetivo es comparar desde métodos clásicos como SARIMA hasta los más recientes como [Prophet](https://facebook.github.io/prophet/) de Facebook.

Cada serie temporal contiene los datos de un período:

- **Apertura (Open)**
- **Alto (High)**
- **Bajo (Low)**
- **Cierre (Close)**
- **Precio de Cierre Ajustado (Adj)**
- **Volumen (Volume)**

Se trata el problema de predicción de una manera general sin aplicar técnicas específicas de modelos matemáticos financieros o conocimientos del dominio financiero o del mercado bursátil, por lo tanto es trasladable a cualquier problema de series temporales univariable.

### Modelos Ensayados

- SARIMA
- LSTM
- GRU
- CNN
- Facebook Prophet

## Casos de Estudio

- [Precios de Cierre de ALUAR Período 2015-2021](TimeSeries_MERVAL_ALUAR_2015_2021.ipynb)