# Homework — Módulo 1 (Conceitos Centrais de Dados)

> 🎯 **Objetivo:** consolidar o módulo 1 com **desafios abertos**. Aqui **você decide como resolver** e precisa **justificar** suas escolhas com base nas aulas do módulo.
>
> ⏱️ **Tempo estimado:** 2 a 3 horas.
>
> 💸 **Custo estimado:** US$ 0 — use a conta gratuita do Azure.
>
> 📌 **Pré-requisito:** ter estudado as aulas [1.1 a 1.6](./README.md).

---

## Desafio 1 — Classifique um cenário real

Escolha um sistema que você conhece (uma loja, um app, uma clínica). Liste **cinco tipos de dados** que ele gera e, para cada um:

- Classifique como estruturado, semiestruturado ou não estruturado.
- Indique o tipo de armazenamento mais adequado (relacional, NoSQL ou arquivos).
- Justifique a escolha.

> **Entrega:** uma tabela com as 5 linhas e suas justificativas.

---

## Desafio 2 — OLTP ou OLAP?

Para o mesmo sistema do Desafio 1, descreva **duas cargas de trabalho**: uma transacional (OLTP) e uma analítica (OLAP).

- Explique o que cada uma faz.
- Aponte como elas diferem em volume, frequência e tipo de operação.
- Diga qual delas se beneficiaria de um formato **colunar** (ex.: Parquet) e por quê.

> **Entrega:** um texto curto comparando as duas cargas.

---

## Desafio 3 — Escolha o formato de arquivo

Você precisa armazenar 10 milhões de registros de vendas que serão **consultados para relatórios** (somas por região e mês).

- Qual formato de arquivo você escolheria? Por quê?
- E se o objetivo fosse **ingerir** esses dados o mais rápido possível? Mudaria sua resposta?

> **Entrega:** sua decisão para os dois cenários, com justificativa baseada em linha × coluna.

---

## Desafio 4 — Monte uma "mini-arquitetura" no papel

Desenhe (papel, PowerPoint ou Draw.io) o caminho dos dados de uma empresa fictícia:

1. Onde os dados **nascem** (sistema OLTP).
2. Como eles são **movidos** (ETL ou ELT — escolha e justifique).
3. Onde são **analisados**.
4. Quem é o **responsável** por cada etapa (DBA, engenheiro, analista).

> **Entrega:** um diagrama simples com as 4 etapas e as funções envolvidas.

---

## Desafio 5 — Explique para um leigo

Escreva um parágrafo (máx. 150 palavras) explicando a diferença entre **OLTP e OLAP** para alguém sem conhecimento técnico, usando uma analogia do dia a dia.

> **Entrega:** o parágrafo. Critério: clareza, sem jargão desnecessário.

---

## Autoavaliação

- [ ] Concluí os 5 desafios
- [ ] Consigo justificar cada decisão com base nos conceitos do módulo
- [ ] Revisei os pontos em que tive dúvida nas aulas correspondentes
