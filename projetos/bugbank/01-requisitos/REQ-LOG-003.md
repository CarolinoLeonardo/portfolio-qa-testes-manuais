# REQ-LOG-003 — Tentativa de acesso sem preencher campos obrigatórios deve exibir a mensagem "Usuário e senha precisam ser preenchidos".

## Descrição

Na tela de login, os campos obrigatórios devem ser preenchidos para prosseguir com o acesso à conta. Se for feita a tentativa de acesso sem preencher esses campos, o sistema deverá exibir a mensagem "Usuário e Senha precisam ser preenchidos."

## Critérios de aceite

- Tentar efetuar o login sem preencher os campos obrigatórios.
- O sistema não deve processar o login
- O sistema exibe a notificação "Usuário e senha precisam ser preenchidos"

## Exemplos

- Válido: Usuário tentou efetuar login sem preencher os campos obrigatórios, o sistema não efetuou o login e exibiu a notificação "Usuário e senha precisam ser preenchidos".
- Inválido: Usuário tentou efetuar login sem preencher os campos obrigatórios, o sistema não efetuou o login e não exibiu a notificação "Usuário e senha precisam ser preenchidos".

## Dúvidas para refinamento

1. Onde a mensagem deverá ser exibida?
