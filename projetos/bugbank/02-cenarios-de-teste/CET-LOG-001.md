# CET-LOG-001 — Impedir login com o campo de senha vazio

**Dado** que estou na tela de login  
**Quando** preencho o campo de e-mail com um e-mail válido e cadastrado  
**E** mantenho o campo de senha vazio  
**E** aciono a opção “Acessar”  
**Então** o sistema deve exibir a mensagem “É campo obrigatório” abaixo do campo de senha  
**E** o login não deve ser efetuado  
**E** devo permanecer na tela de login  

## Observações do cenário

O endereço de e-mail informado deve estar previamente cadastrado no sistema.
