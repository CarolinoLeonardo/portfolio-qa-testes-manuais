# BUG-CAD-001 — Cadastro permite senha sequencial `123456`

## Resumo

A aplicação permite criar uma nova conta utilizando a senha sequencial de seis dígitos `123456`, contrariando o requisito REQ-CAD-001.

## Classificação

| Campo | Valor |
|---|---|
| Módulo | Cadastro de usuário |
| Severidade sugerida | Média |
| Prioridade sugerida | Média |
| Status | Aberto |
| Reprodutibilidade | 1 de 1 execução |
| Ambiente | Ambiente público de demonstração do BugBank |
| Navegador | Google Chrome 150.0.7871.130 — 64 bits |
| Data | 22/07/2026 |
| Reportado por | Leonardo Carolino |
| Caso de teste | [CT-CAD-001](../03-casos-de-teste/CT-CAD-001.md) |

## Pré-condições

- Aplicação disponível.
- E-mail de teste ainda não cadastrado.

## Massa de teste

| Campo | Valor |
|---|---|
| E-mail | `qa.leonardo+ct001@example.com` |
| Nome | `Leonardo QA` |
| Senha | `123456` |
| Confirmação | `123456` |

## Passos para reprodução

1. Acessar `https://bugbank.netlify.app/`.
2. Clicar em **Registrar**.
3. Preencher os campos obrigatórios com dados válidos.
4. Informar `123456` nos campos de senha e confirmação.
5. Clicar em **Cadastrar**.

## Resultado obtido

A conta é criada com sucesso utilizando a senha sequencial `123456`.

## Resultado esperado

A conta não deve ser criada. O sistema deve informar que a senha não atende à política de segurança.

> A redação exata da mensagem precisa ser confirmada, pois não foi definida no requisito original.

## Evidências

Adicionar nesta pasta:

- captura antes do envio do formulário;
- captura ou vídeo mostrando a confirmação da criação da conta;
- data e horário da execução;
- arquivo de vídeo curto, quando necessário.

Pasta: [`../05-evidencias/CT-CAD-001`](../05-evidencias/CT-CAD-001)
