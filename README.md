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

| ID     | Cenário                              | Status     |
| ------ | ------------------------------------ | ---------- |
| QTL-01 | Cadastro de novo usuário             | A EXECUTAR |
| QTL-02 | Login com credenciais válidas        | A EXECUTAR |
| QTL-03 | Login com senha inválida             | A EXECUTAR |
| QTL-04 | Login com usuário inválido           | A EXECUTAR |
| QTL-05 | Busca por produto existente          | A EXECUTAR |
| QTL-06 | Busca por produto inexistente        | A EXECUTAR |
| QTL-07 | Visualização de produto              | A EXECUTAR |
| QTL-08 | Adicionar produto ao carrinho        | A EXECUTAR |
| QTL-09 | Remover produto do carrinho          | A EXECUTAR |
| QTL-10 | Alterar quantidade de produto        | A EXECUTAR |
| QTL-11 | Checkout com dados válidos           | A EXECUTAR |
| QTL-12 | Checkout com campo obrigatório vazio | A EXECUTAR |
| QTL-13 | Validação do pagamento               | A EXECUTAR |
| QTL-14 | Finalização de pedido                | A EXECUTAR |
| QTL-15 | Logout do usuário                    | A EXECUTAR |

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

**Em andamento — 0/15 casos de teste executados.**
