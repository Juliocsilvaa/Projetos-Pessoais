# 🌎 Projeto 2 — Disponibilidade Temporal e Espacial de Dados Hidrológicos

Este projeto tem como objetivo de caracterizar a disponibilidade temporal e espacial de dados hidrológicos em uma região de estudo, a partir do acesso automatizado a bases públicas via API.

O trabalho envolve desde a identificação das estações de monitoramento até a visualização da abrangência temporal dos dados, permitindo avaliar qualidade, continuidade e resolução das informações disponíveis.

## 🎯 Objetivo

- Identificar estações de monitoramento em uma região de interesse;
- Acessar dados hidrológicos por meio de API;
- Avaliar a disponibilidade temporal das séries;
- Caracterizar a distribuição espacial das estações;
- Indicar discretização temporal e percentual de falhas nos dados.


## 🧠 Abordagem

1. **Identificação das Estações**
   - Consulta às fontes oficiais de dados hidrológicos;
   - Filtragem das estações pertencentes à região de estudo;
   - Organização das informações cadastrais.

2. **Acesso aos Dados via API**
   - Requisição automatizada de dados históricos;
   - Armazenamento estruturado em DataFrames;
   - Tratamento inicial e padronização temporal.

3. **Análise da Disponibilidade Temporal**
   - Identificação de períodos com dados válidos;
   - Cálculo de falhas e lacunas nas séries;
   - Classificação da discretização (horária, diária, etc.).

4. **Visualização**
   - Construção de diagrama de Gantt para representação da abrangência temporal;
   - Indicação de discretização e percentual de falhas via *hover*;
   - Mapeamento da localização das estações para análise espacial.

## 🛠️ Técnicas Utilizadas

- Acesso a dados via API
- Manipulação e organização de séries temporais
- Cálculo de falhas e métricas de disponibilidade
- Visualização temporal (Gantt)
- Visualização geoespacial
- Estruturação de código com funções


## 🧰 Ferramentas e Tecnologias

- **Python**
- **Pandas**
- **Requests**
- **Plotly**
- **Jupyter Notebook**



