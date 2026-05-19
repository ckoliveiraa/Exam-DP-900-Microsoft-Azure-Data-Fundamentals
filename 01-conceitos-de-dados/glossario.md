# Glossário — Módulo 1 (Conceitos Centrais de Dados)

## Tipos e Representação de Dados

| Termo | Definição |
|-------|-----------|
| **Dados** | Fatos sobre coisas, eventos e entidades do mundo real. |
| **Dados estruturados** | Dados com esquema fixo, organizados em tabelas (linhas e colunas). |
| **Dados semiestruturados** | Dados com estrutura flexível e autodescrita; campos podem variar por registro (JSON, XML). |
| **Dados não estruturados** | Dados sem esquema definido, como imagens, vídeos e documentos. |
| **Esquema (schema)** | Definição da estrutura dos dados — tabelas, colunas e tipos. |
| **Schema-on-write** | O esquema é aplicado e validado no momento da **gravação**. |
| **Schema-on-read** | O esquema é aplicado apenas na **leitura** dos dados. |

## Formatos de Arquivo

| Termo | Definição |
|-------|-----------|
| **CSV / TSV** | Texto delimitado por vírgula/tabulação; formato tabular simples. |
| **JSON** | Formato de texto hierárquico de pares chave-valor; padrão de APIs e bancos de documentos. |
| **XML** | Formato de texto hierárquico baseado em tags; comum em sistemas legados. |
| **Avro** | Formato binário orientado a **linha**; bom para escrita e ingestão. |
| **Parquet** | Formato binário orientado a **coluna**; otimizado para leitura analítica. |
| **ORC** | Formato binário colunar (*Optimized Row Columnar*); boa compressão e leitura. |
| **Orientado a linha** | Armazena o registro inteiro junto; favorece escrita. |
| **Orientado a coluna** | Armazena valores da mesma coluna juntos; favorece leitura analítica e compressão. |

## Armazenamento

| Termo | Definição |
|-------|-----------|
| **Banco relacional** | Banco baseado em tabelas com esquema fixo, relacionadas por chaves; usa SQL. |
| **Banco não relacional (NoSQL)** | Banco com esquema flexível; tipos: documento, chave-valor, família de colunas, grafo. |
| **Banco de documento** | NoSQL que armazena cada entidade como um documento JSON. |
| **Banco chave-valor** | NoSQL que associa uma chave única a um valor. |
| **Banco de família de colunas** | NoSQL com linhas e colunas agrupadas em famílias. |
| **Banco de grafo** | NoSQL que armazena nós (entidades) e arestas (relações). |
| **Chave primária** | Coluna que identifica unicamente cada linha de uma tabela. |
| **Chave estrangeira** | Coluna que referencia a chave primária de outra tabela. |
| **Armazenamento de arquivos** | Guarda dados como arquivos/objetos, sem esquema (ex.: Blob Storage). |

## Cargas de Trabalho

| Termo | Definição |
|-------|-----------|
| **Transação** | Unidade lógica de trabalho que deve ser concluída por inteiro. |
| **OLTP** | *Online Transaction Processing* — carga transacional do dia a dia. |
| **OLAP** | *Online Analytical Processing* — carga analítica sobre dados históricos. |
| **ACID** | Atomicidade, Consistência, Isolamento e Durabilidade — garantias de transações. |
| **Atomicidade** | A transação ocorre por inteiro ou não ocorre. |
| **Consistência** | Os dados passam de um estado válido para outro estado válido. |
| **Isolamento** | Transações simultâneas não interferem umas nas outras. |
| **Durabilidade** | Uma transação confirmada persiste mesmo após falhas. |
| **Normalização** | Organização dos dados para reduzir redundância (típica de OLTP). |
| **Desnormalização** | Combinação de dados para acelerar leitura (típica de OLAP). |
| **ETL** | Extract, Transform, Load — transforma os dados antes de carregá-los. |
| **ELT** | Extract, Load, Transform — carrega os dados brutos e transforma depois. |
| **Esquema estrela** | Modelo analítico com tabela de fatos cercada por tabelas de dimensão. |

## Funções

| Termo | Definição |
|-------|-----------|
| **DBA** | Administrador de banco de dados — cuida de disponibilidade, segurança, backup e desempenho. |
| **Engenheiro de dados** | Constrói e mantém pipelines de dados e processos de ETL/ELT. |
| **Analista de dados** | Explora dados e cria relatórios e visualizações para apoiar decisões. |
