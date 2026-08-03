# Portfólio de QA — Testes Manuais -- Por Leonardo Carolino

Este repositório reúne projetos práticos de Quality Assurance desenvolvidos por **Leonardo Carolino** durante sua transição de carreira para a área de tecnologia.

O objetivo é demonstrar conhecimentos em planejamento, documentação, execução e acompanhamento de testes manuais.

---

## Projetos

| Projeto                               | Tipo de teste                             | Status       |
| ------------------------------------- | ----------------------------------------- | ------------ |
| [BugBank](projetos/bugbank/README.md) | Testes manuais funcionais e exploratórios | Em andamento |

---

## Projeto BugBank

O [BugBank](https://bugbank.netlify.app/) é uma aplicação bancária web criada para a prática de testes de software.

Neste projeto, os testes são desenvolvidos com base nos [requisitos funcionais da aplicação](https://bugbank.netlify.app/requirements) e também em comportamentos identificados durante testes exploratórios.

### Escopo

Os testes abrangem os seguintes módulos:

* Login;
* Cadastro;
* Transferência;
* Extrato.

Os módulos de Pagamento e Saque ainda aparecem como funcionalidades em desenvolvimento na aplicação.

### Atividades realizadas

* Análise de requisitos;
* Criação de cenários de teste;
* Elaboração e execução de casos de teste;
* Realização de testes exploratórios;
* Registro de defeitos;
* Organização de evidências;
* Rastreabilidade entre requisitos, testes e bugs.

---

## Requisitos documentados

| Código                                                       | Requisito                                                | Origem                 | Status   |
| ------------------------------------------------------------ | -------------------------------------------------------- | ---------------------- | -------- |
| [REQ-CAD-001](projetos/bugbank/01-requisitos/REQ-CAD-001.md) | Bloqueio de senha sequencial                             | Teste exploratório     | Entregue |
| [REQ-CAD-002](projetos/bugbank/01-requisitos/REQ-CAD-002.md) | Cadastro de novo usuário                                 | Requisito funcional    | Entregue |
| [REQ-LOG-001](projetos/bugbank/01-requisitos/REQ-LOG-001.md) | Obrigatoriedade dos campos de e-mail e senha             | Requisito funcional    | Entregue |
| [REQ-LOG-002](projetos/bugbank/01-requisitos/REQ-LOG-002.md) | Indicação visual dos campos obrigatórios                 | Requisito complementar | Entregue |
| [REQ-LOG-003](projetos/bugbank/01-requisitos/REQ-LOG-003.md) | Tentativa de acesso sem preencher os campos obrigatórios | Requisito funcional    | Entregue |

Novos requisitos, cenários e casos de teste serão adicionados conforme o avanço do projeto e das sessões de testes exploratórios.

---

## Convenção de códigos

| Prefixo | Documento        |
| ------- | ---------------- |
| `REQ`   | Requisito        |
| `CET`   | Cenário de teste |
| `CT`    | Caso de teste    |
| `BUG`   | Relatório de bug |

| Código | Módulo        |
| ------ | ------------- |
| `LOG`  | Login         |
| `CAD`  | Cadastro      |
| `TRA`  | Transferência |
| `EXT`  | Extrato       |

Exemplo de rastreabilidade:

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

## Organização do repositório

```text
portfolio-qa-testes-manuais/
├── projetos/
│   └── bugbank/
│       ├── 01-requisitos/
│       ├── 02-cenarios-de-teste/
│       ├── 03-casos-de-teste/
│       ├── 04-bug-reports/
│       ├── 05-anexos-originais/
│       └── README.md
├── templates/
└── README.md
```

---

## Competências demonstradas

* Testes manuais funcionais e exploratórios;
* Análise e documentação de requisitos;
* Criação e execução de casos de teste;
* Registro e classificação de defeitos;
* Organização de evidências;
* Rastreabilidade entre artefatos de teste.

---

## Observações

* O projeto está em desenvolvimento contínuo.
* Os dados utilizados nos testes são fictícios.
* Este repositório possui finalidade educacional e profissional.
