# Projeto de Testes Manuais — BugBank

[Voltar ao portfólio](../../README.md)

Este projeto apresenta o planejamento, a documentação e a execução de testes manuais na aplicação web [BugBank](https://bugbank.netlify.app/).

O BugBank simula operações de uma aplicação bancária e foi desenvolvido para a prática de testes de software.

---

## Informações do projeto

| Informação     | Descrição                |
| -------------- | ------------------------ |
| Aplicação      | BugBank                  |
| Plataforma     | Web                      |
| Tipos de teste | Funcional e exploratório |
| Responsável    | Leonardo Carolino        |
| Início         | Julho de 2026            |
| Status         | Em andamento             |

---

## Objetivo

Praticar o processo de QA manual, incluindo:

* análise de requisitos;
* criação de cenários de teste;
* elaboração e execução de casos de teste;
* realização de testes exploratórios;
* registro de defeitos;
* organização dos artefatos;
* rastreabilidade entre requisitos, testes e bugs.

---

## Abordagem de testes

### Testes baseados em requisitos

Parte dos cenários e casos de teste é criada com base nos [requisitos funcionais publicados pelo BugBank](https://bugbank.netlify.app/requirements).

### Testes exploratórios

O projeto também inclui testes criados a partir da exploração livre da aplicação.

Comportamentos relevantes encontrados durante essas sessões podem gerar:

* requisitos complementares;
* cenários de teste;
* casos de teste;
* relatórios de bug.

A origem exploratória será identificada na documentação correspondente.

---

## Escopo funcional

O projeto pretende cobrir gradualmente os seguintes módulos:

| Módulo        | Situação no projeto |
| ------------- | ------------------- |
| Cadastro      | Em andamento        |
| Login         | Em andamento        |
| Transferência | Planejado           |
| Pagamento     | Planejado           |
| Extrato       | Planejado           |
| Saque         | Planejado           |

---

## Requisitos documentados

| Código                                      | Requisito                                                         | Status   |
| ------------------------------------------- | ----------------------------------------------------------------- | -------- |
| [REQ-CAD-001](01-requisitos/REQ-CAD-001.md) | Bloqueio de senha sequencial                                      | Entregue |
| [REQ-CAD-002](01-requisitos/REQ-CAD-002.md) | Cadastro de novo usuário                                          | Entregue |
| [REQ-LOG-001](01-requisitos/REQ-LOG-001.md) | Obrigatoriedade dos campos de e-mail e senha para efetuar o login | Entregue |
| [REQ-LOG-002](01-requisitos/REQ-LOG-002.md) | Indicação visual de que e-mail e senha são campos obrigatórios    | Entregue |
| [REQ-LOG-003](01-requisitos/REQ-LOG-003.md) | Tentativa de acesso sem preencher os campos obrigatórios          | Entregue |

Novos requisitos serão adicionados conforme o avanço da análise funcional e dos testes exploratórios.

---

## Rastreabilidade

Os documentos utilizam códigos padronizados para facilitar a ligação entre os artefatos.

| Prefixo | Documento        |
| ------- | ---------------- |
| `REQ`   | Requisito        |
| `CET`   | Cenário de teste |
| `CT`    | Caso de teste    |
| `BUG`   | Relatório de bug |

Os módulos também recebem identificadores:

| Código | Módulo        |
| ------ | ------------- |
| `CAD`  | Cadastro      |
| `LOG`  | Login         |
| `TRA`  | Transferência |
| `PAG`  | Pagamento     |
| `EXT`  | Extrato       |
| `SAQ`  | Saque         |

Exemplo:

```text
REQ-LOG-003
     ↓
CET-LOG-003
     ↓
CT-LOG-005
     ↓
BUG-LOG-003
```

---

## Fluxo de trabalho

```text
Análise do requisito ou exploração da aplicação
                        ↓
             Criação do requisito
                        ↓
          Criação do cenário de teste
                        ↓
         Elaboração do caso de teste
                        ↓
             Execução do teste
                        ↓
       Registro do resultado e evidências
                        ↓
        Abertura do bug, quando necessário
```

---

## Estrutura do projeto

```text
bugbank/
├── 01-requisitos/
├── 02-cenarios-de-teste/
├── 03-casos-de-teste/
├── 04-bug-reports/
├── 05-anexos-originais/
└── README.md
```

| Diretório              | Conteúdo                                             |
| ---------------------- | ---------------------------------------------------- |
| `01-requisitos`        | Requisitos analisados e documentados                 |
| `02-cenarios-de-teste` | Cenários de teste                                    |
| `03-casos-de-teste`    | Casos de teste e resultados das execuções            |
| `04-bug-reports`       | Defeitos encontrados                                 |
| `05-anexos-originais`  | Documentos e imagens originais utilizados no projeto |

---

## Observações

* O projeto está em desenvolvimento contínuo.
* Os requisitos podem ser refinados conforme novas informações forem identificadas.
* Os dados utilizados nos testes são sintéticos.
* A aplicação armazena suas informações localmente e não utiliza um banco de dados persistente.
* Este projeto possui finalidade educacional e profissional.

