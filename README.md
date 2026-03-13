# 📊 Análise de Risco de Crédito

Este projeto utiliza técnicas de *Machine Learning* para prever o risco de inadimplência de clientes de cartão de crédito.

O objetivo é identificar padrões associados ao comportamento financeiro dos clientes e construir um modelo capaz de prever a probabilidade de default.

---

## 🎯 Problema de Negócio

Instituições financeiras precisam avaliar o risco de inadimplência antes de conceder crédito.

Uma análise preditiva permite:

- reduzir perdas financeiras
- melhorar políticas de concessão de crédito
- identificar clientes com maior probabilidade de inadimplência

---

## 🎯 Objetivo do Projeto

Desenvolver um modelo de classificação capaz de prever clientes com maior risco de inadimplência utilizando dados históricos de crédito.

---

## 🛠 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📁 Estrutura do Projeto

analise-risco-credito/

data/
notebooks/
imagens/
README.md/
requirements.txt

---

# 🔎 Análise Exploratória de Dados

A análise exploratória foi realizada para identificar padrões relacionados ao comportamento financeiro dos clientes.

### Distribuição da Inadimplência

![Distribuição da inadimplência](imagens/distribuicao_inadimplencia.png)

### Limite de Crédito e Inadimplência

![Limite de crédito](imagens/distribuicao_limite_credito.png)

### Histórico de Pagamentos

![Histórico pagamentos](imagens/historico_pagamentos_inadimplencia.png)

---

# 🤖 Modelagem de Machine Learning

Foram treinados diferentes algoritmos de classificação para prever inadimplência.

Modelos avaliados:

- Logistic Regression
- Random Forest
- XGBoost

---

# 📈 Avaliação dos Modelos

| Modelo | Accuracy |
|------|------|
| Logistic Regression | 0.79 |
| Random Forest | 0.80 |
| XGBoost | 0.80 |

O modelo *Random Forest* apresentou melhor desempenho geral e foi selecionado para a etapa de previsão.

---

# 📊 Principais Insights

A análise revelou alguns padrões importantes:

- Clientes com histórico irregular de pagamento apresentam maior risco de inadimplência.
- Variáveis relacionadas ao comportamento de pagamento são fortes preditores de default.
- O limite de crédito pode influenciar o comportamento de pagamento de determinados perfis de clientes.

---

# 🔮 Aplicação do Modelo

Após o treinamento e avaliação, o modelo foi aplicado para prever inadimplência em novos dados, simulando um cenário real de uso em instituições financeiras.

---

# 👨‍💻 Autor

Murillo Bernardes

