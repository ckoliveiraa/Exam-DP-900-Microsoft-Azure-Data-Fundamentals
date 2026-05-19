# Flashcards — Módulo 4 (Cargas de Trabalho de Análise no Azure)

> Formato: **Pergunta** → clique/revele a **Resposta**.

---

**1. Quais são as etapas do fluxo de análise em larga escala?**
<details><summary>Ver resposta</summary>
Ingestão → processamento/transformação → armazenamento analítico → modelagem → visualização.
</details>

---

**2. O que é a etapa de ingestão de dados?**
<details><summary>Ver resposta</summary>
A captura dos dados das fontes (bancos, arquivos, dispositivos, APIs) para a plataforma de análise. Pode ser em lote ou em fluxo.
</details>

---

**3. Qual a diferença entre ETL e ELT?**
<details><summary>Ver resposta</summary>
**ETL** transforma os dados **antes** de carregá-los (destino: data warehouse). **ELT** carrega os dados brutos e transforma **depois** (destino: data lake/lakehouse).
</details>

---

**4. O que é um pipeline de dados?**
<details><summary>Ver resposta</summary>
Uma sequência automatizada de atividades que move e transforma dados de ponta a ponta, de forma agendada ou disparada por eventos.
</details>

---

**5. O que é um data warehouse?**
<details><summary>Ver resposta</summary>
Repositório de dados **estruturados**, já transformados e modelados, otimizado para consultas analíticas (BI). Usa *schema-on-write*.
</details>

---

**6. O que é um data lake?**
<details><summary>Ver resposta</summary>
Repositório que armazena grandes volumes de dados **brutos** de qualquer tipo, sem transformação prévia. Usa *schema-on-read*.
</details>

---

**7. O que é um data lakehouse?**
<details><summary>Ver resposta</summary>
Modelo híbrido que combina a flexibilidade e o baixo custo de um data lake com a estrutura e o desempenho de um data warehouse.
</details>

---

**8. Qual é o papel do Azure Data Factory?**
<details><summary>Ver resposta</summary>
Serviço de **integração de dados** baseado em pipelines — faz ingestão e transformação (ETL/ELT). Não armazena nem analisa os dados.
</details>

---

**9. O que é o Azure Synapse Analytics?**
<details><summary>Ver resposta</summary>
Plataforma de análise **unificada** que combina data warehouse SQL, Apache Spark e pipelines de dados.
</details>

---

**10. Em que o Azure Databricks é baseado?**
<details><summary>Ver resposta</summary>
No **Apache Spark**. É forte em engenharia de dados, machine learning e adota a arquitetura lakehouse.
</details>

---

**11. O que é o Microsoft Fabric?**
<details><summary>Ver resposta</summary>
Plataforma de análise **SaaS tudo-em-um** que unifica ingestão, data lake, warehouse, ciência de dados, tempo real e Power BI. Usa o data lake **OneLake**.
</details>

---

**12. Como se chama o data lake central do Microsoft Fabric?**
<details><summary>Ver resposta</summary>
**OneLake**.
</details>

---

**13. O que é processamento em lote (batch)?**
<details><summary>Ver resposta</summary>
Dados coletados ao longo do tempo e processados em grupos, em intervalos definidos. Latência alta.
</details>

---

**14. O que é processamento em fluxo (streaming)?**
<details><summary>Ver resposta</summary>
Dados processados continuamente, assim que chegam, com latência baixa (quase em tempo real).
</details>

---

**15. Qual serviço do Azure é dedicado à análise de fluxos em tempo real?**
<details><summary>Ver resposta</summary>
**Azure Stream Analytics**.
</details>

---

**16. Quais são os três componentes do Power BI?**
<details><summary>Ver resposta</summary>
**Power BI Desktop** (criar), **Serviço do Power BI** (publicar/compartilhar) e **Power BI Mobile** (consumir).
</details>

---

**17. Onde se cria um relatório no Power BI?**
<details><summary>Ver resposta</summary>
No **Power BI Desktop** (ou no Serviço do Power BI). Depois ele é publicado no Serviço.
</details>

---

**18. Qual a diferença entre relatório e painel (dashboard) no Power BI?**
<details><summary>Ver resposta</summary>
**Relatório** pode ter várias páginas e vem de um conjunto de dados. **Painel** tem uma única página e pode reunir visuais de vários relatórios.
</details>

---

**19. Qual visualização é melhor para mostrar uma tendência ao longo do tempo?**
<details><summary>Ver resposta</summary>
Gráfico de **linhas**.
</details>

---

**20. Qual linguagem é usada para criar medidas e colunas calculadas no Power BI?**
<details><summary>Ver resposta</summary>
**DAX** (*Data Analysis Expressions*).
</details>

---
