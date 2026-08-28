# HARNESS

> Um bom alinhamento habilita uma boa execução.

## O Que

O Harness define como as pessoas e agentes de IA devem desenvolver software. Essa arquitetura é baseada na minha experiência pessoal.

## Por Que

O Harness é importante para garantir a velocidade e qualidade no desenvolvimento.

## Como

### Arquitetura

A arquitetura inclui:

- Pessoas: pessoas responsáveis por direcionar o desenvolvimento do sistema.
- Agentes: agentes responsáveis pelo desenvolvimento do sistema.
- Feedforward: recursos e ferramentas para orientar o desenvolvimento.
- Feedback: recursos e ferramentas para validar o desenvolvimento.

A infraestrutura inclui:

- Core:
  - Monorepo: code, issues, branches, commits, PRs, etc.
  - Agente: Claude, Codex, Antigravity, etc.
- Feedforward:
  - Documentação: ADRs, handbook, arquitetura, sistema.
  - Especificações: PRDs, design docs, OpenAPI, etc.
  - Habilidades: PM, designer, manager, developer, etc.
  - Scripts: bootstrap, scaffold, provisioning, etc.
- Feedback:
  - Habilidades: quality, security, SRE.
  - Scripts: build, test, lint, SAST/DAST, etc.

### Monorepo

O Harness usa um monorepo garante contexto completo para os agentes de desenvolvimento, e menos complexidade para gerenciar dependências e mudanças no sistema.

### Agentes

O Harness funciona para qualquer agente de desenvolvimento compatível com o `AGENTS.md`.

### Modelos

Equilibrar nível de raciocínio e custos de acordo com o tipo de trabalho:

- Raciocínio baixo: atualização de issues, funcionalidades, correções e tarefas simples.
- Raciocínio médio: planejamento de issues, PRs, funcionalidades e correções e tarefas comuns.
- Raciocínio alto: design, refatoração, funcionalidades, correções e tarefas complexas.

### Habilidades

Usar habilidades para economizar contexto e especializar tarefas:

- PM: foca na dor do usuário, conduz conversas sobre descoberta e design.
- Designer: foca na experiência do usuário, conduz conversas sobre experiência e design.
- Manager: foca na organização do trabalho e padrões e práticas de desenvolvimento, conduz conversas sobre prioridade e remove bloqueios.
- Developer: foca no desenvolvimento e arquitetura, conduz conversas sobre soluções e tecnologias.
- Quality: foca na qualidade do sistema, funcional e não funcional, conduz conversas sobre qualidade.
- Security: foca na segurança do sistema, conduz conversas sobre desenvolvimento seguro.
- SRE: foca na operação e confiabilidade do sistema, conduz conversas sobre monitoramento e performance.

### Ferramentas

Usar ferramentas para aumentar o contexto e autonomia das pessoas e agentes:

- GitHub: usar o `gh` (cliente CLI do GitHub).
