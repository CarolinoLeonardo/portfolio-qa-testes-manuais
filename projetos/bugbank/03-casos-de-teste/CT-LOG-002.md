# CT-LOG-002 — Impedir login com o campo de e-mail vazio

## Informações gerais

| Campo | Valor |
|---|---|
| Módulo | Login de usuário |
| Tipo | Funcional |
| Ambiente | Ambiente público de demonstração do BugBank |
| Data | 27/07/2026 |
| Executor | Leonardo Carolino |
| Requisito relacionado | REQ-LOG-001 |
| Status geral | Aprovado |

## Pré-requisitos

- Navegador com acesso à internet.
- Aplicação disponível.
- Conta de teste válida e ativa no sistema.
- Senha de teste válida e ativa no sistema.

## Massa de teste

| Campo | Valor |
|---|---|
| E-mail | leonardo_qa@tempmail.com — não preencher |
| Senha | 102030 |

## Passos e resultados

| Nº | Ação | Resultado esperado | Resultado obtido | Status |
|---:|---|---|---|---|
| 1 | Acessar `https://bugbank.netlify.app/`. | A página inicial deve ser exibida sem erros aparentes. | A página inicial foi carregada sem mensagens de erro aparentes. | Aprovado |
| 2 | Preencher o campo Senha com o valor da massa de teste. | O campo Senha deve permanecer preenchido, com o valor mascarado, e não deve apresentar mensagens de validação. | O campo Senha permaneceu preenchido, com o valor mascarado, e não apresentou mensagens de validação. | Aprovado |
| 3 | Não preencher o campo E-mail. | O campo E-mail deve permanecer vazio. | O campo E-mail permaneceu vazio. | Aprovado |
| 4 | Clicar em “Acessar”. | O sistema deve exibir a mensagem “É campo obrigatório” abaixo do campo E-mail e não deve efetuar o login. | O sistema exibiu a mensagem “É campo obrigatório” abaixo do campo E-mail e permaneceu na tela de login. | Aprovado |
