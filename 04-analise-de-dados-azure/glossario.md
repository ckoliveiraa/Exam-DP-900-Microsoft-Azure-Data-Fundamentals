# Glossário — Módulo 4 (Cargas de Trabalho de Análise no Azure)

## Análise em Larga Escala

| Termo | Definição |
|-------|-----------|
| **Análise em larga escala** | Processo de transformar grandes volumes de dados brutos em informação útil. |
| **Ingestão de dados** | Captura dos dados das fontes para a plataforma de análise. |
| **Processamento/transformação** | Limpeza, padronização e agregação dos dados (ETL/ELT). |
| **ETL** | Extract, Transform, Load — transforma os dados antes de carregá-los. |
| **ELT** | Extract, Load, Transform — carrega os dados brutos e transforma depois. |
| **Pipeline de dados** | Sequência automatizada de atividades que move e transforma dados. |

## Repositórios Analíticos

| Termo | Definição |
|-------|-----------|
| **Data warehouse** | Repositório de dados estruturados e modelados, otimizado para BI. |
| **Data lake** | Repositório de dados brutos de qualquer tipo; *schema-on-read*. |
| **Data lakehouse** | Modelo híbrido que une flexibilidade do lake e desempenho do warehouse. |
| **Esquema estrela** | Modelo analítico com tabela de fatos cercada por tabelas de dimensão. |
| **Data Lake Storage Gen2** | Armazenamento do Azure com namespace hierárquico, base de data lakes. |

## Serviços de Análise do Azure

| Termo | Definição |
|-------|-----------|
| **Azure Data Factory** | Serviço de integração de dados baseado em pipelines (ETL/ELT). |
| **Azure Synapse Analytics** | Plataforma de análise unificada (SQL + Spark + pipelines). |
| **Azure Databricks** | Plataforma de análise e ML baseada em Apache Spark; arquitetura lakehouse. |
| **Azure HDInsight** | Serviço gerenciado de frameworks open-source de big data. |
| **Microsoft Fabric** | Plataforma de análise SaaS tudo-em-um, com o data lake OneLake. |
| **OneLake** | Data lake central e único do Microsoft Fabric. |
| **Apache Spark** | Mecanismo de processamento distribuído de big data. |

## Análise em Tempo Real

| Termo | Definição |
|-------|-----------|
| **Processamento em lote (batch)** | Dados processados em grupos, em intervalos definidos; latência alta. |
| **Processamento em fluxo (streaming)** | Dados processados continuamente, ao chegar; latência baixa. |
| **Latência** | Tempo entre a geração do dado e o resultado da análise. |
| **Azure Stream Analytics** | Serviço para processar e consultar fluxos de dados em tempo real. |
| **Azure Event Hubs** | Serviço de ingestão de grandes volumes de eventos/streaming. |

## Power BI

| Termo | Definição |
|-------|-----------|
| **Power BI** | Plataforma de business intelligence da Microsoft. |
| **Power BI Desktop** | Aplicativo para criar modelos, relatórios e visualizações. |
| **Serviço do Power BI** | Plataforma online (SaaS) para publicar e compartilhar conteúdo. |
| **Power BI Mobile** | Aplicativo para consumir relatórios e painéis em dispositivos móveis. |
| **Modelo de dados** | Conjunto de tabelas relacionadas que alimenta os relatórios. |
| **DAX** | *Data Analysis Expressions* — linguagem de cálculos do Power BI. |
| **Relatório** | Conjunto de uma ou mais páginas de visualizações de um conjunto de dados. |
| **Painel (dashboard)** | Página única que reúne visuais de um ou mais relatórios. |
