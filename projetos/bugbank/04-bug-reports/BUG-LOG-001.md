# BUG-LOG-001 — Campos de e-mail e senha não possuem indicação visual de obrigatoriedade de preenchimento

## Resumo

Os campos “E-mail” e “Senha” da tela de login não apresentam nenhuma indicação visual de que são de preenchimento obrigatório.

A ausência dessa informação pode dificultar a compreensão do formulário pelo usuário e não atende ao requisito REQ-LOG-002.

## Classificação

| Campo | Valor |
|---|---|
| Módulo | Login de usuário |
| Severidade | Média |
| Prioridade | Média |
| Status | Aberto |
| Ambiente | Ambiente público de demonstração do BugBank |
| Navegador/SO | Google Chrome 150.0.7871.130 — Windows 64 bits |
| Data | 27/07/2026 |
| Reportado por | Leonardo Carolino |
| Caso de teste | CT-LOG-004 |

## Pré-condições

- Navegador com acesso à internet.
- Aplicação BugBank disponível.

## Massa de teste

Não se aplica.

## Passos para reprodução

1. Abrir o navegador.
2. Acessar `https://bugbank.netlify.app/`.
3. Observar o rótulo do campo “E-mail” na área de login.
4. Observar o rótulo do campo “Senha” na área de login.

## Resultado obtido

Os campos “E-mail” e “Senha” não apresentam asterisco vermelho (*) junto aos respectivos rótulos.

## Resultado esperado

Os campos “E-mail” e “Senha” devem apresentar uma indicação visual de obrigatoriedade de preenchimento junto aos respectivos rótulos, por meio de um asterisco vermelho (*).

## Evidências

- Captura de tela da área de login demonstrando a ausência de indicação visual de obrigatoriedade nos campos “E-mail” e “Senha”.
