🎧 Previsão de Popularidade de Músicas com Machine Learning

Este projeto apresenta um pipeline completo de Ciência de Dados, desenvolvido em Python e executado no Google Colab, com o objetivo de prever a popularidade de músicas a partir de suas características acústicas, utilizando técnicas de regressão.

O projeto foi construído com foco didático, mas seguindo boas práticas reais da área, sendo ideal tanto para aprendizado quanto para portfólio profissional.

🧠 Objetivo do Projeto

Construir um modelo de Machine Learning capaz de prever a variável popularity (valor numérico contínuo) com base em atributos como energia, dança, loudness, tempo, entre outros.

🗂️ Etapas do Projeto
1. Carregamento e Exploração Inicial dos Dados

Importação do dataset

Verificação de dimensões, tipos de dados e valores ausentes

Análise inicial da estrutura dos dados

2. Análise Exploratória de Dados (EDA)

Estatísticas descritivas

Visualização da distribuição da variável alvo

Análise de correlação entre variáveis numéricas

Identificação de padrões relevantes para modelagem

3. Preparação dos Dados

Remoção de colunas não relevantes para o modelo

Separação entre variáveis explicativas (X) e variável alvo (y)

Padronização dos dados com StandardScaler

Divisão em conjuntos de treino e teste

4. Modelagem

Treinamento de um modelo de Regressão Linear

Justificativa da escolha do modelo (simplicidade e interpretabilidade)

5. Avaliação do Modelo

Avaliação com métricas de regressão:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² (Coeficiente de Determinação)

Visualização dos valores reais vs. previstos

🛠️ Tecnologias Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

📈 Resultados

O modelo foi capaz de capturar parte significativa da relação entre as variáveis acústicas e a popularidade das músicas. Apesar de simples, a Regressão Linear serviu como uma excelente base para compreensão do problema e pode ser aprimorada com modelos mais complexos.
