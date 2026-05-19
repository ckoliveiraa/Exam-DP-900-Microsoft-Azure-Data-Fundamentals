# Trilha Rápida — Módulo 1 (Conceitos Centrais de Dados)

> Revisão de véspera, focada em **responder questões**. Leia os gatilhos, os fatos e as pegadinhas.

---

## 🎯 Gatilhos de questão

| Se a questão menciona... | A resposta gira em torno de... |
|--------------------------|--------------------------------|
| Esquema fixo, tabelas, linhas e colunas | Dados **estruturados** |
| JSON, XML, campos que variam por registro | Dados **semiestruturados** |
| Imagem, vídeo, áudio, PDF, e-mail | Dados **não estruturados** |
| Esquema validado na **gravação** | *Schema-on-write* (relacional) |
| Esquema aplicado na **leitura** | *Schema-on-read* (data lake) |
| Formato orientado a **linha**, boa para escrita | **Avro** |
| Formato orientado a **coluna**, boa para análise | **Parquet** / **ORC** |
| Transações pequenas, rápidas e frequentes do dia a dia | **OLTP** |
| Análise de grandes volumes históricos, agregação | **OLAP** |
| "Tudo ou nada" | Atomicidade (**ACID**) |
| Transação que persiste após falha | Durabilidade (**ACID**) |
| Criar pipelines, ETL, integrar fontes | **Engenheiro de dados** |
| Backup, segurança, desempenho do banco | **DBA** |
| Relatórios, dashboards, Power BI | **Analista de dados** |

---

## 📌 Fatos que mais caem

- **3 tipos de dados:** estruturado, semiestruturado, não estruturado.
- **ACID** = Atomicidade, Consistência, Isolamento, Durabilidade.
- **OLTP** = normalizado, escrita rápida; **OLAP** = desnormalizado, leitura/agregação.
- **ETL** transforma antes de carregar; **ELT** carrega e transforma depois.
- **3 funções:** DBA (mantém o banco), engenheiro (move/prepara dados), analista (gera insights).

---

## ⚠️ Pegadinhas

- Metadados de um arquivo (nome, tamanho, data) **não** tornam o conteúdo estruturado.
- Avro é de **linha** (não confunda com Parquet/ORC, que são de coluna).
- "Global em milissegundos" e baixa latência **não** são tema deste módulo — é Cosmos DB (Módulo 3).
- Power BI → **analista**; Data Factory → **engenheiro**. Não troque.

---

[← Voltar ao módulo](./README.md)
