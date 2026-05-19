# Simulado — Módulo 1 (Conceitos Centrais de Dados)

> **20 questões** no estilo DP-900. Respostas e justificativas ao final. Meta: **≥ 80%** (16 acertos).

---

### 1. Uma tabela de banco de dados com colunas e tipos definidos é um exemplo de quais dados?
- A) Não estruturados
- B) Estruturados
- C) Semiestruturados
- D) Binários

### 2. Um arquivo JSON em que cada registro pode ter campos diferentes é classificado como:
- A) Estruturado
- B) Não estruturado
- C) Semiestruturado
- D) Relacional

### 3. Qual destes é um exemplo de dado não estruturado?
- A) Uma planilha de vendas
- B) Um vídeo
- C) Uma tabela SQL
- D) Um documento XML

### 4. Em qual abordagem o esquema é validado no momento da gravação?
- A) Schema-on-read
- B) Schema-on-write
- C) Schema-on-delete
- D) Schema-on-query

### 5. Qual formato de arquivo é texto delimitado e tabular?
- A) JSON
- B) Parquet
- C) CSV
- D) Avro

### 6. Qual formato é orientado a linha e adequado para escrita/ingestão?
- A) Parquet
- B) ORC
- C) Avro
- D) CSV

### 7. Qual formato colunar é mais indicado para consultas analíticas em data lakes?
- A) Parquet
- B) XML
- C) TSV
- D) Avro

### 8. Por que formatos colunares comprimem melhor que formatos de linha?
- A) Usam menos colunas
- B) Agrupam valores do mesmo tipo, que se repetem
- C) São arquivos de texto
- D) Não armazenam o esquema

### 9. Quais são as três grandes opções de armazenamento de dados?
- A) SQL, NoSQL e XML
- B) Relacional, não relacional e arquivos
- C) Linha, coluna e grafo
- D) OLTP, OLAP e ETL

### 10. Qual tipo de banco NoSQL armazena nós e arestas?
- A) Documento
- B) Chave-valor
- C) Família de colunas
- D) Grafo

### 11. Um banco que associa uma chave única a um valor é do tipo:
- A) Documento
- B) Chave-valor
- C) Grafo
- D) Relacional

### 12. Um sistema de ponto de venda que registra vendas em tempo real é uma carga de trabalho:
- A) OLAP
- B) OLTP
- C) ETL
- D) Analítica

### 13. O que garante a propriedade de **atomicidade**?
- A) Os dados ficam criptografados
- B) A transação ocorre por inteiro ou não ocorre
- C) Transações não interferem entre si
- D) Os dados persistem após falha

### 14. Uma transação confirmada não se perde mesmo após uma queda de energia. Qual propriedade ACID descreve isso?
- A) Atomicidade
- B) Consistência
- C) Isolamento
- D) Durabilidade

### 15. Qual carga de trabalho é otimizada para leitura e agregação de grandes volumes históricos?
- A) OLTP
- B) OLAP
- C) Transacional
- D) Chave-valor

### 16. No processo **ELT**, em que ordem ocorrem as etapas?
- A) Extrair, Transformar, Carregar
- B) Extrair, Carregar, Transformar
- C) Carregar, Extrair, Transformar
- D) Transformar, Extrair, Carregar

### 17. Dados em OLAP costumam ser organizados de forma:
- A) Normalizada
- B) Desnormalizada (esquema estrela)
- C) Em chave-valor
- D) Sem esquema

### 18. Quem é responsável por backup, segurança e desempenho do banco de dados?
- A) Analista de dados
- B) Engenheiro de dados
- C) Administrador de banco de dados (DBA)
- D) Cientista de dados

### 19. Criar um pipeline que carrega dados de várias fontes é tarefa de qual função?
- A) DBA
- B) Engenheiro de dados
- C) Analista de dados
- D) Usuário final

### 20. Qual ferramenta está associada ao analista de dados para criar relatórios e dashboards?
- A) Azure Data Factory
- B) SQL Server Management Studio
- C) Power BI
- D) Azure Blob Storage

---

## Gabarito Comentado

1. **B** — Tabela com colunas e tipos definidos = dados estruturados.
2. **C** — Campos que variam por registro caracterizam dados semiestruturados.
3. **B** — Vídeo é dado não estruturado; os demais têm estrutura.
4. **B** — *Schema-on-write* valida o esquema na gravação.
5. **C** — CSV é texto delimitado e tabular.
6. **C** — Avro é orientado a linha, bom para escrita e ingestão.
7. **A** — Parquet é colunar e padrão para análise em data lakes.
8. **B** — Valores do mesmo tipo, juntos e repetidos, comprimem melhor.
9. **B** — Relacional, não relacional e armazenamento de arquivos.
10. **D** — Banco de grafo armazena nós (entidades) e arestas (relações).
11. **B** — Banco chave-valor associa uma chave única a um valor.
12. **B** — Registro de vendas em tempo real é carga transacional (OLTP).
13. **B** — Atomicidade = a transação ocorre por inteiro ou não ocorre.
14. **D** — Durabilidade garante a persistência após falhas.
15. **B** — OLAP é otimizado para leitura/agregação de dados históricos.
16. **B** — ELT = Extrair, Carregar e depois Transformar.
17. **B** — OLAP usa modelagem desnormalizada (esquema estrela).
18. **C** — Backup, segurança e desempenho do banco são tarefas do DBA.
19. **B** — Pipelines de dados são responsabilidade do engenheiro de dados.
20. **C** — Power BI é a ferramenta do analista de dados.
