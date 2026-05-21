# Análise de Mercado: Estabelecimentos em Los Angeles

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-ADADAD?style=for-the-badge)

## 📌 Visão Geral do Projeto
Este projeto analisa o mercado de estabelecimentos alimentícios da cidade de Los Angeles com o objetivo de apoiar a decisão de abertura de uma cafeteria inovadora atendida por robôs. A partir de dados públicos sobre restaurantes, foram investigados tipos de estabelecimento, presença de redes, número de assentos e distribuição geográfica por rua.

## 🎯 Objetivos de Negócio
* **Análise de Mercado:** Entender a composição do setor de alimentação em LA por tipo de estabelecimento e modelo (rede vs independente).
* **Análise Geográfica:** Identificar as ruas com maior e menor concentração de estabelecimentos.
* **Apoio à Decisão:** Recomendar estratégia de entrada no mercado para uma cafeteria automatizada.

## 🛠️ Stack Técnica
* **Linguagem:** Python
* **Manipulação de Dados:** Pandas
* **Visualização:** Matplotlib, Seaborn, Plotly Express

## 📉 Metodologia
1. **Preparação de Dados:** Limpeza de nulos, conversão de tipos e extração de nomes de rua a partir de endereços via regex.
2. **Análise de Tipos:** Proporção de estabelecimentos por categoria e comparação entre redes e independentes.
3. **Análise de Assentos:** Média de assentos por tipo de estabelecimento e por rua.
4. **Análise Geográfica:** Top 10 ruas com mais estabelecimentos e distribuição de ruas com apenas um restaurante.

## 🏆 Resultados e Conclusões
* **75% do mercado** é dominado por restaurantes — cafeterias representam apenas 4.5%, indicando baixa concorrência no segmento.
* **60% dos estabelecimentos** são independentes, sem filiação a redes.
* Redes tendem a ter **mais unidades com menos assentos**, priorizando rotatividade — modelo compatível com cafeterias de atendimento rápido.
* Mais da metade das ruas de LA tem **apenas um estabelecimento**, apontando oportunidade em locais menos saturados.
* **Recomendação:** Abrir uma unidade independente em uma rua com baixa concorrência para validar o modelo de negócio antes de considerar expansão em rede.

---

### 📂 Estrutura do Repositório
* `projeto10.ipynb`: Notebook Jupyter contendo toda a análise e visualizações.
* `rest_data_us_upd.csv`: Dataset com dados de estabelecimentos alimentícios de Los Angeles.

---
**Enzo Bombassaro de Freitas** | *Data Analyst* | [LinkedIn](https://www.linkedin.com/in/enzo-bombassaro/) | [GitHub](https://github.com/ezodia1)
