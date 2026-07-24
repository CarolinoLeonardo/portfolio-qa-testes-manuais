# CT-CAD-001 — Impedir cadastro com senha sequencial de seis dígitos

## Informações gerais

| Campo | Valor |
|---|---|
| Módulo | Cadastro de usuário |
| Tipo | Teste funcional negativo |
| Ambiente | Ambiente público de demonstração do BugBank |
| Navegador | Google Chrome 150.0.7871.130 — 64 bits |
| Data de execução | 22/07/2026 |
| Executor | Leonardo Carolino |
| Requisito relacionado | [REQ-CAD-001](../01-requisitos/REQ-CAD-001.md) |
| Cenário relacionado | [CET-CAD-001](../02-cenarios-de-teste/CET-CAD-001.md) |
| Status geral | **Reprovado** |

## Pré-requisitos

- Navegador com acesso à internet.
- Aplicação disponível.
- Usuário na página inicial do BugBank.
- E-mail de teste ainda não cadastrado.

## Massa de teste

| Campo | Valor |
|---|---|
| E-mail | `qa.leonardo+ct001@example.com` |
| Nome | `Leonardo QA` |
| Senha | `123456` |
| Confirmação de senha | `123456` |

## Passos e resultados

| Nº | Ação | Resultado esperado | Resultado obtido | Status |
|---:|---|---|---|---|
| 1 | Acessar `https://bugbank.netlify.app/` | A página inicial deve ser exibida sem erros aparentes. | Página exibida. | Aprovado |
| 2 | Clicar em **Registrar**. | O formulário de cadastro deve ser exibido. | Formulário exibido. | Aprovado |
| 3 | Preencher e-mail e nome com os dados da massa de teste. | Os campos devem aceitar os dados válidos. | Dados aceitos. | Aprovado |
| 4 | Preencher senha e confirmação com `123456`. | Os campos devem aceitar a digitação. | Dados aceitos. | Aprovado |
| 5 | Clicar em **Cadastrar**. | A conta não deve ser criada e uma validação da política de senha deve ser apresentada. | A conta foi criada com a senha `123456`. | **Reprovado** |

## Defeito relacionado

[BUG-CAD-001](../04-bug-reports/BUG-CAD-001.md)
