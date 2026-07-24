# CET-CAD-001 — Cadastro com senha sequencial

## Cenário

**Dado** que o usuário está na tela de cadastro de nova conta  
**E** preencheu os demais campos com dados válidos  
**Quando** informar a senha `123456`  
**E** confirmar a mesma senha  
**E** solicitar o cadastro  
**Então** a conta não deve ser criada  
**E** o sistema deve apresentar uma mensagem informando que a senha não atende à política de segurança.
