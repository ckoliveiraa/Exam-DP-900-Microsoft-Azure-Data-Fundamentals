# Flashcards — Módulo 3 (Dados Não Relacionais no Azure)

> Formato: **Pergunta** → clique/revele a **Resposta**.

---

**1. Quais são os quatro serviços de uma conta de armazenamento do Azure?**
<details><summary>Ver resposta</summary>
Blob Storage, Azure Files, Table Storage e Queue Storage.
</details>

---

**2. Os dados no Armazenamento do Azure são criptografados?**
<details><summary>Ver resposta</summary>
Sim — há **criptografia automática dos dados em repouso**, além de replicação automática.
</details>

---

**3. Qual a diferença entre LRS e GRS?**
<details><summary>Ver resposta</summary>
**LRS** replica 3 cópias dentro de um único datacenter. **GRS** acrescenta uma cópia em uma **região secundária** geograficamente distante.
</details>

---

**4. O que o Azure Blob Storage armazena?**
<details><summary>Ver resposta</summary>
Dados **não estruturados** como objetos (blobs): imagens, vídeos, documentos, backups, logs.
</details>

---

**5. Qual a hierarquia de armazenamento do Blob Storage?**
<details><summary>Ver resposta</summary>
Conta de armazenamento → **contêiner** → **blob**.
</details>

---

**6. Quais são os três tipos de blob?**
<details><summary>Ver resposta</summary>
**Block blob** (arquivos comuns), **append blob** (logs/acréscimos) e **page blob** (acesso aleatório; discos de VM).
</details>

---

**7. Quais são as camadas de acesso do Blob Storage?**
<details><summary>Ver resposta</summary>
**Hot**, **Cool**, **Cold** e **Archive** — do mais frequente/mais caro para guardar ao menos frequente/mais barato.
</details>

---

**8. O que é especial na camada Archive?**
<details><summary>Ver resposta</summary>
É a mais barata para armazenar, mas fica **offline** — exige **reidratação** (para Hot ou Cool) antes de ler os dados.
</details>

---

**9. O que é o Azure Data Lake Storage Gen2?**
<details><summary>Ver resposta</summary>
O Blob Storage com **namespace hierárquico** (pastas reais), otimizado para cargas analíticas de big data.
</details>

---

**10. O que é o Azure Files?**
<details><summary>Ver resposta</summary>
Serviço de **compartilhamento de arquivos** na nuvem, acessível por vários computadores via protocolos SMB e NFS.
</details>

---

**11. Quais protocolos o Azure Files usa?**
<details><summary>Ver resposta</summary>
**SMB** e **NFS** — pode ser montado como unidade de rede em Windows, Linux e macOS.
</details>

---

**12. O que é o Azure Table Storage?**
<details><summary>Ver resposta</summary>
Um banco NoSQL de **chave-valor** para grandes volumes de dados sem esquema fixo; sem junções nem relacionamentos.
</details>

---

**13. Como uma entidade é identificada no Table Storage?**
<details><summary>Ver resposta</summary>
Pela combinação de **Partition Key** (agrupa entidades) e **Row Key** (identifica a entidade na partição).
</details>

---

**14. O que é o Azure Cosmos DB?**
<details><summary>Ver resposta</summary>
Banco NoSQL **distribuído globalmente**, totalmente gerenciado, de **baixa latência** e escala elástica.
</details>

---

**15. Como o desempenho do Cosmos DB é medido?**
<details><summary>Ver resposta</summary>
Em **Request Units (RUs)** — unidade que representa o custo de processar uma operação.
</details>

---

**16. Cite três casos de uso típicos do Cosmos DB.**
<details><summary>Ver resposta</summary>
IoT/telemetria, varejo e e-commerce global, aplicações web/mobile e jogos.
</details>

---

**17. Quais são as cinco APIs do Cosmos DB?**
<details><summary>Ver resposta</summary>
API for NoSQL, MongoDB, Apache Cassandra, Apache Gremlin e Table.
</details>

---

**18. Qual API do Cosmos DB é recomendada para projetos novos?**
<details><summary>Ver resposta</summary>
A **API for NoSQL** — é a API nativa do Cosmos DB.
</details>

---

**19. Qual API do Cosmos DB é usada para dados de grafo?**
<details><summary>Ver resposta</summary>
A **API for Apache Gremlin** — para dados altamente conectados (nós e arestas).
</details>

---

**20. Por que existem APIs como MongoDB e Cassandra no Cosmos DB?**
<details><summary>Ver resposta</summary>
Para **compatibilidade/migração** — permitem que apps já escritos para esses bancos usem o Cosmos DB com pouca ou nenhuma alteração.
</details>

---
