# Glossário — Módulo 3 (Dados Não Relacionais no Azure)

## Armazenamento do Azure

| Termo | Definição |
|-------|-----------|
| **Armazenamento do Azure** | Serviço gerenciado para guardar dados não relacionais na nuvem. |
| **Conta de armazenamento** | Contêiner de nível superior que agrupa os serviços de armazenamento. |
| **Blob Storage** | Serviço para dados não estruturados armazenados como objetos. |
| **Azure Files** | Serviço de compartilhamento de arquivos via SMB/NFS. |
| **Table Storage** | Serviço NoSQL de chave-valor. |
| **Queue Storage** | Serviço de filas de mensagens entre componentes de aplicações. |
| **LRS** | *Locally Redundant Storage* — 3 cópias em um único datacenter. |
| **ZRS** | *Zone-Redundant Storage* — cópias em zonas de disponibilidade diferentes. |
| **GRS** | *Geo-Redundant Storage* — inclui cópia em região secundária. |
| **GZRS** | *Geo-Zone-Redundant Storage* — combina ZRS com região secundária. |

## Blob Storage

| Termo | Definição |
|-------|-----------|
| **Blob** | *Binary Large Object* — objeto/arquivo armazenado no Blob Storage. |
| **Contêiner** | Agrupamento de blobs dentro de uma conta de armazenamento. |
| **Block blob** | Tipo de blob para arquivos comuns (documentos, mídia). |
| **Append blob** | Tipo de blob otimizado para acréscimos (logs). |
| **Page blob** | Tipo de blob de acesso aleatório; base dos discos de VM. |
| **Camada de acesso (tier)** | Nível que define custo conforme a frequência de uso: Hot, Cool, Cold, Archive. |
| **Reidratação** | Processo de mover um blob da camada Archive para Hot/Cool antes de lê-lo. |
| **Gerenciamento de ciclo de vida** | Regras que movem ou excluem blobs automaticamente. |
| **Data Lake Storage Gen2** | Blob Storage com namespace hierárquico, para analytics de big data. |

## Files e Table Storage

| Termo | Definição |
|-------|-----------|
| **SMB / NFS** | Protocolos de compartilhamento de arquivos em rede usados pelo Azure Files. |
| **Entidade** | Item armazenado no Table Storage, com propriedades chave-valor. |
| **Partition Key** | Chave que agrupa entidades relacionadas na mesma partição. |
| **Row Key** | Chave que identifica uma entidade dentro de uma partição. |

## Azure Cosmos DB

| Termo | Definição |
|-------|-----------|
| **Azure Cosmos DB** | Banco NoSQL distribuído globalmente, gerenciado e de baixa latência. |
| **Distribuição global** | Replicação dos dados para várias regiões do Azure. |
| **Request Unit (RU)** | Unidade que mede o custo de processamento de uma operação. |
| **Throughput provisionado** | Modo em que se reserva uma quantidade fixa de RUs/s. |
| **Serverless** | Modo em que se paga apenas pelas RUs efetivamente consumidas. |
| **Autoscale** | Modo que ajusta as RUs automaticamente conforme a demanda. |
| **Multimodelo** | Capacidade de suportar diferentes modelos de dados via APIs. |
| **API for NoSQL** | API nativa do Cosmos DB; modelo de documentos JSON. |
| **API for MongoDB** | API compatível com aplicações MongoDB. |
| **API for Cassandra** | API compatível com aplicações Apache Cassandra. |
| **API for Gremlin** | API para dados de grafo (nós e arestas). |
| **API for Table** | API compatível com o Azure Table Storage. |
