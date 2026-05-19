# Flashcards — Módulo 2 (Dados Relacionais no Azure)

> Formato: **Pergunta** → clique/revele a **Resposta**.

---

**1. No modelo relacional, o que são linhas e colunas de uma tabela?**
<details><summary>Ver resposta</summary>
**Linha** = registro/instância de uma entidade. **Coluna** = atributo/campo, com um tipo de dado definido.
</details>

---

**2. O que é uma chave primária?**
<details><summary>Ver resposta</summary>
Coluna (ou conjunto) que **identifica unicamente** cada linha de uma tabela. Não pode repetir nem ser nula.
</details>

---

**3. O que é uma chave estrangeira?**
<details><summary>Ver resposta</summary>
Coluna que **referencia a chave primária de outra tabela**, criando o relacionamento entre tabelas.
</details>

---

**4. O que é integridade referencial?**
<details><summary>Ver resposta</summary>
Garante que uma chave estrangeira só aponte para um valor que **realmente existe** na tabela referenciada.
</details>

---

**5. O que é normalização?**
<details><summary>Ver resposta</summary>
Processo de organizar as tabelas para **reduzir a redundância** de dados e **evitar anomalias** de atualização.
</details>

---

**6. Qual a principal desvantagem de um banco muito normalizado na hora da leitura?**
<details><summary>Ver resposta</summary>
Exige mais **junções (joins)** entre tabelas para reunir os dados.
</details>

---

**7. O que significam as siglas DDL, DML e DCL?**
<details><summary>Ver resposta</summary>
**DDL** define estrutura (`CREATE`, `ALTER`, `DROP`); **DML** manipula dados (`SELECT`, `INSERT`, `UPDATE`, `DELETE`); **DCL** controla permissões (`GRANT`, `REVOKE`, `DENY`).
</details>

---

**8. Qual comando SQL adiciona novas linhas a uma tabela?**
<details><summary>Ver resposta</summary>
`INSERT`.
</details>

---

**9. O que acontece com um `UPDATE` ou `DELETE` sem cláusula `WHERE`?**
<details><summary>Ver resposta</summary>
A operação afeta **todas as linhas** da tabela.
</details>

---

**10. Qual é o dialeto SQL do SQL Server e do Azure SQL?**
<details><summary>Ver resposta</summary>
**T-SQL** (Transact-SQL).
</details>

---

**11. O que é uma view?**
<details><summary>Ver resposta</summary>
Uma **consulta salva** que age como tabela virtual. **Não armazena dados** — mostra o resultado de um `SELECT` sempre atualizado.
</details>

---

**12. O que é um stored procedure?**
<details><summary>Ver resposta</summary>
Um **bloco de código SQL** salvo no banco, executado sob demanda; pode receber parâmetros e conter lógica.
</details>

---

**13. Para que serve um índice? Qual é o custo?**
<details><summary>Ver resposta</summary>
Acelera a **busca** de linhas. Custo: ocupa espaço e torna a **escrita** um pouco mais lenta.
</details>

---

**14. Qual a diferença entre índice clustered e non-clustered?**
<details><summary>Ver resposta</summary>
**Clustered** define a ordem física das linhas — só **um** por tabela. **Non-clustered** é uma estrutura separada — pode haver **vários**.
</details>

---

**15. Quais são os três serviços da família Azure SQL?**
<details><summary>Ver resposta</summary>
Azure SQL Database, Azure SQL Managed Instance e SQL Server em VMs do Azure.
</details>

---

**16. Qual serviço da família Azure SQL é IaaS?**
<details><summary>Ver resposta</summary>
**SQL Server em VMs do Azure** — você controla o SO e a instância do SQL Server.
</details>

---

**17. Qual serviço é o mais indicado para migrar um banco SQL Server local com poucas mudanças?**
<details><summary>Ver resposta</summary>
**Azure SQL Managed Instance** — PaaS com alta compatibilidade com o SQL Server local.
</details>

---

**18. O que é um pool elástico no Azure SQL Database?**
<details><summary>Ver resposta</summary>
Recurso que permite que **vários bancos** compartilhem um conjunto de recursos, otimizando custo.
</details>

---

**19. Quais bancos open-source têm serviço gerenciado no Azure?**
<details><summary>Ver resposta</summary>
**MySQL**, **PostgreSQL** e **MariaDB** (este último em descontinuação).
</details>

---

**20. O que o Azure gerencia automaticamente nos serviços PaaS de banco de dados?**
<details><summary>Ver resposta</summary>
Provisionamento, patches, backups, alta disponibilidade, segurança e monitoramento.
</details>

---
