# Projeto de Análise e Predição de Evasão de Clientes (Churn) - Telecom X - Parte 2

## 📄 Descrição do Projeto

Este projeto de Ciência de Dados tem como objetivo principal **prever a evasão de clientes (churn)** de uma empresa de telecomunicações fictícia, a Telecom X. A evasão de clientes é um dos maiores desafios para empresas de serviço por assinatura, e a capacidade de prever quais clientes têm maior probabilidade de cancelar seus serviços permite que a empresa tome medidas proativas para retê-los.

O projeto foi desenvolvido em Python, utilizando bibliotecas como Pandas, Scikit-learn e Matplotlib para análise exploratória, pré-processamento de dados e construção de modelos de Machine Learning.

## ⚙️ Tecnologias Utilizadas

* `Pandas`
* `NumPy`
* `Matplotlib e Seaborn`
* `Scikit-learn`

## 📂 Metodologia e Estrutura do Projeto

O projeto segue um fluxo de trabalho padrão em Ciência de Dados:

1.  **Análise Exploratória de Dados (EDA):** Investigação inicial dos dados para identificar padrões, anomalias e insights.
2.  **Pré-processamento de Dados:** Tratamento de valores ausentes, conversão de tipos de dados, e codificação de variáveis categóricas para preparar os dados para os modelos.
3.  **Modelagem:** Construção e treinamento de modelos de Machine Learning para a tarefa de classificação. Foram explorados os seguintes modelos:
    * **Árvore de Decisão:** Modelo intuitivo e de alta interpretabilidade.
    * **Random Forest:** Modelo robusto, conhecido por sua alta acurácia e capacidade de mitigar overfitting.
4.  **Avaliação e Análise de Desempenho:** Avaliação dos modelos utilizando métricas como Acurácia, Precisão, Recall e F1-Score para identificar o melhor modelo para o problema.

## 📈 Análise dos Resultados

Após a construção e avaliação dos modelos, o **Random Forest** foi selecionado como o modelo de melhor desempenho.

* **Acurácia**: 80%
* **F1-Score para Evasão (Classe `1`)**: 52%

Apesar da alta acurácia geral, a análise aprofundada das métricas de desempenho revelou que o recall para a classe de evasão foi o principal ponto fraco, indicando que o modelo ainda tem margem para melhoria na identificação de todos os clientes em risco de churn.

**Análise de Overfitting:** A comparação de desempenho entre os conjuntos de treino e teste mostrou que o modelo Random Forest não apresentou sinais significativos de overfitting, o que o torna uma escolha confiável e generalizável.

## 📊 Importância das Variáveis

Uma das maiores contribuições deste projeto foi a análise da **importância das variáveis** no modelo Random Forest. As variáveis mais relevantes para a previsão de churn foram:
* `tipo_contrato`
* `tempo_contrato`
* `gasto_total`

A identificação dessas variáveis oferece insights estratégicos para a Telecom X, permitindo que a empresa concentre seus esforços de retenção em fatores que realmente impulsionam a evasão de clientes.

## 🚀 Como Executar
> Clone este repositório ou baixe o notebook.
> 
> Abra o arquivo TelecomX_2.ipynb com Jupyter Notebook ou Google Colab.
> 
> Execute as células sequencialmente para acompanhar toda a análise.

## 📎 Arquivo
- `TelecomX_2.ipynb`
