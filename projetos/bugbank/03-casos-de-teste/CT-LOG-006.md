# CT-LOG-006 — Sistema não deve autorizar o acesso para usuários inválidos ou não cadastrados.

## Informações gerais

| Campo | Valor |
|---|---|
| Módulo | Login do usuário |
| Tipo | Funcional |
| Ambiente | Ambiente público de demonstração do Bugbank |
| Data | 01/08/2026 |
| Executor | Leonardo Carolino |
| Requisito Relacionado | REQ-LOG-004 |
| Status geral | Aprovado |

## Pré-requisitos

- Navegador com acesso à internet
- Aplicação Bugbank disponível
- E-mail de usuário não cadastrado/inválido

## Massa de teste

| Campo | Valor |
|---|---|
| E-mail | leonardo.tester@tempmail.com |
| Senha | 102030 |

## Passos e resultados

| Nº | Ação | Resultado esperado | Resultado obtido | Status |
|---:|---|---|---|---|
| 1 | Acessar `https://bugbank.netlify.app/` | A página deve ser carregada e exibida sem erros ou mensagem de validação aparente. | A página foi carregada e exibida sem erros ou mensagem de validação aparente. | Aprovado |
| 2 | Preencher o campo obrigatório "E-mail" com e-mail não cadastrado/inválido | O campo obrigatório "E-mail" deve permanecer preenchido com o valor informado pelo usuário, sem mensagens de validação aparente. | O campo obrigatório "E-mail" permaneceu preenchido com o valor informado pelo usuário, sem mensagens de validação aparente. | Aprovado |
| 3 | Preencher o campo obrigatório "Senha" com um valor de 6 números | O campo obrigatório "Senha" deve permanecer preenchido com o valor informado pelo usuário, com os dados mascarados, sem mensagens de validação aparente. | O campo obrigatório "Senha" permaneceu preenchido com o valor informado pelo usuário, com os dados mascarados, sem mensagens de validação aparente. | Aprovado |
| 4 | Clicar na opção "Acessar" | O Sistema não deve autorizar o acesso a uma área restrita da aplicação e deve permanecer na tela de login. | O Sistema não autorizou acesso a uma área restrita da aplicação, exibiu a mensagem de validação "Usuário ou senha inválido. Tente novamente ou verifique suas informações!" em uma janela Pop-up e permaneceu na tela de login. | Aprovado |
