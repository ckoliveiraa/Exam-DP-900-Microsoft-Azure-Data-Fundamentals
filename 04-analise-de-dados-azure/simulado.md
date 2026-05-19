# Simulado — Módulo 4 (Cargas de Trabalho de Análise no Azure)

> **20 questões** no estilo DP-900. Respostas e justificativas ao final. Meta: **≥ 80%** (16 acertos).

---

### 1. Qual é a primeira etapa do fluxo de análise em larga escala?
- A) Visualização
- B) Modelagem
- C) Ingestão
- D) Armazenamento

### 2. No processo ELT, a transformação ocorre:
- A) Antes de carregar os dados
- B) Depois de carregar os dados no destino
- C) Durante a ingestão
- D) Não há transformação

### 3. O que é um pipeline de dados?
- A) Um banco de dados relacional
- B) Uma sequência automatizada que move e transforma dados
- C) Um tipo de visualização
- D) Um formato de arquivo

### 4. Um repositório de dados estruturados, modelados e otimizados para BI é um:
- A) Data lake
- B) Data warehouse
- C) Blob Storage
- D) Banco OLTP

### 5. Qual repositório armazena dados brutos de qualquer tipo, sem transformação prévia?
- A) Data warehouse
- B) Data lake
- C) Banco relacional
- D) Table Storage

### 6. O modelo que combina flexibilidade do data lake com desempenho do data warehouse é o:
- A) Data mart
- B) Data lakehouse
- C) Banco NoSQL
- D) Esquema estrela

### 7. Qual serviço do Azure é usado para ingestão e transformação de dados via pipelines?
- A) Power BI
- B) Azure Data Factory
- C) Azure Stream Analytics
- D) Azure Cosmos DB

### 8. O Azure Synapse Analytics é melhor descrito como:
- A) Um banco NoSQL
- B) Uma plataforma de análise unificada
- C) Uma ferramenta de visualização
- D) Um serviço de armazenamento de arquivos

### 9. O Azure Databricks é baseado em qual tecnologia?
- A) SQL Server
- B) Apache Spark
- C) MongoDB
- D) Power Query

### 10. Qual plataforma é uma solução SaaS de análise tudo-em-um da Microsoft?
- A) Azure HDInsight
- B) Microsoft Fabric
- C) Azure Data Factory
- D) Azure Files

### 11. Como se chama o data lake central do Microsoft Fabric?
- A) DataLake
- B) OneLake
- C) BlobLake
- D) SynapseLake

### 12. O processamento em lote (batch) é caracterizado por:
- A) Latência baixa, dados processados ao chegar
- B) Latência alta, dados processados em grupos periodicamente
- C) Não usar armazenamento
- D) Processar apenas um registro por vez em tempo real

### 13. O processamento em fluxo (streaming) é indicado quando:
- A) A resposta imediata não é necessária
- B) É preciso reagir aos dados em tempo real
- C) Os dados são processados uma vez por mês
- D) Não há fonte de dados

### 14. Qual serviço do Azure é dedicado à análise de fluxos em tempo real?
- A) Azure Data Factory
- B) Azure Stream Analytics
- C) Azure Synapse Pipelines
- D) Power BI Desktop

### 15. Telemetria contínua de sensores de IoT é um exemplo de processamento:
- A) Em lote
- B) Em fluxo (streaming)
- C) Manual
- D) Relacional

### 16. Em qual componente do Power BI os relatórios são criados?
- A) Power BI Mobile
- B) Power BI Desktop
- C) Power BI Gateway
- D) OneLake

### 17. Qual componente do Power BI é usado para publicar e compartilhar conteúdo?
- A) Power BI Desktop
- B) Serviço do Power BI
- C) Power BI Mobile
- D) Azure Synapse

### 18. Qual a diferença entre relatório e painel no Power BI?
- A) Não há diferença
- B) O relatório tem uma página; o painel tem várias
- C) O relatório pode ter várias páginas; o painel tem uma única
- D) O painel só funciona offline

### 19. Para mostrar a tendência de vendas ao longo dos meses, a melhor visualização é:
- A) Gráfico de pizza
- B) Gráfico de linhas
- C) Mapa
- D) Cartão (KPI)

### 20. Qual linguagem é usada para criar medidas e colunas calculadas no Power BI?
- A) SQL
- B) DAX
- C) Python
- D) T-SQL

---

## Gabarito Comentado

1. **C** — A ingestão é a primeira etapa: captura os dados das fontes.
2. **B** — No ELT, a transformação ocorre depois da carga, já no destino.
3. **B** — Pipeline é uma sequência automatizada que move e transforma dados.
4. **B** — Data warehouse guarda dados estruturados e modelados para BI.
5. **B** — Data lake armazena dados brutos de qualquer tipo.
6. **B** — O data lakehouse combina lake e warehouse.
7. **B** — Azure Data Factory faz ingestão e transformação via pipelines.
8. **B** — Synapse Analytics é uma plataforma de análise unificada.
9. **B** — O Azure Databricks é baseado em Apache Spark.
10. **B** — Microsoft Fabric é a plataforma SaaS tudo-em-um.
11. **B** — O data lake central do Fabric é o OneLake.
12. **B** — Batch processa em grupos periodicamente, com latência alta.
13. **B** — Streaming é indicado quando é preciso reagir em tempo real.
14. **B** — Azure Stream Analytics é dedicado a fluxos em tempo real.
15. **B** — Telemetria contínua de IoT é processamento em fluxo (streaming).
16. **B** — Os relatórios são criados no Power BI Desktop.
17. **B** — O Serviço do Power BI publica e compartilha conteúdo.
18. **C** — Relatório pode ter várias páginas; painel tem uma única.
19. **B** — Gráfico de linhas é ideal para tendências ao longo do tempo.
20. **B** — DAX é a linguagem de cálculos do Power BI.
