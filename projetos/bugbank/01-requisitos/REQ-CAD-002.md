# REQ-CAD-002 — Cadastro de novo usuário

## Descrição

O sistema deve permitir a criação de uma nova conta quando o usuário preencher todos os campos obrigatórios com dados válidos e utilizar um endereço de e-mail que ainda não esteja cadastrado.

## Critérios de aceite

- Todos os campos obrigatórios devem ser preenchidos.
- Os dados informados devem atender às regras de validação de cada campo.
- O endereço de e-mail informado não pode estar associado a outra conta.
- Quando todas as informações forem válidas, o sistema deve criar a conta.
- Após a criação da conta, o sistema deve informar ao usuário que o cadastro foi realizado com sucesso.

## Exemplos

- **Válido:** preencher todos os campos obrigatórios com dados válidos e utilizar um endereço de e-mail ainda não cadastrado.
- **Inválido:** preencher o formulário utilizando um endereço de e-mail já cadastrado no sistema.

## Dúvidas para refinamento

1. Quais são os campos obrigatórios para a criação da conta?
2. Quais são as regras de validação aplicáveis a cada campo?
3. Qual mensagem deve ser exibida quando o e-mail informado já estiver cadastrado?
4. Qual mensagem de sucesso deve ser apresentada após a criação da conta?
5. Após a criação da conta, o usuário deve ser autenticado automaticamente ou direcionado para a tela de login?
