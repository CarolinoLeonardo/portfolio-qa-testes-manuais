# REQ-CAD-003 — Os campos Nome, Email, Senha e Confirmação de senha são de preenchimento obrigatório

## Descrição

O sistema deve exigir o preenchimento dos campos "Nome", "E-mail", "Senha" e "Confirmação de senha" para concluir o cadastro de um novo usuário.

## Critérios de aceite

- Os campos "Nome", "E-mail", "Senha" e "Confirmação de senha" devem ser de preenchimento obrigatório.
- O sistema não deve concluir o cadastro quando um ou mais campos obrigatórios estiverem vazios.

## Exemplos

- Válido: Usuário não preenche um ou mais campos obrigatórios e o sistema não conclui o cadastro de uma nova conta.
- Inválido: Usuário não preenche um ou mais campos obrigatórios e o sistema conclui o cadastro de uma nova conta.

## Dúvidas para refinamento

1. Há indicação visual que Nome, Email, Senha e Confirmação de senha são campos obrigatórios?
