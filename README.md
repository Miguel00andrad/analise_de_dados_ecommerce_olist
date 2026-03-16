# 📊 Otimização Logística e Análise de Satisfação (NPS) - E-commerce Olist

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)]()
[![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=google&logoColor=white)]()

🔗 **[Clique aqui para acessar o Dashboard Interativo no Looker Studio](https://lookerstudio.google.com/reporting/19e9d0a9-cd74-4466-a441-409850b7fa48)**

## 📌 O Problema de Negócio
O e-commerce brasileiro enfrenta desafios geográficos. O objetivo deste projeto de **Análise de Dados** foi investigar as bases de dados públicas da Olist (disponíveis no Kaggle) para entender as alavancas de crescimento da empresa e, principalmente, identificar os gargalos operacionais que impactam a satisfação do cliente (CSAT/NPS).

A análise foi dividida em duas frentes principais:
1. **Saúde Financeira e Vendas:** Faturamento bruto, ticket médio e categorias mais fortes.
2. **Logística e Experiência do Cliente:** O impacto do tempo de trânsito (SLA) e custos de frete regionais nas avaliações finais.

## 🛠️ Tecnologias e Metodologia
* **Python (Pandas/NumPy):** Utilizado no Google Colab para extração, tratamento de valores nulos, conversão de tipagens de data (datetime) e cruzamento de múltiplas tabelas relacionais (ETL). O script unificou milhares de linhas de pedidos, clientes e avaliações em uma base otimizada.
* **Looker Studio:** Desenvolvimento de um painel executivo (Dashboard) focado em UI/UX para facilitar a leitura de KPIs complexos, utilizando campos calculados para métricas ponderadas.

## 💡 Principais Descobertas (Insights)
Durante a análise exploratória, identifiquei um padrão crítico na retenção de clientes:

* **A Escadinha da Dor (Atraso = Detração):** Existe uma correlação fortíssima entre a quebra do SLA de entrega e o aumento exponencial de avaliações Nota 1. O tempo de espera provou ser o maior ofensor da satisfação do cliente.
* **A Barreira Regional do Frete:** O mapa de calor evidenciou que clientes das regiões Norte e Nordeste pagam tickets médios de frete severamente superiores aos do Sudeste (chegando a ultrapassar R$ 42 de média).
* **Sufocamento de Mercado:** Como consequência direta do frete alto, o volume de pedidos e a penetração de mercado no N/NE são desproporcionalmente baixos, indicando uma demanda reprimida.

## 📸 Telas do Dashboard

### 1. Visão Executiva e Financeira
*(Mapeamento de faturamento, volume de pedidos e ticket médio por categoria).*
![Visão Executiva](https://lookerstudio.google.com/reporting/19e9d0a9-cd74-4466-a441-409850b7fa48/page/Rh3rF)

### 2. Visão Logística e Satisfação
*(Análise de SLA, ofensores de nota e mapa de custos de distribuição).*
![Visão Logística](https://lookerstudio.google.com/reporting/19e9d0a9-cd74-4466-a441-409850b7fa48/page/p_glo4m1qu1d)

## 🚀 Plano de Ação Estratégico
Com base nos dados levantados, a recomendação para a diretoria de operações envolve:
1. **Revisão de Malha Logística no N/NE:** Priorizar a captação de parceiros logísticos regionais ou a implementação de minihubs de distribuição no Norte e Nordeste.
2. **Foco na Redução do Tempo de Trânsito:** O barateamento do frete e a entrega mais rápida são os fatores primários que irão alavancar a recuperação do NPS global da operação e destravar a expansão comercial em estados fora do eixo Sudeste.

---
*Projeto desenvolvido para fins de estudo e composição de portfólio em Análise de Dados.*
