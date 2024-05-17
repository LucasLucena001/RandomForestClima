# # Previsão do Clima Atual

Este repositório contém um projeto de Machine Learning desenvolvido para prever o clima atual. Foram utilizados três modelos diferentes: RandomForestRegressor, Gradient Boosting Regressor (GBR) e AdaBoost Regressor (ADA). Os modelos foram avaliados usando o coeficiente de determinação (R² score), o Erro Médio Absoluto (MAE) e o Erro Quadrático Médio (MSE).

## Descrição

Este projeto tem como objetivo desenvolver e comparar diferentes modelos de regressão para prever o clima atual com base em um conjunto de características meteorológicas. Os modelos utilizados foram:

- **RandomForestRegressor:** Um regressor que usa múltiplas árvores de decisão para reduzir o overfitting e melhorar a precisão.
- **Gradient Boosting Regressor (GBR):** Um método de boosting que constrói modelos de forma sequencial, onde cada modelo corrige os erros do modelo anterior.
- **AdaBoost Regressor (ADA):** Um método de boosting, que ajusta os pesos das instâncias de treinamento, dando mais peso aos casos mais difíceis de prever.

## Bibliotecas Utilizadas

Este projeto foi desenvolvido em Python e utiliza as seguintes bibliotecas:

```bash
numpy
pandas
scikit-learn
matplotlib
seaborn
