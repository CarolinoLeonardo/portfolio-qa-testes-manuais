# CT-CAD-004 — Validar a obrigatoriedade do preenchimento do campo E-mail para criação de nova conta

## Informações gerais

| Campo | Valor |
|---|---|
| Módulo | Cadastro de nova conta |
| Tipo | Funcional |
| Ambiente | Ambiente público de demonstração do BugBank |
| Data | 05/08/2026 |
| Executor | Leonardo Carolino |
| Requisito Relacionado | REQ-CAD-003 |
| Status geral | Não executado |

## Pré-requisitos

1. Navegador com acesso à internet
2. Aplicação Bugbank disponível
3. Dados de massa de teste ainda não utilizados

## Massa de teste

| Campo | Valor |
|---|---|
| Nome | Leonardo |
| Email | (Não preencher) |
| Senha | 102030 |
| Confirmação de Senha | 102030 |

## Passos e resultados

| Nº | Ação | Resultado esperado | Resultado obtido | Status |
|---:|---|---|---|---|
| 1 | Acessar <https://bugbank.netlify.app/> | A página inicial deve ser exibida sem erros ou mensagem de validação aparente | A página inicial foi exibida sem erros ou mensagem de validação aparente | Aprovado |
| 3 | Clicar na opção "Registrar" | A aplicação deverá exibir o formulário de cadastro. | A aplicação exibiu o formulário de cadastro. | Aprovado |
| 4 | Não preencher o campo "E-mail" | O campo obrigatório "E-mail" deve permanecer vazio, sem mensagens de validação aparente. | O campo obrigatório "E-mail" permaneceu vazio, sem mensagens de validação aparente. | Aprovado |
| 5 | Preencher o campo "Nome" com os dados de massa de teste | O campo obrigatório "Nome" deve permanecer preenchido com o valor informado pelo usuário, sem mensagens de validação aparente. | O campo obrigatório "Nome" permaneceu preenchido com o valor informado pelo usuário, sem mensagens de validação aparente. | Aprovado |
| 6 | Preencher o campo "Senha" com os dados de massa de teste | O campo obrigatório "Senha" deve permanecer preenchido com o valor informado pelo usuário, com os dados mascarados, sem mensagens de validação aparente. | O campo obrigatório "Senha" permaneceu preenchido com o valor informado pelo usuário, com os dados mascarados, sem mensagens de validação aparente. | Aprovado |
| 7 | Preencher o campo "Confirmação de Senha" com os dados de massa de teste | O campo obrigatório "Confirmação de Senha" deve permanecer preenchido com o valor informado pelo usuário, com os dados mascarados, sem mensagens de validação aparente. | O campo obrigatório "Confirmação de Senha" permaneceu preenchido com o valor informado pelo usuário, com os dados mascarados, sem mensagens de validação aparente. | Aprovado |
| 8 | Clicar na opção "Cadastrar" | O sistema não conclui o cadastro e deve permanecer na tela de formulário de cadastro. | O sistema não concluiu o cadastro, exibiu a mensagem "É campo obrigatório" embaixo do input do E-mail e permaneceu na tela de formulário de cadastro. | Aprovado |
