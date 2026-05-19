# Laboratórios — Módulo 1 (Conceitos Centrais de Dados)

> Práticas **introdutórias** para fixar os conceitos do módulo e preparar a base para o [Homework](./homework.md). São rápidas e de baixo custo — use a [conta gratuita do Azure](https://azure.microsoft.com/pt-br/free/).
>
> 💸 **Custo:** US$ 0 — tudo cabe no nível gratuito.

---

## Lab 1.1 — Criar a conta gratuita e conhecer o portal

**Objetivo:** ter um ambiente Azure pronto para os próximos labs.

1. Acesse [azure.microsoft.com/pt-br/free](https://azure.microsoft.com/pt-br/free/) e crie a conta gratuita.
2. Faça login no [portal do Azure](https://portal.azure.com).
3. Localize a barra de busca, o menu de recursos e o **Cloud Shell**.

**Validação:** o portal abre e você consegue pesquisar serviços.

---

## Lab 1.2 — Classificar tipos de dados

**Objetivo:** treinar a distinção entre dados estruturados, semiestruturados e não estruturados.

1. Reúna três arquivos no seu computador: uma planilha (`.xlsx` ou `.csv`), um arquivo `.json` e uma imagem (`.jpg`/`.png`).
2. Para cada um, anote: qual tipo de dado é e por quê.
3. Confira com a aula [1.1](./1.1-como-representar-dados.md).

**Validação:** você classifica os três corretamente e justifica cada um.

---

## Lab 1.3 — Criar uma conta de armazenamento e enviar arquivos

**Objetivo:** ver na prática onde dados não estruturados são guardados.

1. No portal, crie um recurso **Conta de Armazenamento** (*Storage Account*).
2. Dentro dela, crie um **contêiner de Blob**.
3. Faça **upload** dos três arquivos do Lab 1.2.
4. Observe os **metadados** de cada blob (nome, tamanho, tipo, data).

**Validação:** os três arquivos aparecem listados no contêiner.

---

## Lab 1.4 — Comparar formatos de arquivo

**Objetivo:** perceber a diferença prática entre formatos de texto.

1. Crie um pequeno conjunto de dados (5 linhas) com nome, cidade e idade.
2. Salve-o em **CSV** e também em **JSON**.
3. Abra os dois em um editor de texto e compare: tamanho, legibilidade, hierarquia.

**Validação:** você sabe explicar quando preferir CSV e quando preferir JSON.

---

> ✅ Concluiu os labs? Avance para o [Homework](./homework.md), onde os desafios pedem que você **decida e justifique** soluções a partir desta base.
