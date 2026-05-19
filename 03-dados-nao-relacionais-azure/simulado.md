# Simulado — Módulo 3 (Dados Não Relacionais no Azure)

> **20 questões** no estilo DP-900. Respostas e justificativas ao final. Meta: **≥ 80%** (16 acertos).

---

### 1. Qual destes NÃO é um serviço de uma conta de armazenamento do Azure?
- A) Blob Storage
- B) Table Storage
- C) Azure SQL Database
- D) Queue Storage

### 2. Os dados no Armazenamento do Azure são, por padrão:
- A) Públicos e não criptografados
- B) Criptografados em repouso e replicados
- C) Armazenados sem redundância
- D) Acessíveis só via FTP

### 3. Qual opção de redundância inclui uma cópia em região secundária?
- A) LRS
- B) ZRS
- C) GRS
- D) Nenhuma

### 4. O Azure Blob Storage é mais adequado para:
- A) Dados relacionais com esquema fixo
- B) Dados não estruturados como imagens e vídeos
- C) Tabelas normalizadas
- D) Filas de mensagens

### 5. Qual é a hierarquia do Blob Storage?
- A) Conta → blob → contêiner
- B) Contêiner → conta → blob
- C) Conta → contêiner → blob
- D) Blob → contêiner → conta

### 6. Qual tipo de blob é otimizado para operações de acréscimo, como logs?
- A) Block blob
- B) Append blob
- C) Page blob
- D) Archive blob

### 7. Qual camada de acesso é a mais barata para armazenar dados raramente acessados?
- A) Hot
- B) Cool
- C) Cold
- D) Archive

### 8. Para ler dados na camada Archive, é necessário:
- A) Nada, o acesso é imediato
- B) Reidratar os dados para Hot ou Cool
- C) Excluir e recriar o blob
- D) Mudar a conta de armazenamento

### 9. Dados acessados com muita frequência devem ficar em qual camada?
- A) Hot
- B) Cool
- C) Cold
- D) Archive

### 10. O que adiciona o Azure Data Lake Storage Gen2 ao Blob Storage?
- A) Suporte a SQL
- B) Namespace hierárquico (pastas reais)
- C) Criptografia
- D) Replicação automática

### 11. O Azure Files permite acessar arquivos por meio de quais protocolos?
- A) HTTP e FTP
- B) SMB e NFS
- C) ODBC e JDBC
- D) SQL e T-SQL

### 12. Um cenário ideal para o Azure Files é:
- A) Armazenar discos de máquinas virtuais
- B) Substituir um servidor de arquivos local compartilhado
- C) Executar consultas analíticas
- D) Hospedar um banco relacional

### 13. O Azure Table Storage é um banco de dados do tipo:
- A) Relacional
- B) NoSQL de chave-valor
- C) Grafo
- D) Documento

### 14. No Table Storage, uma entidade é identificada por:
- A) Apenas a Row Key
- B) Apenas a Partition Key
- C) Partition Key + Row Key
- D) Uma chave estrangeira

### 15. Qual recurso do Table Storage agrupa entidades relacionadas para melhorar a escala?
- A) Row Key
- B) Partition Key
- C) Índice clustered
- D) Contêiner

### 16. Qual é a principal característica do Azure Cosmos DB?
- A) É um banco relacional com esquema fixo
- B) É um banco NoSQL distribuído globalmente e de baixa latência
- C) Só funciona em uma região
- D) Não é gerenciado

### 17. Como o desempenho do Cosmos DB é medido e pago?
- A) Em gigabytes
- B) Em Request Units (RUs)
- C) Em número de tabelas
- D) Em horas de CPU

### 18. Qual destes é um caso de uso típico do Cosmos DB?
- A) Relatório financeiro de fim de mês em lote
- B) Telemetria de dispositivos IoT em escala global
- C) Backup de arquivos antigos
- D) Servidor de arquivos compartilhado

### 19. Qual API do Cosmos DB é recomendada para um projeto novo?
- A) API for MongoDB
- B) API for Cassandra
- C) API for NoSQL
- D) API for Table

### 20. Uma aplicação precisa armazenar dados altamente conectados (rede de relacionamentos). Qual API do Cosmos DB usar?
- A) API for NoSQL
- B) API for Gremlin
- C) API for Table
- D) API for MongoDB

---

## Gabarito Comentado

1. **C** — Azure SQL Database é um serviço relacional, não faz parte da conta de armazenamento.
2. **B** — Os dados são criptografados em repouso e replicados automaticamente.
3. **C** — GRS (Geo-Redundant Storage) inclui cópia em região secundária.
4. **B** — Blob Storage é para dados não estruturados (imagens, vídeos).
5. **C** — A hierarquia é conta → contêiner → blob.
6. **B** — Append blob é otimizado para acréscimos, como logs.
7. **D** — Archive é a camada mais barata para armazenar.
8. **B** — Dados em Archive precisam ser reidratados para Hot/Cool antes da leitura.
9. **A** — Dados acessados com frequência ficam na camada Hot.
10. **B** — O Data Lake Storage Gen2 adiciona namespace hierárquico.
11. **B** — O Azure Files usa os protocolos SMB e NFS.
12. **B** — O Azure Files substitui servidores de arquivos compartilhados.
13. **B** — Table Storage é um NoSQL de chave-valor.
14. **C** — A entidade é identificada por Partition Key + Row Key.
15. **B** — A Partition Key agrupa entidades e influencia a escala.
16. **B** — Cosmos DB é NoSQL distribuído globalmente e de baixa latência.
17. **B** — O desempenho é medido em Request Units (RUs).
18. **B** — Telemetria IoT em escala global é um caso clássico do Cosmos DB.
19. **C** — A API for NoSQL é a nativa, recomendada para projetos novos.
20. **B** — A API for Gremlin é para dados de grafo (altamente conectados).
