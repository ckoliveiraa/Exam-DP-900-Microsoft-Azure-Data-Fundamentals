# Flashcards — Módulo 1 (Conceitos Centrais de Dados)

> Formato: **Pergunta** → clique/revele a **Resposta**.

---

**1. Quais são os três tipos de dados quanto à estrutura?**
<details><summary>Ver resposta</summary>
Estruturado, semiestruturado e não estruturado.
</details>

---

**2. O que caracteriza dados estruturados?**
<details><summary>Ver resposta</summary>
Seguem um **esquema fixo** — tabelas com linhas, colunas e tipos definidos. Esquema aplicado na gravação (*schema-on-write*) e consultados com SQL.
</details>

---

**3. O que são dados semiestruturados?**
<details><summary>Ver resposta</summary>
Têm estrutura **flexível e autodescrita** — cada registro pode ter campos diferentes. Exemplos: JSON, XML, YAML.
</details>

---

**4. Dê exemplos de dados não estruturados.**
<details><summary>Ver resposta</summary>
Imagens, vídeos, áudio, PDFs, documentos do Office, e-mails. Não se organizam em campos; guardados como arquivos/blobs.
</details>

---

**5. Diferença entre *schema-on-write* e *schema-on-read*?**
<details><summary>Ver resposta</summary>
- **Schema-on-write**: o esquema é aplicado na **gravação** (dado inválido é rejeitado) — bancos relacionais.
- **Schema-on-read**: o esquema é aplicado na **leitura** — data lakes e arquivos não estruturados.
</details>

---

**6. CSV é um formato orientado a quê e para qual uso?**
<details><summary>Ver resposta</summary>
Texto **delimitado** (campos separados por vírgula). Simples, universal, para dados tabulares — não guarda tipos nem hierarquia.
</details>

---

**7. Qual a diferença entre formatos orientados a linha e a coluna?**
<details><summary>Ver resposta</summary>
- **Linha** (Avro): grava o registro inteiro de uma vez — bom para **escrita**.
- **Coluna** (Parquet, ORC): agrupa valores da mesma coluna — bom para **leitura analítica** e comprime melhor.
</details>

---

**8. Avro, Parquet e ORC — qual é de linha e quais são de coluna?**
<details><summary>Ver resposta</summary>
**Avro** = linha. **Parquet** e **ORC** = coluna.
</details>

---

**9. Quais são as três grandes opções de armazenamento de dados?**
<details><summary>Ver resposta</summary>
Bancos relacionais, bancos não relacionais (NoSQL) e armazenamento de arquivos.
</details>

---

**10. Quais são os quatro tipos de bancos NoSQL?**
<details><summary>Ver resposta</summary>
Documento, chave-valor, família de colunas e grafo.
</details>

---

**11. Qual tipo de banco NoSQL é ideal para dados muito conectados (redes sociais, recomendações)?**
<details><summary>Ver resposta</summary>
Banco de **grafo** (nós e arestas). No Azure: Cosmos DB com API for Apache Gremlin.
</details>

---

**12. O que é uma carga de trabalho OLTP?**
<details><summary>Ver resposta</summary>
*Online Transaction Processing* — muitas transações **pequenas, rápidas e frequentes** que registram operações do dia a dia. Baixa latência, alta concorrência.
</details>

---

**13. O que significa a sigla ACID?**
<details><summary>Ver resposta</summary>
**A**tomicidade, **C**onsistência, **I**solamento e **D**urabilidade — propriedades que garantem transações confiáveis.
</details>

---

**14. O que é atomicidade?**
<details><summary>Ver resposta</summary>
A transação ocorre **por inteiro ou não ocorre** — não há estado parcial.
</details>

---

**15. O que é durabilidade?**
<details><summary>Ver resposta</summary>
Uma transação **confirmada persiste**, mesmo após falha do sistema (queda de energia, reinício).
</details>

---

**16. O que é uma carga de trabalho OLAP?**
<details><summary>Ver resposta</summary>
*Online Analytical Processing* — consultas complexas sobre **grandes volumes de dados históricos**, focadas em agregações e tendências para apoiar decisões.
</details>

---

**17. Cite três diferenças entre OLTP e OLAP.**
<details><summary>Ver resposta</summary>
OLTP: transações pequenas, dados atuais, normalizados, otimizado para escrita. OLAP: consultas complexas, dados históricos, desnormalizados, otimizado para leitura/agregação.
</details>

---

**18. O que é ETL? E ELT?**
<details><summary>Ver resposta</summary>
- **ETL**: Extrair → **Transformar** → Carregar (transforma antes de gravar).
- **ELT**: Extrair → Carregar → **Transformar** (grava bruto e transforma depois).
</details>

---

**19. Quais são as três funções de dados cobradas no exame?**
<details><summary>Ver resposta</summary>
Administrador de banco de dados (DBA), engenheiro de dados e analista de dados.
</details>

---

**20. Quem é responsável por criar pipelines de dados? E quem cria relatórios no Power BI?**
<details><summary>Ver resposta</summary>
Pipelines de dados → **engenheiro de dados**. Relatórios/visualizações no Power BI → **analista de dados**.
</details>

---
