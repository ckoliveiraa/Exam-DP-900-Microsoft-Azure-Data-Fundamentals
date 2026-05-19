# Trilha Rápida — Módulo 3 (Dados Não Relacionais no Azure)

> Revisão de véspera, focada em **responder questões**. Leia os gatilhos, os fatos e as pegadinhas.

---

## 🎯 Gatilhos de questão

| Se a questão menciona... | A resposta gira em torno de... |
|--------------------------|--------------------------------|
| Imagens, vídeos, backups, objetos não estruturados | **Blob Storage** |
| Compartilhamento de arquivos, SMB/NFS, unidade de rede | **Azure Files** |
| NoSQL chave-valor simples e barato | **Table Storage** |
| Dados raramente acessados, custo mínimo de guarda | Camada **Archive** |
| Dados muito acessados | Camada **Hot** |
| Cópia em região secundária (recuperação de desastre) | **GRS** |
| Namespace hierárquico para big data | **Data Lake Storage Gen2** |
| NoSQL distribuído globalmente, baixa latência | **Azure Cosmos DB** |
| Desempenho/custo de operações no Cosmos DB | **Request Units (RUs)** |
| Dados muito conectados (grafo) | Cosmos DB — **API for Gremlin** |
| Projeto novo no Cosmos DB | **API for NoSQL** |

---

## 📌 Fatos que mais caem

- **4 serviços da conta de armazenamento:** Blob, Files, Table, Queue.
- Hierarquia do Blob: **conta → contêiner → blob**.
- Camadas de acesso: **Hot, Cool, Cold, Archive** (mais usado/mais caro → menos usado/mais barato).
- Table Storage: entidade identificada por **Partition Key + Row Key**.
- Cosmos DB tem **5 APIs:** NoSQL, MongoDB, Cassandra, Gremlin, Table.
- Redundância: **LRS** (um datacenter) → **ZRS** → **GRS** → **GZRS**.

---

## ⚠️ Pegadinhas

- A camada **Archive** exige **reidratação** antes de ler — não é acesso imediato.
- **Queue Storage** existe na conta de armazenamento, mas o foco do exame é Blob/Files/Table.
- A **API do Cosmos DB** é escolhida na criação da conta e **não muda** depois.
- MongoDB/Cassandra/Table existem para **compatibilidade/migração**; para projeto novo, use **NoSQL**.

---

[← Voltar ao módulo](./README.md)
