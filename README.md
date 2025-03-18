# Predição do Preço de Corridas de Uber e Lyft 

Este repositório contém o código e a análise para um projeto de predição do preço de corridas de Uber e Lyft usando técnicas de machine learning. O objetivo principal é prever o valor esperado de uma corrida com base em variáveis como categoria do veículo, horário, condições climáticas, entre outras. A métrica utilizada para otimização é o MAPE (Mean Absolute Percentage Error).

## Dataset

O dataset utilizado foi coletado a partir de consultas de preço para corridas de aplicativo entre algumas regiões de Boston durante novembro e dezembro de 2018. Ele contém aproximadamente 700 mil instâncias com 57 variáveis, incluindo informações sobre preço da corrida, categoria do veículo, horário, condições climáticas, entre outras.

O dataset original pode ser encontrado no Kaggle.

## Estrutura do Repositório

- **[uber_lyft_price_prediction](https://github.com/erikmilesi/uber_lyft_price_prediction/blob/main/uber_lyft_price_prediction.ipynb)**: Contém o Jupyter Notebook com a análise e o código para a predição do preço das corridas.
- **[data](https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices?sort=votes&select=cab_rides.csv)**: Contém o dataset utilizado no projeto.
- **README.md**: Este arquivo, que fornece uma visão geral do projeto.

## Pré-requisitos

Para executar o código, você precisará das seguintes bibliotecas Python:

- `pandas` — Para manipulação e análise de dados.
- `numpy` — Para operações matemáticas e manipulação de arrays.
- `scikit-learn` — Para pré-processamento de dados, modelagem, avaliação e métricas de aprendizado de máquina.
- `seaborn` — Para visualização de dados estatísticos.
- `matplotlib` — Para visualização de gráficos e figuras.
- `kagglehub` — Para acessar e carregar datasets diretamente do Kaggle.
- `math` — Para funções matemáticas adicionais.
  
Bibliotecas específicas do scikit-learn que são utilizadas incluem:

- `train_test_split` — Para dividir os dados em conjuntos de treino e teste.
- `StandardScaler`, `OneHotEncoder`, `PolynomialFeatures` — Para transformação e normalização dos dados.
- `LinearRegression`, `Ridge` — Para construção de modelos de regressão linear.
- `make_column_transformer`, `Pipeline`, `make_pipeline` — Para criação de pipelines de pré-processamento e modelagem.
- `mean_absolute_percentage_error`, `mean_squared_error`, `mean_absolute_error` — Para avaliar a performance dos modelos.

---

# Uber and Lyft Fare Prediction 

This repository contains the code and analysis for a project predicting the fare of Uber and Lyft rides using machine learning techniques. The main goal is to predict the expected fare of a ride based on variables such as vehicle category, time, weather conditions, and more. The optimization metric used is MAPE (Mean Absolute Percentage Error).

## Dataset

The dataset used was collected from fare queries for ride-sharing services between some regions in Boston during November and December of 2018. It contains approximately 700,000 instances with 57 variables, including information about the fare, vehicle category, time, weather conditions, and others.

The original dataset can be found on Kaggle.

## Repository Structure

- **[uber_lyft_price_prediction](https://github.com/erikmilesi/uber_lyft_price_prediction/blob/main/uber_lyft_price_prediction.ipynb)**: Contains the Jupyter Notebook with the analysis and code for predicting the fare of the rides.
- **[data](https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices?sort=votes&select=cab_rides.csv)**: Contains the dataset used in the project.
- **README.md**: This file, providing an overview of the project.

## Prerequisites

To run the code, you will need the following Python libraries:

- `pandas` — For data manipulation and analysis.
- `numpy` — For mathematical operations and array manipulation.
- `scikit-learn` — For data preprocessing, modeling, evaluation, and machine learning metrics.
- `seaborn` — For statistical data visualization.
- `matplotlib` — For visualizing graphs and figures.
- `kagglehub` — For accessing and loading datasets directly from Kaggle.
- `math` — For additional mathematical functions.
  
Specific `scikit-learn` libraries used include:

- `train_test_split` — For splitting the data into training and testing sets.
- `StandardScaler`, `OneHotEncoder`, `PolynomialFeatures` — For data transformation and normalization.
- `LinearRegression`, `Ridge` — For building linear regression models.
- `make_column_transformer`, `Pipeline`, `make_pipeline` — For creating preprocessing and modeling pipelines.
- `mean_absolute_percentage_error`, `mean_squared_error`, `mean_absolute_error` — For evaluating model performance.

