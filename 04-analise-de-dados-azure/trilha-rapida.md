# Trilha Rápida — Módulo 4 (Cargas de Trabalho de Análise no Azure)

> Revisão de véspera, focada em **responder questões**. Leia os gatilhos, os fatos e as pegadinhas.

---

## 🎯 Gatilhos de questão

| Se a questão menciona... | A resposta gira em torno de... |
|--------------------------|--------------------------------|
| Capturar dados das fontes | **Ingestão** |
| Transformar **depois** de carregar | **ELT** (destino: data lake) |
| Transformar **antes** de carregar | **ETL** (destino: data warehouse) |
| Dados estruturados, modelados, BI | **Data warehouse** |
| Dados brutos de qualquer tipo, baixo custo | **Data lake** |
| Híbrido: flexibilidade do lake + desempenho do warehouse | **Lakehouse** |
| Ingestão e transformação via pipelines | **Azure Data Factory** |
| Análise unificada (SQL + Spark + pipelines) | **Azure Synapse Analytics** |
| Análise e machine learning com Spark | **Azure Databricks** |
| Plataforma SaaS tudo-em-um, com OneLake | **Microsoft Fabric** |
| Processar dados em grupos, periodicamente | **Batch** (lote) |
| Reagir a dados em tempo real | **Streaming** (fluxo) |
| Análise de fluxos em tempo real | **Azure Stream Analytics** |
| Criar relatórios e visualizações | **Power BI Desktop** |
| Publicar e compartilhar conteúdo | **Serviço do Power BI** |

---

## 📌 Fatos que mais caem

- Fluxo da análise: **ingestão → processamento → armazenamento → modelagem → visualização**.
- **Batch** = latência alta, em grupos; **streaming** = latência baixa, contínuo.
- **Data Factory** move/transforma; **não** armazena nem analisa.
- **OneLake** é o data lake central do Microsoft Fabric.
- Power BI: **Desktop** (criar) → **Serviço** (publicar) → **Mobile** (consumir).
- Cálculos no Power BI usam a linguagem **DAX**.

---

## ⚠️ Pegadinhas

- **Relatório** = várias páginas, um conjunto de dados; **painel** = uma página, vários relatórios.
- Telemetria de IoT contínua → **streaming**, não batch.
- Databricks é baseado em **Apache Spark** (não em SQL Server).
- Gráfico de **linhas** para tendência no tempo; **colunas** para comparar categorias.

---

[← Voltar ao módulo](./README.md)
