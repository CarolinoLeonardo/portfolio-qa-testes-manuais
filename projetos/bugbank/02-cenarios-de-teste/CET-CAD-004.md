# CET-CAD-004 — Validar exibição da mensagem "Nome não pode ser vazio" ao tentar criar nova conta sem preencher o campo obrigatório Nome

**Dado** que estou na página de cadastro de nova conta  
**Quando** deixo vazio o campo obrigatório "Nome"  
**E** preencho com dados válidos o demais campos obrigatórios  
**E** clico na opção "Cadastrar"  
**Então** o sistema não conclui o cadastro de nova conta  
**E** permaneço na tela de cadastro de nova conta  
**E** o sistema exibe a mensagem "Nome não pode ser vazio".  

## Observações do cenário

O E-mail a ser utilizado não pode estar previamente cadastrado no sistema.
