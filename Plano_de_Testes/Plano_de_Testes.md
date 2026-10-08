# Plano de Testes

**Projeto:** Swag Labs - QA Manual

**Versao:** 1.0

**Responsavel:** Eduardo Soares

**Data:** 18/07/2026

**Status:** Em elaboracao

## 1. Objetivo

Este documento tem como objetivo definir a estratégia de testes para a aplicação Swag Labs, descrevendo o escopo, o ambiente, os critérios e as funcionalidades que serão validadas durante a execução dos testes manuais, garantindo a qualidade das funcionalidades críticas da aplicação e proporcionando uma experiência consistente ao usuário final.


## 2. Escopo

O escopo do projeto contempla a validação das principais funcionalidades da aplicação web Swag Labs, garantindo que os fluxos críticos estejam funcionando corretamente antes da liberação para produção.

Serão realizados testes nas seguintes funcionalidades:

Autenticação de usuários (login e logout);
Validação das mensagens de erro de autenticação;
Exibição e integridade do catálogo de produtos;
Ordenação da listagem de produtos (A-Z, Z-A);
Adição e remoção de produtos do carrinho;
Navegação entre as páginas da aplicação;
Preenchimento das informações do checkout;
Finalização da compra;
Validação do fluxo completo de compra (End-to-End).

## 3. Fora do Escopo

Nesta Sprint, não fazem parte do escopo deste projeto:

Testes de performance e carga;
Testes de APIs;
Testes de segurança;
Testes de compatibilidade entre diferentes navegadores e dispositivos.

O foco desta etapa é a execução de testes funcionais manuais na aplicação web, validando os principais fluxos da jornada do usuário e garantindo o correto funcionamento das funcionalidades previstas na Sprint.

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
