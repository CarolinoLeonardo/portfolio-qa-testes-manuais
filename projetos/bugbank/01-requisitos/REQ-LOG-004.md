# REQ-LOG-004 — Não deve autorizar o acesso para usuários inválidos ou não cadastrados.

## Descrição

O sistema deve validar se o usuário informado está cadastrado e impedir o acesso quando ele for inválido ou inexistente.

## Critérios de aceite

- O sistema deve verificar se o usuário informado está cadastrado.
- O sistema não autorizar o acesso quando o usuário (e-mail) informado não estiver cadastrado.
- O sistema não autorizar o acesso quando o usuário (e-mail) informado for inválido.
- O usuário deve permanecer na tela de login após a tentativa de acesso não autorizada.

## Exemplos

- Válido: O sistema não deve autorizar o acesso quando o usuário (e-mail) informado não estiver cadastrado ou inválido
- Inválido: O sistema permite que um usuário não cadastrado acesse uma área restrita da aplicação.

## Dúvidas para refinamento

1. O sistema apresenta alguma mensagem de validação?
