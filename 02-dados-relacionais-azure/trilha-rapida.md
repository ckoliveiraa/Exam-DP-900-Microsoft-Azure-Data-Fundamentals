# Trilha Rápida — Módulo 2 (Dados Relacionais no Azure)

> Revisão de véspera, focada em **responder questões**. Leia os gatilhos, os fatos e as pegadinhas.

---

## 🎯 Gatilhos de questão

| Se a questão menciona... | A resposta gira em torno de... |
|--------------------------|--------------------------------|
| Identifica unicamente cada linha | **Chave primária** |
| Referencia outra tabela | **Chave estrangeira** |
| Reduzir redundância de dados | **Normalização** |
| Definir estrutura (`CREATE`, `ALTER`, `DROP`) | **DDL** |
| Manipular dados (`SELECT`, `INSERT`, `UPDATE`, `DELETE`) | **DML** |
| Conceder/remover permissões (`GRANT`, `REVOKE`) | **DCL** |
| Consulta salva que não armazena dados | **View** |
| Bloco de código SQL reutilizável com parâmetros | **Stored procedure** |
| Acelerar a busca de linhas | **Índice** |
| Controle total do SO e da instância (IaaS) | **SQL Server em VM** |
| Migrar SQL Server local com pouca alteração | **SQL Managed Instance** |
| App novo, nuvem, mínima administração (PaaS) | **Azure SQL Database** |
| Banco gerenciado MySQL/PostgreSQL | **Azure Database for...** |

---

## 📌 Fatos que mais caem

- **3 serviços Azure SQL:** SQL Database (PaaS), Managed Instance (PaaS), SQL Server em VM (IaaS).
- **T-SQL** é o dialeto do SQL Server e do Azure SQL.
- **Mais PaaS** = menos administração; **mais IaaS** = mais controle.
- Em **PaaS**, o Azure cuida de patches, backups, HA e segurança.
- Só pode haver **um índice clustered** por tabela.
- **Pool elástico** = vários bancos compartilham recursos.

---

## ⚠️ Pegadinhas

- `UPDATE`/`DELETE` **sem `WHERE`** afetam **todas** as linhas.
- View **não** armazena dados — é só uma consulta salva.
- Para **migração**, a resposta quase sempre é **Managed Instance**, não SQL Database.
- **MariaDB** está em descontinuação — prefira PostgreSQL/MySQL.

---

[← Voltar ao módulo](./README.md)
