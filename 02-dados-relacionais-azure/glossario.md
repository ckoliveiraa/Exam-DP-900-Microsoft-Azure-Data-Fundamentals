# Glossário — Módulo 2 (Dados Relacionais no Azure)

## Conceitos Relacionais

| Termo | Definição |
|-------|-----------|
| **Modelo relacional** | Modelo que organiza os dados em tabelas relacionadas por chaves. |
| **Tabela (relação)** | Conjunto de dados sobre um tipo de entidade, em linhas e colunas. |
| **Linha (registro/tupla)** | Uma instância da entidade representada pela tabela. |
| **Coluna (campo/atributo)** | Uma propriedade da entidade, com tipo de dado definido. |
| **Chave primária** | Coluna que identifica unicamente cada linha; única e não nula. |
| **Chave estrangeira** | Coluna que referencia a chave primária de outra tabela. |
| **Integridade de entidade** | Regra: a chave primária é única e não nula. |
| **Integridade referencial** | Regra: a chave estrangeira aponta para um valor existente. |
| **Integridade de domínio** | Regra: os valores respeitam o tipo e as restrições da coluna. |

## Normalização

| Termo | Definição |
|-------|-----------|
| **Normalização** | Organização das tabelas para reduzir redundância e anomalias. |
| **Desnormalização** | Combinação de dados que aceita redundância para acelerar leitura. |
| **Anomalia de atualização** | Inconsistência causada por dados duplicados em várias linhas. |
| **Junção (join)** | Operação que combina linhas de duas ou mais tabelas relacionadas. |

## SQL

| Termo | Definição |
|-------|-----------|
| **SQL** | *Structured Query Language* — linguagem padrão dos bancos relacionais. |
| **DDL** | *Data Definition Language* — define estrutura (`CREATE`, `ALTER`, `DROP`). |
| **DML** | *Data Manipulation Language* — manipula dados (`SELECT`, `INSERT`, `UPDATE`, `DELETE`). |
| **DCL** | *Data Control Language* — controla permissões (`GRANT`, `REVOKE`, `DENY`). |
| **T-SQL** | Transact-SQL — dialeto SQL do SQL Server e do Azure SQL. |
| **WHERE** | Cláusula que filtra quais linhas uma operação afeta. |

## Objetos de Banco

| Termo | Definição |
|-------|-----------|
| **View (exibição)** | Consulta salva que age como tabela virtual; não armazena dados. |
| **Stored procedure** | Bloco de código SQL salvo no banco, executável sob demanda. |
| **Índice (index)** | Estrutura que acelera a busca de linhas por colunas. |
| **Índice clustered** | Define a ordem física das linhas; só um por tabela. |
| **Índice non-clustered** | Estrutura separada que aponta para as linhas; vários por tabela. |

## Serviços Azure

| Termo | Definição |
|-------|-----------|
| **IaaS** | *Infrastructure as a Service* — cliente gerencia SO e software. |
| **PaaS** | *Platform as a Service* — provedor gerencia infraestrutura e plataforma. |
| **Azure SQL Database** | Banco relacional PaaS totalmente gerenciado, para apps cloud-native. |
| **Azure SQL Managed Instance** | PaaS com alta compatibilidade com SQL Server local; ideal para migração. |
| **SQL Server em VM do Azure** | SQL Server em máquina virtual (IaaS); controle total do ambiente. |
| **Pool elástico** | Recurso que permite vários bancos compartilharem recursos. |
| **Azure Database for PostgreSQL** | Serviço gerenciado para o banco open-source PostgreSQL. |
| **Azure Database for MySQL** | Serviço gerenciado para o banco open-source MySQL. |
| **Azure Database for MariaDB** | Serviço gerenciado para MariaDB (em descontinuação). |
