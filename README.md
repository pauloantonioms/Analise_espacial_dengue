# 🦟 Análise espacial de pacientes com dengue com sinais de alarme e dengue grave no Nordeste (2024)

Este repositório apresenta a análise completa dos casos de dengue com sinais de alarme e dengue grave registrados na região Nordeste do Brasil entre janeiro e setembro de 2024, com foco na identificação de padrões espaciais, áreas de risco, autocorrelação espacial e associação com fatores socioambientais e climáticos.

O trabalho foi desenvolvido como parte de um projeto de **Iniciação Científica (PICVOL/UFS)**, utilizando técnicas de estatística espacial, análise epidemiológica e geoprocessamento.

---

## 📌 Objetivos do Estudo

### Objetivo Geral
Conhecer melhor os aspectos relacionados a incidência da dengue com sinais de alarme e dengue grave na região Nordeste do Brasil.

### Objetivos Específicos
- Caracterizar os pacientes com dengue com sinais de alarme e dengue grave no Nordeste;
- Verificar a existência de autocorrelação espacial da incidência e do percentual de pacientes com sinais de alarme e dengue grave no Nordeste;
- Verificar a existência de padrões na distribuição espacial da incidência e do percentual de pacientes com sinais de alarme e dengue grave no Nordeste;
- Encontrar o Risco Relativo da infecção e da ocorrência de dengue com sinais de alarme e dengue grave no Nordeste;
- Relacionar determinantes sociais, fatores ambientais e climáticos com a incidência e do percentual de pacientes com sinais de alarme e dengue grave no Nordeste.

---

## 🗺️ Metodologia

- **Tipo de estudo:** Ecológico, com unidade de análise municipal.  
- **Período analisado:** Jan–Set 2024.  
- **Dados epidemiológicos:** SINAN/DATASUS.  
- **Dados socioambientais:** Censo 2022 (IBGE/SIDRA), cobertura de saúde (APS/Ministério da Saúde).  

### Ferramentas
- **R 4.3.3 (RStudio)**  
- Pacotes: `geobr`, `spdep`, entre outros.  

### Análises aplicadas
- Taxa de incidência padronizada (100 mil hab.)  
- Estimador Bayesiano Empírico Global  
- Índice de Moran (Global e Local)  
- LISA Maps (uni e bivariados)  
- Escaneamento de risco (Cluster e RR)  

---

## 📊 Principais Resultados

### Perfil dos Pacientes
- **7.692 casos analisados**  
- 91,63%: Dengue com sinais de alarme  
- 8,37%: Dengue grave  
- Predomínio de:  
  - Adultos 18–59 anos (57,12%)  
  - Mulheres (57,72%)  
  - Cor parda (76,43%)  

### Sintomas mais frequentes
- **Sinais de alarme:** dor abdominal (51,8%), queda de plaquetas (46,24%)  
- **Dengue grave:** taquicardia (31,83%), hematêmese (24,38%)  

### Distribuição Espacial
- Bahia concentra as maiores taxas de incidência, incluindo um outlier extremo:  
  - **Piripá (BA): 1815 casos / 100 mil hab.**  
- 93 municípios classificados como **Alto-Alto** (alto risco).  
- Ceará apresentou o maior número de municípios sem registros.  

### Associação com fatores socioambientais
- **Desmatamento:** correlação espacial positiva.  
- **Cobertura de agentes de saúde e atenção básica:** correlação negativa.  
- **Abastecimento de água:** clusters Alto-Alto concentrados na Bahia.  
- **Esgotamento sanitário:** associação espacial negativa.
- **Destino do Lixo:** associação espacial negativa.  
---

## 📌 Conclusões

A análise espacial demonstrou que:

- A dengue grave e com sinais de alarme apresenta **forte dependência espacial**, com clusters bem definidos.  
- A **Bahia concentra os principais hotspots** epidemiológicos.  
- Determinantes ambientais e sociais desempenham papel significativo na incidência.  
- O uso de ferramentas espaciais é essencial para vigilância epidemiológica e alocação eficiente de recursos, como vacinação e controle vetorial.  


## 📘 Acesso ao Relatório Completo

[**Relatório – Análise Espacial da Dengue no Nordeste (2024)**](Relatório_Final_Paulo.pdf)


