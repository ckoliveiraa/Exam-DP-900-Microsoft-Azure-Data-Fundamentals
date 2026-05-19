# Homework — Módulo 3 (Dados Não Relacionais no Azure)

> 🎯 **Objetivo:** consolidar o módulo 3 com **prática guiada** e **desafios abertos**. Nos desafios, **você decide como resolver** e precisa **justificar** suas escolhas com base nas aulas.
>
> ⏱️ **Tempo estimado:** 2 a 3 horas.
>
> 💸 **Custo estimado:** US$ 0 — a prática roda no sandbox gratuito do Microsoft Learn.
>
> 📌 **Pré-requisito:** ter estudado as aulas 3.1 a 3.5.

---

## Parte 1 — Prática guiada (Microsoft Learn)

> Exercícios no **Microsoft Learn**, em ambiente sandbox — **sem conta Azure** e **sem custo**. Basta uma conta Microsoft gratuita para login.

### Prática 3.1 — Explorar os recursos do Armazenamento do Azure
1. Acesse o módulo [**Explorar o Armazenamento do Azure para dados não relacionais**](https://learn.microsoft.com/pt-br/training/modules/explore-provision-deploy-non-relational-data-services-azure/).
2. Percorra todas as unidades e responda à **verificação de conhecimentos**.

### Prática 3.2 — Explorar os recursos do Azure Cosmos DB
1. Acesse o módulo [**Explorar fundamentos do Azure Cosmos DB**](https://learn.microsoft.com/pt-br/training/modules/explore-non-relational-data-stores-azure/).
2. Percorra as unidades, incluindo a de **exercício** (sandbox / recurso de demonstração).

### Prática 3.3 — Avaliação de prática oficial (parcial)
1. Abra a [**avaliação de prática gratuita do DP-900**](https://learn.microsoft.com/pt-br/credentials/certifications/exams/dp-900/practice/assessment?assessment-type=practice&assessmentId=24).
2. Responda às questões de **dados não relacionais no Azure** e revise as explicações dos erros.

> ✅ **Validação da Parte 1:** concluir os exercícios guiados e revisar as questões do Domínio 3.

---

## Parte 2 — Desafios

### Desafio 1 — Escolha o serviço de armazenamento

Para cada necessidade, indique o serviço do Armazenamento do Azure mais adequado (Blob, Files ou Table) e justifique:

1. Hospedar imagens e vídeos exibidos no site da empresa.
2. Disponibilizar uma pasta de rede compartilhada entre várias máquinas.
3. Guardar perfis de usuário consultados rapidamente por chave, sem esquema fixo.

> **Entrega:** os três serviços escolhidos, com justificativa.

---

### Desafio 2 — Plano de camadas de acesso

Uma empresa gera arquivos de relatório todo mês. Eles são muito acessados nos primeiros 30 dias, raramente entre 30 e 180 dias, e depois quase nunca — mas precisam ser guardados por 7 anos.

- Defina em quais **camadas** (Hot, Cool, Cold, Archive) os arquivos devem estar ao longo do tempo.
- Explique como o **gerenciamento de ciclo de vida** automatizaria isso.

> **Entrega:** uma linha do tempo com as camadas e a regra de ciclo de vida proposta.

---

### Desafio 3 — Redundância adequada

Para cada cenário, escolha entre LRS, ZRS, GRS ou GZRS e justifique:

1. Dados de teste descartáveis, custo mínimo.
2. Dados críticos que precisam sobreviver à perda de uma região inteira.

> **Entrega:** as duas escolhas, com justificativa baseada em proteção × custo.

---

### Desafio 4 — Quando usar o Cosmos DB

Descreva uma aplicação fictícia que **justifique** o uso do Azure Cosmos DB.

- Explique por que ela precisa de distribuição global e baixa latência.
- Diga qual seria um caso em que o Cosmos DB **não** seria a melhor escolha e por quê.

> **Entrega:** um texto curto com os dois cenários.

---

### Desafio 5 — Escolha a API do Cosmos DB

Para cada situação, indique a API do Cosmos DB mais adequada e justifique:

1. Um projeto totalmente novo, sem dependência de outro banco.
2. A migração de um aplicativo existente que já usa MongoDB.
3. Uma rede social que precisa modelar relações entre usuários.

> **Entrega:** as três APIs escolhidas, com justificativa.

---

## Autoavaliação

- [ ] Concluí a prática guiada (Parte 1)
- [ ] Concluí os 5 desafios (Parte 2)
- [ ] Consigo justificar cada decisão com base nos conceitos do módulo
- [ ] Revisei os pontos em que tive dúvida nas aulas correspondentes
