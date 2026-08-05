# REQ-LOG-001 — Obrigatoriedade dos campos de e-mail e senha para efetuar o Login

## Descrição

O sistema deve exigir o preenchimento dos campos de e-mail e senha para permitir uma tentativa de autenticação.

## Critérios de aceite

- O campo de e-mail deve ser obrigatório.
- O campo de senha deve ser obrigatório.
- O sistema não deve processar o login quando um dos campos obrigatórios estiver vazio.

## Exemplos

- **Válido:** Usuário não preenche um ou mais campos obrigatórios e o sistema não conclui o login.
- **Inválido:** Usuário não preenche um ou mais campos obrigatórios e o sistema conclui o login.

## Dúvidas para refinamento

1. O sistema deve considerar espaços em branco como campo não preenchido?
2. Os campos devem apresentar alguma indicação visual de obrigatoriedade?
3. A validação deve ocorrer ao sair do campo ou somente ao tentar realizar o login?
