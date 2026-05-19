# Simulado — Módulo 2 (Dados Relacionais no Azure)

> **20 questões** no estilo DP-900. Respostas e justificativas ao final. Meta: **≥ 80%** (16 acertos).

---

### 1. No modelo relacional, uma linha de uma tabela representa:
- A) Um atributo
- B) Uma instância de uma entidade
- C) Um tipo de dado
- D) Uma consulta

### 2. Qual elemento identifica unicamente cada linha de uma tabela?
- A) Chave estrangeira
- B) Índice
- C) Chave primária
- D) View

### 3. Uma coluna que referencia a chave primária de outra tabela é uma:
- A) Chave primária
- B) Chave estrangeira
- C) Chave composta
- D) Restrição de domínio

### 4. O que garante a integridade referencial?
- A) Que a chave primária não se repita
- B) Que a chave estrangeira aponte para um valor existente
- C) Que os tipos de dados estejam corretos
- D) Que não haja valores nulos

### 5. Qual é o principal objetivo da normalização?
- A) Acelerar a leitura
- B) Reduzir a redundância de dados
- C) Aumentar o número de tabelas
- D) Eliminar as chaves estrangeiras

### 6. Um banco altamente normalizado tende a exigir, na leitura:
- A) Menos tabelas
- B) Mais junções (joins)
- C) Menos índices
- D) Mais redundância

### 7. Qual família de comandos SQL é usada para definir a estrutura do banco?
- A) DML
- B) DCL
- C) DDL
- D) TCL

### 8. O comando `SELECT` pertence a qual família?
- A) DDL
- B) DML
- C) DCL
- D) DDL e DCL

### 9. Qual comando adiciona novas linhas a uma tabela?
- A) UPDATE
- B) INSERT
- C) ALTER
- D) CREATE

### 10. O que acontece ao executar `DELETE FROM Cliente` sem `WHERE`?
- A) Nada, gera erro
- B) Exclui apenas a primeira linha
- C) Exclui todas as linhas da tabela
- D) Exclui a tabela inteira

### 11. Qual é o dialeto SQL do Azure SQL?
- A) PL/SQL
- B) PL/pgSQL
- C) T-SQL
- D) SQL/PSM

### 12. O que é uma view?
- A) Uma cópia física da tabela
- B) Uma consulta salva que age como tabela virtual
- C) Um índice especial
- D) Um backup automático

### 13. Um bloco de código SQL salvo no banco, que aceita parâmetros, é:
- A) Uma view
- B) Um índice
- C) Um stored procedure
- D) Uma chave estrangeira

### 14. Qual a principal vantagem de um índice?
- A) Reduz o espaço em disco
- B) Acelera a busca de linhas
- C) Acelera as operações de escrita
- D) Elimina a necessidade de chave primária

### 15. Quantos índices clustered uma tabela pode ter?
- A) Nenhum
- B) Apenas um
- C) Até três
- D) Ilimitados

### 16. Qual serviço da família Azure SQL é classificado como IaaS?
- A) Azure SQL Database
- B) Azure SQL Managed Instance
- C) SQL Server em VMs do Azure
- D) Azure Database for MySQL

### 17. Uma empresa quer migrar um SQL Server local para a nuvem com o mínimo de alterações. Qual serviço escolher?
- A) Azure SQL Database (banco único)
- B) Azure SQL Managed Instance
- C) Azure Database for PostgreSQL
- D) Azure Cosmos DB

### 18. O que é um pool elástico no Azure SQL Database?
- A) Um backup distribuído
- B) Um conjunto de recursos compartilhado por vários bancos
- C) Um tipo de índice
- D) Um servidor virtual

### 19. Qual destes é um serviço gerenciado para banco open-source no Azure?
- A) Azure SQL Managed Instance
- B) Azure Database for PostgreSQL
- C) SQL Server em VM
- D) Azure Cosmos DB

### 20. Em um serviço de banco de dados PaaS, quem é responsável pelos patches e backups?
- A) O cliente
- B) O Azure (provedor)
- C) Um parceiro externo
- D) Ninguém — não há patches

---

## Gabarito Comentado

1. **B** — Uma linha é uma instância (registro) da entidade.
2. **C** — A chave primária identifica unicamente cada linha.
3. **B** — Chave estrangeira referencia a chave primária de outra tabela.
4. **B** — Integridade referencial exige que a FK aponte para um valor existente.
5. **B** — Normalização reduz a redundância de dados.
6. **B** — Mais normalização → mais junções para reunir os dados.
7. **C** — DDL (Data Definition Language) define a estrutura.
8. **B** — `SELECT` é DML (consulta/manipulação de dados).
9. **B** — `INSERT` adiciona novas linhas.
10. **C** — Sem `WHERE`, o `DELETE` remove todas as linhas.
11. **C** — T-SQL é o dialeto do SQL Server e do Azure SQL.
12. **B** — View é uma consulta salva; não armazena dados.
13. **C** — Stored procedure é um bloco de código SQL reutilizável.
14. **B** — O índice acelera a busca de linhas.
15. **B** — Só pode haver um índice clustered por tabela.
16. **C** — SQL Server em VM é IaaS; os demais são PaaS.
17. **B** — Managed Instance oferece alta compatibilidade para migração.
18. **B** — Pool elástico compartilha recursos entre vários bancos.
19. **B** — Azure Database for PostgreSQL é serviço para banco open-source.
20. **B** — Em PaaS, o Azure cuida de patches e backups.
