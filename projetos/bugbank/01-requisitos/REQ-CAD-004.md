# REQ-CAD-004 — Tentativa de cadastro sem preencher nome deve visualizar a mensagem "Nome não pode ser vazio"

## Descrição

REQ-CAD-004 — Tentativa de cadastro sem preencher nome deve visualizar a mensagem "Nome não pode ser vazio"

## Critérios de aceite

- Os campos obrigatórios (E-mail, Senha e Confirmação de Senha) devem ser preenchidos com dados válidos.
- O campo obrigatório Nome deve se manter vazio.
- O sistema deve identificar quando o campo "Nome" estiver vazio.
- A mensagem "Nome não pode ser vazio" deve ser apresentada após a tentativa de realizar o cadastro sem preencher o campo "Nome".
- O cadastro não deve ser concluído enquanto o campo "Nome" permanecer vazio.

## Exemplos

- Válido: A mensagem "Nome não pode ser vazio" deve ser apresentada após a tentativa de realizar o cadastro sem preencher o campo "Nome".
- Inválido: A mensagem "Nome não pode ser vazio" não é apresentada após a tentativa de realizar o cadastro sem preencher o campo "Nome".

## Dúvidas para refinamento

1. A mensagem aparece em qual local?
