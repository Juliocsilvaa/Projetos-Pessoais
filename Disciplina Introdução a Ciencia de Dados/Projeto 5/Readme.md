# 🔁 Projeto 5 — Reamostragem e Inferência Estatística com Bootstrapping

Este projeto tem como foco a aplicação de técnicas de **reamostragem estatística**, com ênfase no método de **Bootstrapping** como ferramenta de inferência não paramétrica.

O objetivo principal foi estimar estatísticas amostrais e seus respectivos **intervalos de confiança** a partir dos próprios dados observados, quantificando a variabilidade e a incerteza das estimativas sem depender de pressupostos rígidos sobre a distribuição populacional.

## 🎯 Objetivo

- Compreender o conceito de reamostragem estatística;
- Aplicar o método de bootstrapping para estimar estatísticas amostrais;
- Avaliar variabilidade e incerteza associadas às estimativas;
- Construir intervalos de confiança baseados em reamostragem;
- Comparar estimativas empíricas com estatísticas tradicionais.

## 🧠 Abordagem Metodológica

### 1️⃣ Conceito Teórico de Bootstrapping

O bootstrapping é uma técnica de reamostragem que consiste em:

- Sortear, com reposição, múltiplas amostras a partir do conjunto original;
- Calcular a estatística de interesse para cada reamostragem;
- Construir a distribuição empírica dessa estatística;
- Estimar variabilidade, erro padrão e intervalos de confiança.

Essa abordagem permite realizar inferência estatística mesmo quando:
- O tamanho da amostra é limitado;
- A distribuição populacional é desconhecida;
- As hipóteses paramétricas não são adequadas.



### 2️⃣ Implementação Computacional

A aplicação prática envolveu:

- Definição da estatística de interesse (ex: média, mediana, etc.);
- Geração de múltiplas reamostragens com reposição;
- Cálculo iterativo da estatística para cada amostra;
- Construção da distribuição empírica das estimativas;
- Cálculo do erro padrão;
- Estimativa de intervalos de confiança percentílicos.


## 📊 Análises Realizadas

- Distribuição da estatística estimada via bootstrapping;
- Comparação entre estimativa pontual e média das reamostragens;
- Avaliação da dispersão das estimativas;
- Construção de intervalos de confiança baseados em percentis.


## 🛠️ Técnicas Utilizadas

- Reamostragem com reposição
- Simulação computacional
- Inferência estatística não paramétrica
- Estimativa de erro padrão
- Construção de intervalos de confiança percentílicos
- Visualização da distribuição empírica


## 🧰 Ferramentas e Tecnologias

- **Python**
- **NumPy**
- **Pandas**
- **Jupyter Notebook**

