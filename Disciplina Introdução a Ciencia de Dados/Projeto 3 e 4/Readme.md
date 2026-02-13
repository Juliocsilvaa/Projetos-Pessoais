# 🌧️ Projeto 3 e 4 — Comparação de Dados Pluviométricos e Análise Espacial (GPM/NASA)

Este projeto integra duas etapas complementares desenvolvidas na disciplina de **Introdução à Ciência de Dados**:

- **Projeto 3:** Comparação entre dados de precipitação observados em solo e estimativas por satélite (missão GPM/NASA);
- **Projeto 4:** Representação espacial das estações de monitoramento e da área (pixel) correspondente às estimativas satelitais.

O objetivo central foi avaliar diferenças entre fontes de dados pluviométricos e compreender suas implicações temporais e espaciais.


# 📊 Projeto 3 — Comparação entre Dados Observados e Estimativas por Satélite

## 🎯 Objetivo

- Acessar e organizar dados pluviométricos observados em solo;
- Acessar dados de precipitação estimados pela missão GPM (NASA);
- Sincronizar temporalmente as séries;
- Comparar padrões, diferenças e tendências entre as fontes;
- Caracterizar o comportamento típico das estimativas e suas variações ao longo do tempo.

## 🧠 Abordagem

1. **Aquisição dos Dados**
   - Coleta de dados observados em estações de monitoramento;
   - Acesso aos dados da missão GPM;
   - Armazenamento estruturado em DataFrames.

2. **Sincronização Temporal**
   - Alinhamento das séries com base em períodos comuns;
   - Geração de séries de diferenças síncronas;
   - Tratamento de falhas e lacunas.

3. **Análise Comparativa**
   - Avaliação estatística das diferenças entre as fontes;
   - Análise do comportamento das estimativas ao longo do tempo;
   - Identificação de padrões de superestimativa ou subestimativa.

4. **Visualização**
   - Gráficos temporais em diferentes discretizações;
   - Representação das diferenças acumuladas;
   - Análise visual da variabilidade entre as fontes.

---

# 🗺️ Projeto 4 — Representação Espacial das Estações e Pixels do GPM

## 🎯 Objetivo

- Identificar as coordenadas geográficas das estações de monitoramento;
- Determinar o pixel correspondente da estimativa GPM;
- Estimar os limites espaciais do pixel;
- Representar espacialmente estações e área de estimativa.

## 🧠 Abordagem

1. **Georreferenciamento**
   - Organização das coordenadas das estações;
   - Identificação da grade espacial da missão GPM.

2. **Cálculo da Área Representativa**
   - Estimativa dos limites do pixel correspondente;
   - Conversão de coordenadas para visualização cartográfica.

3. **Visualização Espacial**
   - Construção de mapas com localização das estações;
   - Representação gráfica do pixel associado;
   - Análise da relação espacial entre observação pontual e estimativa em grade.


## 🛠️ Técnicas Utilizadas

- Manipulação de séries temporais
- Sincronização de dados multifuente
- Cálculo de diferenças e métricas estatísticas
- Visualização temporal comparativa
- Análise geoespacial
- Manipulação de coordenadas geográficas


## 🧰 Ferramentas e Tecnologias

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Plotly**
- **Jupyter Notebook**



