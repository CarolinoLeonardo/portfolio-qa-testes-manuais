# CT-LOG-004 — Validar a indicação visual que os campos E-mail e Senha na tela de Login são obrigatórios.

## Informações gerais

| Campo | Valor |
|---|---|
| Módulo | Login de usuário |
| Tipo | Funcional |
| Ambiente | Ambiente público de demonstração do BugBank |
| Data | 27/07/2026 |
| Executor | Leonardo Carolino |
| Requisito relacionado | REQ-LOG-002 |
| Status geral | Reprovado |

## Pré-requisitos

- Navegador com acesso à internet.
- Aplicação BugBank disponível.

## Massa de teste

Não se aplica.

## Passos e resultados

| Nº | Ação | Resultado esperado | Resultado obtido | Status |
|---:|---|---|---|---|
| 1 | Acessar `https://bugbank.netlify.app/`. | A página inicial deve ser exibida sem erros aparentes. | A página inicial foi carregada sem mensagens de erro aparentes. | Aprovado |
| 2 | Observar o rótulo do campo “E-mail” na área de login. | Deve existir uma indicação visual de obrigatoriedade junto ao rótulo do campo “E-mail”, por meio de um asterisco vermelho (*). | Não foi apresentada nenhuma indicação visual de obrigatoriedade junto ao rótulo do campo “E-mail”. | Reprovado |
| 3 | Observar o rótulo do campo “Senha” na área de login. | Deve existir uma indicação visual de obrigatoriedade junto ao rótulo do campo “Senha”, por meio de um asterisco vermelho (*)”. | Não foi apresentada nenhuma indicação visual de obrigatoriedade junto ao rótulo do campo “Senha”. | Reprovado |
