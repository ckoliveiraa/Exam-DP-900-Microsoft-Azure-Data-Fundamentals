# Homework — Módulo 2 (Dados Relacionais no Azure)

> 🎯 **Objetivo:** consolidar o módulo 2 com **prática guiada** e **desafios abertos**. Nos desafios, **você decide como resolver** e precisa **justificar** suas escolhas com base nas aulas.
>
> ⏱️ **Tempo estimado:** 2 a 3 horas.
>
> 💸 **Custo estimado:** US$ 0 — a prática roda no sandbox gratuito do Microsoft Learn.
>
> 📌 **Pré-requisito:** ter estudado as aulas 2.1 a 2.6.

---

## Parte 1 — Prática guiada (Microsoft Learn)

> Exercícios no **Microsoft Learn**, em ambiente sandbox — **sem conta Azure** e **sem custo**. Basta uma conta Microsoft gratuita para login.

### Prática 2.1 — Explorar conceitos de dados relacionais
1. Acesse o módulo [**Explorar conceitos fundamentais de dados relacionais**](https://learn.microsoft.com/pt-br/training/modules/explore-relational-data-offerings/).
2. Percorra todas as unidades e responda à **verificação de conhecimentos**.

### Prática 2.2 — Explorar serviços de banco de dados relacional no Azure
1. Acesse o módulo [**Explorar serviços de banco de dados relacional no Azure**](https://learn.microsoft.com/pt-br/training/modules/explore-provision-deploy-relational-database-offerings-azure/).
2. Percorra as unidades, incluindo a de **exercício** (sandbox / recurso de demonstração).

### Prática 2.3 — Avaliação de prática oficial (parcial)
1. Abra a [**avaliação de prática gratuita do DP-900**](https://learn.microsoft.com/pt-br/credentials/certifications/exams/dp-900/practice/assessment?assessment-type=practice&assessmentId=24).
2. Responda às questões de **dados relacionais no Azure** e revise as explicações dos erros.

> ✅ **Validação da Parte 1:** concluir os exercícios guiados e revisar as questões do Domínio 2.

---

## Parte 2 — Desafios

### Desafio 1 — Modele um banco normalizado

Escolha um cenário simples (uma biblioteca, uma loja, uma escola). Projete **três tabelas** relacionadas:

- Defina as colunas de cada tabela e seus tipos de dados.
- Indique a **chave primária** de cada tabela.
- Mostre onde estão as **chaves estrangeiras** que ligam as tabelas.
- Explique como seu modelo evita redundância.

> **Entrega:** o desenho das 3 tabelas com chaves identificadas.

---

### Desafio 2 — Escreva os comandos SQL

Para o banco do Desafio 1, escreva (apenas o texto SQL, sem executar):

- Um comando **DDL** que cria uma das tabelas.
- Um `INSERT`, um `UPDATE` e um `DELETE` para essa tabela.
- Um `SELECT` com cláusula `WHERE`.

> **Entrega:** o conjunto de comandos. Critério: uso correto de cada comando e do `WHERE`.

---

### Desafio 3 — View ou stored procedure?

Para dois cenários a seguir, decida qual objeto usar e justifique:

1. Expor a relatórios apenas o nome e a cidade dos clientes, escondendo dados sensíveis.
2. Encapsular a lógica de "registrar um novo pedido e atualizar o estoque".

> **Entrega:** sua decisão para cada cenário, com justificativa.

---

### Desafio 4 — Escolha o serviço Azure SQL

Para cada situação, indique o serviço da família Azure SQL mais adequado e explique:

1. Uma startup vai criar um app novo na nuvem e quer o mínimo de administração.
2. Uma empresa precisa migrar um SQL Server local que usa SQL Agent e consultas entre bancos.
3. Um sistema legado exige acesso ao sistema operacional do servidor.

> **Entrega:** os três serviços escolhidos, com justificativa baseada em IaaS × PaaS.

---

### Desafio 5 — Relacional ou não relacional?

Reveja o Módulo 1. Descreva **um caso** em que um banco **relacional** é a melhor escolha e **um caso** em que um banco **não relacional** seria melhor. Justifique cada decisão considerando esquema, integridade e escala.

> **Entrega:** dois parágrafos curtos comparando as escolhas.

---

## Autoavaliação

- [ ] Concluí a prática guiada (Parte 1)
- [ ] Concluí os 5 desafios (Parte 2)
- [ ] Consigo justificar cada decisão com base nos conceitos do módulo
- [ ] Revisei os pontos em que tive dúvida nas aulas correspondentes
