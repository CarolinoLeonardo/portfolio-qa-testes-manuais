# BUG-LOG-003 — Sistema não exibiu a mensagem "Usuário e senha precisam ser preenchidos"

## Resumo

Ao tentar realizar o acesso ao sistema sem preencher os campos obrigatórios, o sistema não exibiu a mensagem "Usuário e senha precisam ser preenchidos" conforme REQ-LOG-003. Ao invés disso, o sistema exibe a mensagem "Campo Obrigatório" logo abaixo do input obrigatório.

## Classificação

| Campo | Valor |
|---|---|
| Módulo | Login de usuário |
| Severidade | Média |
| Prioridade | Baixa |
| Status | Aberto |
| Ambiente | Ambiente público de demonstração do Bugbank |
| Navegador/SO | Navegador Chrome - Versão 151.0.7922.71 (Versão oficial) 64 bits |
| Data | 30/07/2026 |
| Reportado por | Leonardo Carolino |
| Caso de teste | CT-LOG-005 |

## Pré-condições

- Navegador com acesso à internet
- Aplicação Bugbank disponível

## Massa de teste

| Campo | Valor |
|---|---|
| E-mail | Não preencher |
| Senha | Não preencher |

## Passos para reprodução

1. Acessar `https://bugbank.netlify.app/`
2. Não preencher os campos obrigatórios
3. Clicar na opção "Acessar"

## Resultado obtido

O sistema não exibiu a mensagem "Usuário e senha precisam ser preenchidos", o login não foi efetuado e o usuário permaneceu na tela de acesso

## Resultado esperado

O sistema deve exibir a mensagem "Usuário e senha precisam ser preenchidos", o login não deve ser efetuado e o usuário deve permanecer na tela de acesso

## Evidências

- Print do bug após o teste em anexo
