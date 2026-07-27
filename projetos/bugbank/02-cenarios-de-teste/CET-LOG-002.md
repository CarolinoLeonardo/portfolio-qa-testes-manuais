# CET-LOG-002 — Impedir login com o campo de e-mail vazio

**Dado** que estou na tela de login  
**Quando** preencho o campo de senha com uma senha válida e cadastrada  
**E** mantenho o campo de e-mail vazio  
**E** aciono a opção “Acessar”  
**Então** o sistema deve exibir a mensagem “É campo obrigatório” abaixo do campo de e-mail  
**E** o login não deve ser efetuado  
**E** devo permanecer na tela de login  

## Observações do cenário

A senha informada deve estar vinculada a uma conta previamente cadastrada no sistema.
