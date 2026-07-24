# Projeto de Testes Manuais — BugBank

## Objetivo

Praticar o processo de QA manual em uma aplicação web, desde a análise de requisitos até o registro de defeitos.

## Aplicação testada

- Aplicação: BugBank
- URL: https://bugbank.netlify.app/
- Plataforma: Web
- Responsável pelos testes: Leonardo Carolino
- Início do projeto: julho de 2026

## Escopo atual

Validação das regras de criação de senha durante o cadastro de uma nova conta.

## Artefatos

| ID | Artefato | Resultado |
|---|---|---|
| REQ-CAD-001 | [Requisito de senha sequencial](01-requisitos/REQ-CAD-001.md) | Analisado |
| CET-CAD-001 | [Cenário de teste](02-cenarios-de-teste/CET-CAD-001.md) | Executado |
| CT-CAD-001 | [Caso de teste](03-casos-de-teste/CT-CAD-001.md) | Reprovado |
| BUG-CAD-001 | [Bug report](04-bug-reports/BUG-CAD-001.md) | Aberto |

## Estrutura

```text
bugbank/
├── 01-requisitos/
├── 02-cenarios-de-teste/
├── 03-casos-de-teste/
├── 04-bug-reports/
├── 05-evidencias/
└── 06-anexos-originais/
```

## Observações

- Os dados de teste são sintéticos.
- A mensagem de validação exata deve ser confirmada com o responsável pelo requisito.
- O requisito ainda precisa esclarecer se sequências decrescentes e sequências inseridas em senhas maiores também devem ser bloqueadas.
