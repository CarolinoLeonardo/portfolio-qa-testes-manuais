# CT-LOG-005 — Tentativa de acesso sem preencher campos obrigatórios deve exibir a mensagem "Usuário e senha precisam ser preenchidos".

## Informações gerais

| Campo | Valor |
|---|---|
| Módulo | Login de usuário |
| Tipo | Funcional |
| Ambiente | Ambiente público de demonstração do Bugbank |
| Data | 30/07/2026 |
| Executor | Leonardo Carolino |
| Requisito Relacionado | REQ-LOG-003 |
| Status geral | Reprovado |

## Pré-requisitos

- Navegador com acesso à internet
- Aplicação Bugbank disponível

## Massa de teste

| Campo | Valor |
|---|---|
| E-mail | Não preencher |
| Senha | Não preencher |

## Passos e resultados

| Nº | Ação | Resultado esperado | Resultado obtido | Status |
|---:|---|---|---|---|
| 1 | Acessar `https://bugbank.netlify.app/` | A página inicial deve ser exibida sem erros aparentes. | A página inicial foi exibida sem erros aparentes. | Aprovado |
| 2 | Não preencher os campos obrigatórios | Os campos obrigatórios devem permanecer vazios, sem mensagens de validação | Os campos obrigatórios permaneceram vazios, sem mensagens de validação | Aprovado |
| 3 | Clicar na opção "Acessar" | O sistema deve exibir a mensagem "Usuário e senha precisam ser preenchidos", o login não dever ser efetuado e o usuário deve permanecer na tela de acesso | O sistema não exibiu a mensagem "Usuário e senha precisam ser preenchidos", o login não foi efetuado e o usuário permaneceu na tela de acesso | Reprovado |
