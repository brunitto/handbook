# GERENCIAMENTO DE TRABALHO

> Um bom alinhamento habilita uma boa execução.

## O Que

O gerenciamento do trabalho define como estruturar, organizar e gerenciar o trabalho. Estruturar significa garantir informações consistentes como contexto, objetivos e DOD. Organizar significa garantir que todo trabalho pode ser listado, detalhado, ordenado e filtrado. Gerenciar significa garantir que o trabalho seja entregue, ajustando o escopo, mudando a prioridade e removendo os bloqueios.

## Por Que

O gerenciamento de trabalho é importante para garantir que as pessoas e agentes se concentrem no trabalho mais importante. O gerenciamento do trabalho também ajuda a criar um ambiente saudável para as pessoas e a aumentar a velocidade e qualidade de entrega.

Em um ambiente de desenvolvimento acelerado por IA (Harness), o gerenciamento do trabalho ajuda a alinhar o contexto, objetivos e DOD entre as pessoas e agentes.

## Como

### Princípios

- Todo trabalho deve ser visível.
- Todo trabalho deve ser limitado.
- Todo trabalho deve ser gerenciado.
- Todo trabalho deve acelerar os objetivos.
- Todo trabalho deve ter um prazo.

### Ferramentas

Usar o GitHub (Issues, Projects) para gerenciar o trabalho.

### Estrutura

Usar uma estrutura de três níveis para organizar o trabalho:

- OKR: resultado-chave de um objetivo, representa o aspecto objetivo do trabalho, estruturado como um milestone.
  - Iteration: iteração, representa o aspecto tempo do trabalho, estruturado como um campo do tipo Iteration.
    - Issue: demanda, representa o trabalho, estruturado como uma issue.
   
**Nota: issues podem ser quebradas em sub-issues se necessário.**

### Artefatos

- Issue: demanda de trabalho, representa algo que precisa ser feito.
- Backlog: lista estruturada e ordenada de todas as issues, representa todo o trabalho que precisa ser feito.
- Projeto: visão gerenciada do backlog, representa a organização e gerenciamento doe trabalho.

### Atividades

- Planning: planejamento do trabalho para a próxima iteração.
- Daily: gerenciamento do trabalho em progresso.
- Review: revisão do trabalho entregue.

### Planning

Antes da sessão:

- Garanta que a próxima iteração esteja definida e tenha objetivo e data.
- Garanta que todas as issues candidatas estejam especificadas (título, descrição e campos personalizados).
- Garanta que as pessoas leiam as issues antes da sessão de planejamento.
- Reserve tempo suficiente para a sessão (de duas a quatro horas para iterações de duas semanas).

Durante a sessão:

- Acesse o GitHub Project.
- Selecione a visão de tabela.
- Ordene as issues por prioridade.
- Compartilhe o contexto e o objetivo da issue.
- Discuta e revise o DOD.
- Estime a issue em conjunto.
- Decida se a issue permanecerá na iteração.

Depois da sessão:

- Garanta que as sessões de daily estejam agendadas.

### Daily

Antes da sessão:

- Garanta que as issues da iteração estejam atualizadas (comentários e campos personalizados).
- Reserve tempo suficiente para a sessão (de 10 a 20 minutos para iterações de duas semanas).

Durante a sessão:

- Acesse o GitHub Project.
- Selecione a visão de quadro.
- Revise cada issue da release da direita para a esquerda (fluxo de valor) e de cima para baixo (prioridade).
- Peça uma atualização.
- Se a issue estiver bloqueada:
  - Discuta o bloqueio.
  - Se o bloqueio puder ser resolvido em um ou dois minutos, resolva-o.
  - Caso contrário, agende uma reunião para resolvê-lo e prossiga com a daily.
- Pergunte sobre a confiança na estimativa.
- Atualize a issue, se necessário (comentários e prioridade).

Depois da sessão:

- Garanta que as issues continuem atualizadas (comentários e campos personalizados).
- Garanta que o backlog seja refinado (mantenha apenas issues relevantes e revise títulos, descrições e campos personalizados).

### Review

Antes da sessão:

- Reserve tempo suficiente para a sessão (duas horas para releases de duas semanas).

Durante a sessão:

- Acesse o GitHub Project.
- Selecione a visão de quadro.
- Revise cada issue concluída:
- Leia o contexto, o objetivo e o DOD da issue.
- Peça ao responsável que faça uma demonstração.
- Discuta o resultado.
- Discuta melhorias no sistema de trabalho:
  - Peça a cada pessoa uma mudança que possa melhorar o sistema de trabalho.
  - Discuta as sugestões.
  - Crie issues para as alterações aprovadas em conjunto.

Depois da sessão:

- Garanta que o planejamento da próxima iteração esteja agendado.

### Apêndice

#### Visões

- Backlog: útil para visualizar todo o trabalho que precisa ser feito, principalmente na planning.
- Board: útil para visualizar o trabalho em progresso, principalmente na daily.
- Roadmap: útil para visualizar o trabalho na linha do tempo.

#### Campos

- Kind: tipo do trabalho:
  - Funcionalidade.
  - Defeito.
  - Tarefa.
  - Débito.
- Priority: prioridade do trabalho:
  - Urgente.
  - Alta.
  - Média.
  - Baixa.
- Order: ordem do trabalho na mesma prioridade.
- Iteration: iteração do trabalho.

#### Fluxo

Fluxo padrão:

- Backlog: trabalho que deve ser feito.
- WIP: trabalho em progresso.
- Done: trabalho feito.

Fluxo alternativo:

- Backlog: trabalho que deve ser feito.
- In Planning: trabalho em planejamento.
- In Design: trabalho em design.
- In Development: trabalho em desenvolvimento.
- In Delivery: trabalho em revisão/entrega.
- Done: trabalho feito.

#### DOD

Usar DOD para alinhar como uma issue pode ser considerada pronta entre as pessoas e agentes. O DOD é importante para aumentar a qualidade da entrega. O DOD deve ser definido como uma lista de verificação simples, onde cada item representa uma condição que precisa ser validada. Quando todos os itens estiverem validados, a issue pode ser considerada pronta.

#### Estimativas

#### Issue

Modelo de issue:

```markdown
Contexto:

- Fato relacionado ao trabalho.
- Limitação relacionada ao trabalho.

Objetivo:

Declaração do objetivo do trabalho.

DOD:

- [ ] Algo que deve ser validado para considerar o trabalho pronto.
- [ ] Validações funcionais (testes E2E, documentacão, etc),
- [ ] Validações não funcionais (segurança, performance, etc).
```
