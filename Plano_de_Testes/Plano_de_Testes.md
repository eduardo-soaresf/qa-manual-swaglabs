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