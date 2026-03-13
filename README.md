# 📊 Análise de Risco de Crédito

Este projeto tem como objetivo analisar dados de clientes para identificar padrões de inadimplência e desenvolver um modelo de machine learning capaz de prever risco de default.

A análise combina exploração de dados, engenharia de variáveis e modelagem preditiva.

---

# 🎯 Objetivo do Projeto

Identificar fatores associados ao risco de inadimplência e construir um modelo capaz de prever clientes com maior probabilidade de default.

Esse tipo de análise pode apoiar instituições financeiras em decisões de concessão de crédito e gestão de risco.

---

# 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📁 Estrutura do Projeto

analise-risco-credito
│
├── data
├── imagens
├── notebooks
│ ├── EDA_risco_de_credito.ipynb
│ ├── base_tratada.ipynb
│ ├── Feature_engineering.ipynb
│ ├── Modelagem_e_Avaliacao.ipynb
│ └── Previsao_Novos_Defaults.ipynb

---

# 🔎 Análise Exploratória (EDA)

Foram analisadas distribuições de variáveis relevantes relacionadas ao comportamento financeiro dos clientes.

## Distribuição de Inadimplência
![Distribuição de Inadimplência](imagens/distribuicao_inadimplencia.png)

## Limite de Crédito vs Inadimplência
![Limite de Crédito](imagens/distribuicao_limite_credito.png)

## Fatura e Inadimplência
![Fatura](imagens/distribuicao_fatura_inadimplencia.png)

## Pagamentos e Inadimplência
![Pagamentos](imagens/distribuicao_pagamento_inadimplencia.png)

## Saldo Recente
![Saldo](imagens/distribuicao_saldo_recente_inadimplencia.png)

## Histórico de Pagamentos
![Histórico](imagens/historico_pagamentos_inadimplencia.png)

---

# 🤖 Modelagem Preditiva

Foi utilizado um modelo de *Random Forest* para prever a probabilidade de inadimplência.

Etapas realizadas:

1. Tratamento de dados
2. Engenharia de variáveis
3. Divisão treino/teste
4. Treinamento do modelo
5. Avaliação de performance

---

# 📈 Resultados

O modelo demonstrou capacidade de identificar padrões relevantes associados ao risco de crédito, permitindo prever potenciais clientes inadimplentes.

---

# 👨‍💻 Autor

Murillo Bernardes
