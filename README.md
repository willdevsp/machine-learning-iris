# Análise e Classificação do Dataset Iris

Este projeto realiza uma análise exploratória e classificação do famoso dataset Iris utilizando diferentes algoritmos de machine learning.

## 📋 Sobre o Dataset

O dataset Iris é um dos mais conhecidos na área de machine learning. Ele contém 150 amostras de três diferentes espécies de flores Iris (Setosa, Versicolor e Virginica), com quatro características medidas para cada amostra:
- Comprimento da sépala (cm)
- Largura da sépala (cm)
- Comprimento da pétala (cm)
- Largura da pétala (cm)

## 🚀 Funcionalidades

- Carregamento e pré-processamento dos dados
- Análise exploratória detalhada com visualizações
- Implementação de múltiplos modelos de classificação:
  - K-Nearest Neighbors (KNN)
  - Regressão Logística
  - Random Forest
  - XGBoost

## 📊 Análise Exploratória

O projeto inclui várias visualizações para entender melhor os dados:
- Pairplot para visualizar relações entre características
- Boxplots para análise da distribuição dos dados
- Informações estatísticas descritivas

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas - Manipulação de dados
- Seaborn/Matplotlib - Visualização de dados
- Scikit-learn - Modelos de machine learning
- XGBoost - Gradient boosting

## 📦 Dependências

```python
pandas==2.2.2
seaborn==0.13.2
matplotlib==3.9.2
scikit-learn==1.5.2
numpy==1.26.4
xgboost==2.1.1
```

Para instalar as dependências, utilize o comando:
```bash
pip install -r requirements.txt
```

## 🔍 Estrutura do Projeto

O projeto está organizado em um Jupyter Notebook com as seguintes seções:
1. Importação das bibliotecas
2. Carregamento dos dados
3. Criação do DataFrame
4. Análise exploratória
5. Preparação dos dados
6. Treinamento e avaliação dos modelos

## 🎯 Resultados

O projeto implementa e compara diferentes algoritmos de classificação, apresentando a acurácia de cada modelo na classificação das espécies de Iris.

## 👤 Autor

willdevsp

## 📄 Licença

Este projeto está sob a licença MIT.