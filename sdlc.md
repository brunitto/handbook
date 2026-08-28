# SDLC

> Um bom alinhamento habilita uma boa execução.

## O Que

O SDLC define as atividades e artefatos de todo o ciclo de vida de desenvolvimento de software. Este SDLC é baseado na minha experiência pessoal.

Por definição, este SDLC é adaptado para um ambiente de desenvolvimento acelerado por IA (Harness).

## Por Que

O SDLC é importante para criar consistência no trabalho entre as pessoas e agentes de IA. O SDLC também ajuda na camada de _feedforward_ do Harness.

## Como

### Resumo

**Todo o SDLC é adaptado para o uso de agentes de desenvolvimento (Claude, Codex, Antigravity, etc).**

**Cada execução do SDLC é definido como uma mudança, ou _change_.**

O ciclo de vida padrão é:

- Agente de desenvolvimento:
  - Iniciar sessão de desenvolvimento.
  - Limpar o contexto.
  - Carregar o AGENTS.md.
- Organização do trabalho:
  - Toda mudança deve ter uma issue.
  - Revisar a issue (título, descrição, comentários).
  - Criar e associar uma branch com a issue.
  - Mudar para a branch criada.
  - Iniciar o ambiente de desenvolvimento.
- Especificação e design:
  -  Escrever a especificação da mudança.
  -  Revisar a especificação da mudança:
     - Se estiver OK, aprovar.
     - Se não estiver OK, alterar.
     - Pontos de atenção:
       - Padrões e práticas de desenvolvimento (handbook).
       - Decisões de arquitetura e tecnologia (adrs).
       - Prioridade das tarefas.
       - Plano de validação.
- Testes e implementação:
  - Escrever os testes da mudança.
  - Executar os testes e falhar.
  - Escrever a implementação e passar.
  - Refatorar e continuar passando.
  - Executar `build`, `test` e `lint`:
    - Se passar, continuar.
    - Se não passar, arrumar.
  - Abrir PR.
- Revisão de código:
  - Executar `build`, `test` e `lint` automaticamente:
    - Se passar, continuar.
    - Se não passar, notificar o time de desenvolvimento e não aprovar a PR.
  - Refatorar o código e continuar passando nos testes.
  - Aprovar PR.
- Testes e integração:
  - Executar `build`, `test` e `lint`:
    - Se passar, continuar.
    - Se não passar, notificar o time de desenvolvimento.
  - Executar validações adicionais:
    - Dependências.
    - SAST/DAST.
  - Criar pacote e rotular com o _hash_ do último commit.
- Entrega e publicação:
  - Executar o _workflow_ de publicação manualmente.
  - Especificar o ambiente (`STG`, `PRD`).
  - Especificar o _hash_ do pacote.
  - Monitorar.

### Agente de Desenvolvimento

TODO.

### Trunk-Based Development

TODO.

### Ambiente de Desenvolvimento

TODO.

### SDD

TODO.

### TDD

TODO.

### Conventional Commits

TODO.

### PRs

TODO.

### CI/CD

TODO.
