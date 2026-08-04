# CT-LOG-007 — Sistema deve direcionar usuários válidos e cadastrados para a home da conta após tentativa de login.

## Informações gerais

| Campo | Valor |
|---|---|
| Módulo | Login de usuário |
| Tipo | Funcional |
| Ambiente | Ambiente público de demonstração do Bugbank |
| Data | 04/08/2026 |
| Executor | Leonardo Carolino |
| Requisito Relacionado | REQ-LOG-005 |
| Status geral | Aprovado |

## Pré-requisitos

1. Navegador com acesso à internet
2. Aplicação Bugbank disponível
3. Conta de usuário criada e ativa no sistema

## Massa de teste

| Campo | Valor |
|---|---|
| e-mail | leonardo.qa@tempmail.com |
| senha | 102030 |

## Passos e resultados

| Nº | Ação | Resultado esperado | Resultado obtido | Status |
|---:|---|---|---|---|
| 1 | Acessar <https://bug-bank.netlify.app/> | A página deve ser carregada e exibida sem erros ou mensagem de validação aparente. | A página foi carregada e exibida sem erros ou mensagem de validação aparente. | Aprovado |
| 2 | Preencher o campo obrigatório "E-mail" com e-mail válido e cadastrado no sistema | O campo obrigatório "E-mail" deve permanecer preenchido com o valor informado pelo usuário, sem mensagens de validação aparente | O campo obrigatório "E-mail" permaneceu preenchido com o valor informado pelo usuário, sem mensagens de validação aparente | Aprovado |
| 3 | Preencher o campo obrigatório "Senha" com valor válido e cadastrado no sistema | O campo obrigatório "Senha" deve permanecer preenchido com o valor informado pelo usuário, com os dados mascarados, sem mensagens de validação aparente | O campo obrigatório "Senha" permaneceu preenchido com o valor informado pelo usuário, com os dados mascarados, sem mensagens de validação aparente | Aprovado |
| 4 | Clicar na opção "Acessar" | O sistema deve validar os dados de usuário informados, autorizar o acesso e direcionar o usuário para a página home de sua conta | O sistema validou os dados de usuário informados, autorizou o acesso e direcionou o usuário para a página home de sua conta | Aprovado |
