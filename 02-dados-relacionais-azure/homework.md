# Homework — Módulo 2 (Dados Relacionais no Azure)

> 🎯 **Objetivo:** consolidar o módulo 2 com **desafios abertos**. Aqui **você decide como resolver** e precisa **justificar** suas escolhas com base nas aulas do módulo.
>
> ⏱️ **Tempo estimado:** 2 a 3 horas.
>
> 💸 **Custo estimado:** US$ 0 — use a conta gratuita do Azure.
>
> 📌 **Pré-requisito:** ter estudado as aulas [2.1 a 2.6](./README.md).

---

## Desafio 1 — Modele um banco normalizado

Escolha um cenário simples (uma biblioteca, uma loja, uma escola). Projete **três tabelas** relacionadas:

- Defina as colunas de cada tabela e seus tipos de dados.
- Indique a **chave primária** de cada tabela.
- Mostre onde estão as **chaves estrangeiras** que ligam as tabelas.
- Explique como seu modelo evita redundância.

> **Entrega:** o desenho das 3 tabelas com chaves identificadas.

---

## Desafio 2 — Escreva os comandos SQL

Para o banco do Desafio 1, escreva (apenas o texto SQL, sem executar):

- Um comando **DDL** que cria uma das tabelas.
- Um `INSERT`, um `UPDATE` e um `DELETE` para essa tabela.
- Um `SELECT` com cláusula `WHERE`.

> **Entrega:** o conjunto de comandos. Critério: uso correto de cada comando e do `WHERE`.

---

## Desafio 3 — View ou stored procedure?

Para dois cenários a seguir, decida qual objeto usar e justifique:

1. Expor a relatórios apenas o nome e a cidade dos clientes, escondendo dados sensíveis.
2. Encapsular a lógica de "registrar um novo pedido e atualizar o estoque".

> **Entrega:** sua decisão para cada cenário, com justificativa.

---

## Desafio 4 — Escolha o serviço Azure SQL

Para cada situação, indique o serviço da família Azure SQL mais adequado e explique:

1. Uma startup vai criar um app novo na nuvem e quer o mínimo de administração.
2. Uma empresa precisa migrar um SQL Server local que usa SQL Agent e consultas entre bancos.
3. Um sistema legado exige acesso ao sistema operacional do servidor.

> **Entrega:** os três serviços escolhidos, com justificativa baseada em IaaS × PaaS.

---

## Desafio 5 — Relacional ou não relacional?

Reveja o Módulo 1. Descreva **um caso** em que um banco **relacional** é a melhor escolha e **um caso** em que um banco **não relacional** seria melhor. Justifique cada decisão considerando esquema, integridade e escala.

> **Entrega:** dois parágrafos curtos comparando as escolhas.

---

## Autoavaliação

- [ ] Concluí os 5 desafios
- [ ] Consigo justificar cada decisão com base nos conceitos do módulo
- [ ] Revisei os pontos em que tive dúvida nas aulas correspondentes
