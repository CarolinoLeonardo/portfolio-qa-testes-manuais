# CT-CAD-002 — Cadastrar um novo usuário no sistema

## Informações gerais

| Campo | Valor |
|---|---|
| Módulo | Cadastro de usuário |
| Tipo | Funcional |
| Ambiente | Ambiente público de demonstração do BugBank |
| Data | 25/07/2026 |
| Executor | Leonardo Carolino |
| Requisito relacionado | REQ-CAD-002 |
| Status geral | Aprovado |

## Pré-requisitos

- Navegador com acesso à internet.
- Aplicação disponível.
- E-mail de teste ainda não cadastrado.

## Massa de teste

| Campo | Valor |
|---|---|
| E-mail | leonardo_qa@tempmail.com |
| Nome | Leonardo QA |
| Senha | 10203 |
| Confirmação de senha | 10203 |

## Passos e resultados

| Nº | Ação | Resultado esperado | Resultado obtido | Status |
|---:|---|---|---|---|
| 1 | Acessar `https://bugbank.netlify.app/`. | A página inicial deve ser exibida sem erros aparentes. | A página inicial foi carregada sem mensagens de erro aparentes. | Aprovado |
| 2 | Clicar em **“Registrar”**. | O formulário de cadastro deve ser exibido com os campos E-mail, Nome, Senha e Confirmação de senha. | O formulário de cadastro foi exibido com todos os campos esperados. | Aprovado |
| 3 | Preencher os campos E-mail e Nome com os dados da massa de teste. | Os campos devem aceitar os dados válidos informados. | Os valores foram preenchidos nos dois campos. | Aprovado |
| 4 | Preencher os campos Senha e Confirmação de senha com os dados da massa de teste. | Os campos devem aceitar os valores informados e apresentá-los mascarados, sem mensagens de validação. | Os valores foram preenchidos nos dois campos e permaneceram mascarados, sem mensagens de validação. | Aprovado |
| 5 | Clicar em **“Cadastrar”**. | A conta deve ser criada e uma notificação de sucesso contendo o número da conta deve ser apresentada. | A conta foi criada e uma notificação de sucesso contendo o número da conta foi apresentada. | Aprovado |
