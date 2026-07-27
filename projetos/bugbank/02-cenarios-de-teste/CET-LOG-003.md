# CET-LOG-003 — Impedir login com os campos de e-mail e senha vazios

**Dado** que estou na tela de login  
**Quando** mantenho os campos de e-mail e senha vazios  
**E** aciono a opção “Acessar”  
**Então** o sistema deve exibir a mensagem “É campo obrigatório” abaixo dos campos de e-mail e senha  
**E** o login não deve ser efetuado  
**E** devo permanecer na tela de login  

## Observações do cenário

As mensagens de obrigatoriedade devem ser apresentadas simultaneamente nos dois campos.
