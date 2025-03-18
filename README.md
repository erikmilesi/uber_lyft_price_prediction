# Predição do Preço de Corridas de Uber e Lyft ![Bandeira do Brasil](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zY3JpcHQtMjAgY29tcGxldGU9Il0gdi12aWV3Qm94PSIwIDAgNTEyIDUxMiI+Cgk8ZyBmaWxsPSJub25lIj4KPHJlY3Qgd2lkdGg9IjUxMiIgaGVpZ2h0PSI1MTIiIGZpbGw9IiMwMEE4NTkiLz4KPHBvbHlnb24gZmlsbD0iI0ZGQ0MwMCIgcG9pbnRzPSIyNTYsMTIwIDEyOCwyNTYgMjU2LDM5MiAiLz4KPHNpcmNsZSBjeD0iMjU2IiBjeT0iMjU2IiByPSIxNTAiIGZpbGw9IiMzZTQwOTUiLz4KPHBhdGggZmlsbD0ibm9uZSIgZD0iTTEyOSwyNjAgYzcuNywyLjYsMjAuMiwtMCAzNi40LDExLjQgMTUuNCw1LjIsMjkuNiwxMS4zMywgMTMuOSwzOS4yYzE1LjIsMTIuMiwzLjgsMjIuOSw1LjgsMzYuOCw4Ljk1LDE3LjcsMjAuOSwzLjgsMTEuMiwzMC40QzAiLz4KPC9nPjwvc3ZnPgo=)

Este repositório contém o código e a análise para um projeto de predição do preço de corridas de Uber e Lyft usando técnicas de machine learning. O objetivo principal é prever o valor esperado de uma corrida com base em variáveis como categoria do veículo, horário, condições climáticas, entre outras. A métrica utilizada para otimização é o MAPE (Mean Absolute Percentage Error).

## Dataset

O dataset utilizado foi coletado a partir de consultas de preço para corridas de aplicativo entre algumas regiões de Boston durante novembro e dezembro de 2018. Ele contém aproximadamente 700 mil instâncias com 57 variáveis, incluindo informações sobre preço da corrida, categoria do veículo, horário, condições climáticas, entre outras.

O dataset original pode ser encontrado no Kaggle:
- [Dataset original](https://www.kaggle.com/raviilmunde/uber-lyft-cab-prices)
- [Dataset com variáveis adicionais](https://www.kaggle.com/brdmachado/uber-lyft-boston)

## Estrutura do Repositório

- **notebooks/**: Contém o Jupyter Notebook com a análise e o código para a predição do preço das corridas.
- **data/**: Contém o dataset utilizado no projeto.
- **scripts/**: Contém scripts auxiliares para processamento de dados ou outras tarefas.
- **README.md**: Este arquivo, que fornece uma visão geral do projeto.

## Como Executar o Código

### Pré-requisitos

Para executar o código, você precisará das seguintes bibliotecas Python:

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

---

# Prediction of Uber and Lyft Ride Prices

This repository contains the code and analysis for a project focused on predicting Uber and Lyft ride prices using machine learning techniques. The main goal is to predict the expected price of a ride based on variables such as vehicle category, time of day, weather conditions, and others. The optimization metric used is MAPE (Mean Absolute Percentage Error).

## Dataset

The dataset used was collected from fare queries for app-based rides between some regions of Boston during November and December 2018. It contains approximately 700,000 instances with 57 variables, including information about ride prices, vehicle category, time of day, weather conditions, and more.

The original dataset can be found on Kaggle:
- [Original dataset](https://www.kaggle.com/raviilmunde/uber-lyft-cab-prices)
- [Dataset with additional variables](https://www.kaggle.com/brdmachado/uber-lyft-boston)

## Repository Structure

- **notebooks/**: Contains the Jupyter Notebook with the analysis and code for predicting ride prices.
- **data/**: Contains the dataset used in the project.
- **scripts/**: Contains auxiliary scripts for data processing or other tasks.
- **README.md**: This file, which provides an overview of the project.

## How to Run the Code

### Prerequisites

To run the code, you will need the following Python libraries:

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
