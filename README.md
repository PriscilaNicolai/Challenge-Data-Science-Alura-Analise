# 📊 Desafio Data Science Alura: Análise de Churn (TelecomX)
 
## 🎯 Objetivo do Projeto
Este projeto faz parte do Challenge de Data Science da Alura. O objetivo é reduzir a Taxa de Cancelamento (Churn) da operadora TelecomX através da análise de dados e identificação de perfis de risco.
 
**Ferramentas utilizadas:** Python, Pandas, Seaborn, Matplotlib, Git.
 
---
 
## 🔍 Principais Descobertas (Executive Summary)
 
### 1. Diagnóstico Atual
* **Base analisada:** 7.267 clientes.
* **Taxa de Churn Global:** 26,5%.
 
### 2. Perfis de Risco (Quem está saindo?)
* **Forma de Pagamento:** Clientes com **Cheque Eletrônico** e contrato **Mensal** são os maiores ofensores.
* **Fator "Stickiness":** Clientes que contratam apenas o serviço básico saem mais. A fidelidade aumenta drasticamente a partir de **3 serviços extras** contratados (Segurança, Backup, etc).
* **Produtos:** A **Fibra Óptica** possui o maior ticket médio, mas também a maior taxa de evasão, sugerindo necessidade de revisão de qualidade ou preço.
 
---
 
## 🛠️ Estrutura do Projeto
* `TelecomX_BR.ipynb`: Notebook principal com todo o código de ETL, Limpeza e Análise Exploratória (EDA).
* `Telco-Customer-Churn-Limpo.csv`: Base de dados tratada e pronta para uso.
* `TelecomX_dicionario.md`: Dicionário das variáveis originais.
 
---
 
## 🚀 Como executar
Necessário ter Python e Jupyter Notebook instalados.
Bibliotecas necessárias: `pandas`, `seaborn`, `matplotlib`.