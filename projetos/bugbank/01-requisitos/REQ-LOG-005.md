# REQ-LOG-005 — Usuários válidos e cadastros são direcionados para a home da conta.

## Descrição

Após a validação das credenciais informadas, o sistema deve conceder acesso ao usuário e direcioná-lo para a página inicial da conta (Home).

## Critérios de aceite

- O sistema deve verificar se o e-mail do usuário informado está cadastrado.
- O sistema deve verificar se a senha informada está correta.
- O sistema autoriza o acesso à conta quando usuário e senha forem confirmados.
- O sistema direciona o usuário para a página inicial da conta (Home).
- A página Home deve ser carregada corretamente após o login.

## Exemplos

- Válido: Usuário cadastrado informa e-mail e senha válidos, o login é realizado e ele é direcionado para a página Home.
- Inválido: Usuário informa e-mail ou senha inválidos, o login não é realizado e ele permanece na página de acesso.

## Dúvidas para refinamento

- Nenhuma

