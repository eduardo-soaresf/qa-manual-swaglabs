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
| **Navegador** | Google Chrome (Versão 155.0.8059.84 (Versão oficial) 64 bits) |
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

Os testes serão realizados manualmente, com foco na validação funcional das funcionalidades contempladas no escopo do projeto.

A estratégia será organizada por histórias de usuário, considerando suas regras de negócio, critérios de aceitação e comportamentos esperados.

As atividades incluem:

- Análise dos requisitos e critérios de aceitação.
- Elaboração e organização dos casos de teste no Qase.
- Execução dos testes funcionais e dos principais fluxos de ponta a ponta.
- Registro dos resultados e evidências das execuções.
- Identificação e documentação de defeitos no Jira, incluindo descrição, passos para reprodução, resultado esperado, resultado obtido e evidências.
- Reexecução dos testes após correções e realização de testes de regressão quando necessário.

Os resultados serão acompanhados para identificar falhas, avaliar a cobertura dos requisitos e verificar se as funcionalidades atendem ao comportamento esperado.

## 6. Critérios de Entrada

## 6. Critérios de Entrada

Para iniciar a execução dos testes, os seguintes critérios devem ser atendidos:

- Histórias de usuário disponíveis e analisadas.
- Requisitos e regras de negócio identificados.
- Critérios de aceitação definidos e compreendidos.
- Comportamentos esperados documentados.
- Ambiente de testes acessível e operacional.
- Dados de teste disponíveis.
- Casos de teste elaborados e cadastrados no Qase.

## 7. Critérios de Saída

A etapa de testes será considerada concluída quando:

- Todos os casos de teste planejados para o escopo forem executados.
- Os resultados das execuções estiverem registrados no Qase.
- As evidências relevantes estiverem documentadas.
- Os defeitos identificados estiverem registrados no Jira.
- Os defeitos corrigidos tiverem sido retestados.
- Os resultados, pendências e riscos conhecidos estiverem consolidados.

## 8. Tipos de Teste

Serão aplicados os seguintes tipos de teste:

- **Teste funcional:** verifica se as funcionalidades atendem aos requisitos e critérios de aceitação.
- **Teste positivo:** valida o comportamento esperado com dados e condições válidas.
- **Teste negativo:** verifica o tratamento de entradas inválidas e situações não permitidas.
- **Teste exploratório:** permite investigar comportamentos e identificar falhas além dos cenários previamente documentados.
- **Teste de regressão:** verifica se alterações ou correções não impactaram funcionalidades existentes.
- **Teste ponta a ponta (E2E):** valida a jornada completa do usuário, desde o acesso à aplicação até a finalização da compra.

## 9. Ferramentas Utilizadas

- **Jira:** gerenciamento das histórias de usuário, critérios de aceitação, backlog e registro de defeitos.
- **Qase:** organização dos casos de teste, execução, resultados e evidências.
- **GitHub:** documentação do projeto, versionamento e histórico das atividades.
- **Google Chrome:** navegador utilizado para execução dos testes.
- **Swag Labs:** aplicação web utilizada como objeto de testes.

## 10. Riscos e Considerações

- Comportamentos específicos da aplicação podem apresentar falhas que impactem a execução dos testes.
- Indisponibilidade ou instabilidade do ambiente pode impedir a realização de determinados cenários.
- Dados de teste inadequados podem comprometer os resultados das validações.
- Alterações nos requisitos ou critérios de aceitação podem exigir revisão dos casos de teste.
- Correções realizadas durante o processo podem demandar novos testes e regressões.

Os riscos identificados serão considerados durante o planejamento e a execução, com registro de eventuais impactos nos resultados.
