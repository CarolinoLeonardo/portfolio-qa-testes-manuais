# REQ-CAD-001 — Bloqueio de senha sequencial

## Descrição

O sistema deve impedir a criação de uma nova conta quando a senha for composta exclusivamente por seis dígitos consecutivos em ordem crescente.

## Exemplo de senha inválida

```text
123456
```

## Critério de aceite

- A conta não deve ser criada.
- O sistema deve informar que a senha não atende à política de segurança.

## Pontos que precisam de esclarecimento

1. Sequências decrescentes, como `654321`, também devem ser bloqueadas?
2. Outras sequências crescentes, como `234567`, devem ser bloqueadas?
3. A regra se aplica quando a sequência aparece dentro de uma senha maior, como `Abc123456!`?
4. Senhas com seis números repetidos, como `111111`, também são consideradas inválidas?
5. Existe uma mensagem obrigatória definida pelo negócio?
