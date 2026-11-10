# Plano de Testes

**Projeto:** Swag Labs - QA Manual

**Versao:** 1.0

**Responsavel:** Eduardo Soares

**Data:** 09/11/2026

**Status:** Em elaboração

## 1. Objetivo

Este documento tem como objetivo estabelecer o planejamento e a estratégia de testes funcionais manuais da aplicação web Swag Labs, definindo o escopo, o ambiente, os critérios e as atividades necessárias para avaliar o comportamento das principais funcionalidades da aplicação.

O projeto tem como finalidade simular um processo de QA em um ambiente de desenvolvimento de software, contemplando desde a análise dos requisitos até a execução dos testes, identificação de defeitos e registro de evidências.


## 2. Escopo

O escopo contempla a validação das principais funcionalidades da aplicação Swag Labs, organizadas em três áreas:

Acesso à aplicação

Realização de login com credenciais válidas e inválidas;

Tratamento de tentativas de acesso por usuários bloqueados;

Realização de logout.

Catálogo de produtos

Exibição e integridade das informações dos produtos;

Validação de nomes, imagens, descrições e preços;

Ordenação dos produtos por nome (A-Z e Z-A);

Ordenação dos produtos por preço (menor para maior e maior para menor);

Visualização dos detalhes dos produtos.

Jornada de compra

Adição e remoção de produtos do carrinho;

Visualização dos produtos adicionados;

Navegação entre as etapas do checkout;

Preenchimento das informações solicitadas;

Revisão e confirmação do pedido;

Validação da confirmação da compra;

Teste do fluxo completo de compra (End-to-End).

Os testes serão organizados e executados de acordo com os requisitos e critérios de aceite definidos para cada User Story, considerando os fluxos funcionais e as regras de negócio da aplicação.

## 3. Fora do Escopo

Testes de performance e carga;

Testes de APIs;

Testes de segurança;

Testes de compatibilidade entre diferentes navegadores e dispositivos.

O foco deste projeto está na execução de testes funcionais manuais em uma aplicação web, com ênfase na validação dos requisitos, dos comportamentos esperados e dos principais fluxos de utilização.

## 4. Ambiente de Testes

Nesta seção são descritos os ambientes e as condições necessárias para a execução dos testes da aplicação.

| Item | Informação |
| ---- | ---------- |
| **Aplicação** | Swag Labs |
| **Tipo** | Aplicação Web |
| **URL** | https://www.saucedemo.com |
| **Sistema Operacional** | Windows 11 |
| **Navegador** | Google Chrome (versão instalada na máquina de testes) |
| **Conexão com a Internet** | Obrigatória |

### Massas de Teste

Os testes serão executados utilizando as massas de teste disponibilizadas pela aplicação.

#### Usuários

- `standard_user`
- `locked_out_user`
- `problem_user`
- `performance_glitch_user`
- `error_user`
- `visual_user`

#### Senha

```text
secret_sauce
```

## 5. Estratégia de Testes

A estratégia adotada neste projeto consiste na validação dos principais fluxos da jornada do usuário, executando testes funcionais manuais de ponta a ponta (End-to-End) para garantir o correto funcionamento das funcionalidades contempladas nesta Sprint.

A execução dos testes seguirá a seguinte sequência:

- Autenticação (Login);
- Navegação pela aplicação;
- Validação do catálogo de produtos;
- Adição e remoção de produtos do carrinho;
- Preenchimento das informações do checkout;
- Finalização da compra;
- Logout da aplicação.

Durante a execução dos testes, todas as evidências serão registradas e qualquer comportamento divergente do esperado será documentado por meio de um Bug Report no Jira, contendo a descrição do problema, passos para reprodução, severidade e evidências.

Após a correção dos defeitos pela equipe de desenvolvimento, serão realizados os retestes necessários para validar a solução implementada e garantir que a funcionalidade esteja apta para publicação.

## 6. Critérios de Entrada

A execução dos testes será iniciada após a análise e compreensão da Story e dos requisitos da funcionalidade.

Para início da execução, devem ser atendidos os seguintes critérios:

- Story e requisitos da funcionalidade disponíveis e analisados;
- Critérios de aceite definidos e compreendidos;
- Regras de negócio identificadas;
- Comportamento esperado da funcionalidade compreendido;
- Funcionalidade disponível no ambiente de testes;
- Ambiente de testes acessível e operacional;
- Massa de testes disponível;
- Casos de teste elaborados e cadastrados no Qase.

Após o atendimento desses critérios, a execução dos testes poderá ser iniciada.
