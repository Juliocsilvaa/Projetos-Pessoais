# 📊 Detecção de Consumo Não Autorizado em Sistemas de Abastecimento de Água Utilizando Ciência de Dados

Este projeto corresponde ao meu **Trabalho de Conclusão de Curso (TCC)** em Engenharia Civil e tem como objetivo aplicar técnicas de **ciência de dados e aprendizado de máquina** para identificar padrões de consumo anômalos em sistemas de abastecimento de água, associados a possíveis fraudes, vazamentos ou irregularidades operacionais.

A motivação do trabalho surge da importância da redução de perdas aparentes em sistemas de saneamento, que impactam diretamente a eficiência operacional, a sustentabilidade financeira das concessionárias e a disponibilidade hídrica.

O estudo propõe a detecção de irregularidades por meio da análise do comportamento de consumo dos usuários, com base no método desenvolvido por **Ghamkhar et al. (2023)**, que utiliza o algoritmo de aprendizado de máquina **não supervisionado DBSCAN**. Para lidar com a alta dimensionalidade e a baixa resolução dos dados, são empregadas métricas de complexidade baseadas em séries temporais, como a **Complexidade de Lempel-Ziv (LZC)**, capazes de capturar variabilidade, imprevisibilidade e rupturas de padrão no consumo.


## 🎯 Objetivo

Desenvolver um modelo analítico capaz de:
- Identificar consumos atípicos em ligações de água;
- Apoiar processos de fiscalização e tomada de decisão;
- Contribuir para estratégias de redução de perdas aparentes em sistemas de abastecimento de água.


## 🧠 Abordagem

O trabalho foi desenvolvido a partir da análise de séries históricas de consumo de unidades consumidoras, com foco na identificação de padrões de comportamento associados a irregularidades. A metodologia seguiu as seguintes etapas:

1. **Analise exploratoria (EDA) e Tratamento dos Dados**
   - Análise estatística inicial das variáveis;
   - Tipagem correta das colunas;
   - Identificação de valores ausentes e inconsistências;
   - Avaliação da distribuição e variabilidade dos consumos ao longo do tempo.
  
2. **Pré-processamento**
    - Remoção de colunas e registros não representativos;
    - Estruturação dos dados em formato adequado para análise temporal;
    - Padronização (normalização) das séries de consumo;
    - Segmentação das séries por unidade consumidora.
  
3. **Extração de Características de Séries Temporais (TSLF e LZC)**
   - Cálculo de métricas de variação, estabilidade e complexidade temporal;
   - Construção de vetores representativos do comportamento histórico de cada unidade;
   - Redução implícita da dimensionalidade por meio de atributos estatísticos compactos.

4. **Modelagem Não Supervisionada (Clusterização com DBSCAN)**
   - Aplicação do algoritmo DBSCAN (Density-Based Spatial Clustering of Applications with Noise);
   - Agrupamento das unidades consumidoras com base na similaridade dos atributos construídos;
   - Identificação automática de pontos classificados como ruído (outliers), interpretados como possíveis padrões anômalos;
   - Definição e ajuste dos parâmetros ε (*epsilon*) e *min_samples* para melhor representação da densidade dos dados.
   - Avaliação da qualidade dos agrupamentos por meio de métricas internas de clusterização e análise da separabilidade entre grupos.

  
5. **Análise dos resultados**
   - Caracterização do comportamento de consumo classificados como anômalos ;
   - Interpretação dos casos classificados como anômalos;
   - Identificação de rupturas abruptas ou padrões atípicos persistentes.
   - Discussão da viabilidade de aplicação do modelo como ferramenta de apoio à fiscalização em sistemas reais de abastecimento.

## 🛠️ Técnicas Utilizadas

- Análise exploratória de dados (EDA)
- Pré-processamento de dados
- Engenharia de atributos em séries temporais
- Extração de métricas de complexidade (LZC, TSLF)
- Redução implícita da dimensionalidade
- Clusterização não supervisionada baseada em densidade (DBSCAN)
- Avaliação interna de qualidade de agrupamentos

## 🧰 Ferramentas e Tecnologias

- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Numpy**
- **Jupyter Notebook**
