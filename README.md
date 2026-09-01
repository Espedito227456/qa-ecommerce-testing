# QA E-commerce Testing

## Sobre o projeto

Projeto de **QA Manual** desenvolvido para testar uma aplicação de e-commerce web.

O projeto tem como objetivo aplicar na prática conceitos de qualidade de software, incluindo planejamento de casos de teste, execução de testes funcionais, registro de resultados, coleta de evidências, identificação de possíveis defeitos e documentação.

## Objetivo

Validar o funcionamento das principais funcionalidades de uma aplicação de e-commerce, utilizando cenários positivos e negativos.

Durante o projeto serão executados **15 casos de teste**, com registro dos resultados e das respectivas evidências.

## Escopo dos testes

Os testes serão realizados nas seguintes áreas:

* Cadastro de usuário
* Login
* Autenticação
* Busca de produtos
* Visualização de produtos
* Carrinho de compras
* Inclusão e remoção de produtos
* Checkout
* Preenchimento de dados
* Pagamento
* Finalização de pedido
* Validações de campos
* Cenários negativos

## Casos de teste

| ID     | Cenário                              | Status     |  Jira   |
| ------ | ------------------------------------ | ---------- | ------- |
| EQL-1  | Acesso à página inicial              |   PASS     | [EQL-1](https://espeditomarquesdossantos.atlassian.net/browse/EQL-1)   |
| EQL-2 | Cadastro de novo usuário | PASS | [EQL-2](https://espeditomarquesdossantos.atlassian.net/browse/EQL-2) |
| EQL-3  | Login com credenciais válidas        | A EXECUTAR |
| EQL-4  | Login com senha inválida             | A EXECUTAR |
| EQL-5  | Login com usuário inválido           | A EXECUTAR |
| EQL-6  | Busca por produto existente          | A EXECUTAR |
| EQL-7  | Busca por produto inexistente        | A EXECUTAR |
| EQL-8  | Visualização de produto              | A EXECUTAR |
| EQL-9  | Adicionar produto ao carrinho        | A EXECUTAR |
| EQL-10 | Alterar quantidade de produto        | A EXECUTAR |
| EQL-11 | Remover produto do carrinho          | A EXECUTAR |
| EQL-12 | Checkout com dados válidos           | A EXECUTAR |
| EQL-13 | Checkout com campo obrigatório vazio | A EXECUTAR |
| EQL-14 | Validação do pagamento               | A EXECUTAR |
| EQL-15 | Finalização de pedido                | A EXECUTAR |

## Jira

Os casos de teste e o acompanhamento da execução serão registrados no projeto **E-commerce QA Lab**, no Jira.

**Projeto Jira:** EQL

Os links individuais dos casos serão adicionados conforme os testes forem criados.

## Evidências

As evidências dos testes serão armazenadas no diretório:

`evidencias/`

Cada caso de teste terá sua própria pasta para organização das capturas de tela e demais evidências.

## Bugs

Possíveis defeitos encontrados durante a execução serão registrados no diretório:

`bugs/`

Cada bug confirmado deverá conter informações como:

* Título
* Ambiente
* Passos para reprodução
* Resultado esperado
* Resultado obtido
* Evidência
* Severidade
* Prioridade

## Relatórios

Os relatórios finais da execução serão armazenados no diretório:

`relatorios/`

## Estrutura do projeto

```text
qa-ecommerce-testing/
│
├── bugs/
├── casos-de-teste/
├── evidencias/
├── relatorios/
└── README.md
```

## Ferramentas utilizadas

* Jira
* Git
* GitHub
* VS Code
* Excel
* Testes funcionais manuais

## Metodologia

O projeto segue o fluxo:

**Planejamento → Caso de teste → Jira → Execução → Evidência → Resultado → Bug Report (quando aplicável) → Relatório**

## Status do projeto

**Em andamento — 2/15 casos de teste executados.**
