# QA Manual — Swag Labs

Projeto de Quality Assurance desenvolvido no contexto da InsightHub, com foco na aplicação de práticas de testes de software em uma aplicação de e-commerce.

O projeto simula um ciclo de QA, abrangendo desde a análise de requisitos e o planejamento dos testes até a execução, identificação de defeitos e documentação dos resultados.

## Sobre a InsightHub

A InsightHub é uma empresa fictícia de tecnologia, criada para representar um ambiente profissional de desenvolvimento de software e Quality Assurance.

Neste portfólio, a empresa serve como contexto para projetos práticos que simulam demandas, processos e atividades de uma equipe de QA, abrangendo desde a análise de requisitos até a validação da qualidade de aplicações.

Os projetos são desenvolvidos com foco na aplicação de práticas do mercado, utilizando ferramentas e metodologias presentes no cotidiano de equipes de tecnologia.

## Sobre o projeto

O Swag Labs é uma aplicação web de demonstração que simula uma loja virtual, permitindo explorar funcionalidades como autenticação, catálogo de produtos, carrinho e checkout.

A aplicação será utilizada como objeto de testes para validar regras de negócio, comportamentos esperados e possíveis defeitos ao longo da jornada de compra.

**Informações do projeto:**

- **Empresa:** InsightHub
- **Aplicação:** Swag Labs
- **Tipo:** Projeto prático de estudo e portfólio
- **Abordagem:** QA Manual
- **Status:** Em desenvolvimento

## Objetivos

- Aplicar técnicas de análise e planejamento de testes.
- Elaborar casos de teste com base em requisitos e critérios de aceitação.
- Validar funcionalidades e regras de negócio da aplicação.
- Identificar, documentar e acompanhar defeitos.
- Registrar resultados e evidências das execuções.
- Aplicar práticas de QA utilizadas em equipes de desenvolvimento de software.
- Preparar a base para a implementação de testes automatizados.

## Escopo dos testes

Os testes serão concentrados em três áreas funcionais da aplicação:

### 1. Acesso à aplicação

- Autenticação com credenciais válidas e inválidas.
- Tratamento de tentativas de acesso com usuários bloqueados.
- Encerramento da sessão por meio do logout.

### 2. Catálogo de produtos

- Exibição e integridade das informações dos produtos.
- Validação de nomes, imagens, descrições e preços.
- Ordenação de produtos por nome e preço.
- Visualização dos detalhes dos produtos.

### 3. Jornada de compra

- Adição e remoção de produtos do carrinho.
- Visualização dos itens selecionados.
- Início e preenchimento do checkout.
- Revisão das informações do pedido.
- Finalização da compra e confirmação do pedido.

Os cenários serão definidos com base nas histórias de usuário, regras de negócio e critérios de aceitação documentados no Jira.

## Fora do escopo

Nesta etapa do projeto, não serão contemplados:

- **Testes de performance e carga:** avaliação de desempenho, capacidade e comportamento sob alto volume de acessos.
- **Testes de API:** validação direta de endpoints e serviços da aplicação.
- **Testes de segurança:** análise de vulnerabilidades e mecanismos de proteção.
- **Testes de compatibilidade:** validação em diferentes navegadores, sistemas operacionais e dispositivos.

O foco desta etapa está nos testes funcionais manuais da aplicação web, considerando os requisitos e comportamentos definidos para o projeto.

## Ferramentas e tecnologias

| Ferramenta | Aplicação no projeto |
|---|---|
| Jira | Gerenciamento de Epics, histórias de usuário, critérios de aceitação, backlog e defeitos. |
| Qase | Organização de suítes, casos de teste, execuções e evidências. |
| GitHub | Versionamento, documentação e histórico do projeto. |
| Visual Studio Code | Edição dos arquivos de documentação e desenvolvimento. |
| Google Chrome | Navegador utilizado para acessar e testar a aplicação. |
| Swag Labs | Aplicação web utilizada como objeto de testes. |

## Processo de QA

O projeto seguirá um fluxo estruturado de Quality Assurance, contemplando as seguintes etapas:

1. **Análise da demanda:** entendimento das histórias de usuário, requisitos, regras de negócio e critérios de aceitação.
2. **Planejamento dos testes:** definição do escopo, estratégia, ambiente, dados e critérios para execução.
3. **Desenho dos casos de teste:** elaboração de cenários com pré-condições, dados de teste, passos e resultados esperados.
4. **Execução dos testes:** realização dos cenários planejados, registro dos resultados e coleta de evidências.
5. **Gestão de defeitos:** documentação das falhas identificadas, acompanhamento das correções e realização de retestes e testes de regressão.
6. **Conclusão dos testes:** consolidação dos resultados, cobertura dos requisitos, defeitos e eventuais pendências.

As atividades serão documentadas e acompanhadas por meio do Jira, Qase e GitHub.

## Estrutura do repositório

```text
qa-manual-swaglabs/
│
├── Plano_de_Testes/
│   └── Plano_de_Testes.md
│
└── README.md
```

A estrutura será ampliada conforme a evolução do projeto e a criação de novos artefatos de QA.

## Artefatos do projeto

Os principais artefatos utilizados para documentar e acompanhar o processo de QA são:

| Artefato | Descrição | Localização |
|---|---|---|
| Plano de Testes | Documento que define escopo, estratégia, ambiente e critérios de teste. | [Acessar documento](Plano_de_Testes/Plano_de_Testes.md) |
| Histórias de Usuário | Requisitos funcionais e critérios de aceitação das funcionalidades. | Jira |
| Casos de Teste | Cenários estruturados com pré-condições, passos e resultados esperados. | Qase |
| Evidências de Teste | Registros que demonstram os resultados das execuções. | Qase |
| Registro de Defeitos | Documentação e acompanhamento das falhas identificadas. | Jira |

Os artefatos serão incorporados e atualizados conforme o avanço das etapas do projeto.

## Resultados dos testes

Os resultados serão consolidados após a execução dos casos de teste, permitindo acompanhar a qualidade das funcionalidades avaliadas.

Serão considerados os seguintes indicadores:

- Total de casos de teste planejados e executados.
- Quantidade de testes aprovados, reprovados e bloqueados.
- Defeitos identificados e respectivos níveis de severidade.
- Cobertura das histórias de usuário e critérios de aceitação.
- Resultados dos retestes e testes de regressão.

Os indicadores serão atualizados com base nas execuções registradas no Qase e nos defeitos documentados no Jira.

## Próximas etapas

- Finalização e revisão do Plano de Testes.
- Organização dos casos de teste no Qase, vinculados às histórias de usuário do Jira.
- Execução dos cenários funcionais e registro das evidências.
- Documentação de defeitos, acompanhamento das correções e retestes.
- Implementação de testes automatizados utilizando Selenium WebDriver.
- Evolução futura da automação com Playwright.
- Aplicação de SQL para consultas, validação de dados e preparação de massas de teste.
- Desenvolvimento de indicadores e dashboards de qualidade.

---

**InsightHub | Quality Assurance**

*Qualidade não é apenas encontrar defeitos, mas garantir que o software atenda aos requisitos e entregue o comportamento esperado.*