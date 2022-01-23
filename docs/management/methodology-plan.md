# Plano metodológico

## Histórico de revisão

| Data       | Autor                                        | Modificações                          | Versão |
| ---------- | -------------------------------------------- | ------------------------------------- | ------ |
| 23/01/2022 | [Lieverton Santos](https://github.com/lievertom) | Adicionou o plano metodológico da equipe | 1.0    |

## Introdução

O presente documento visa descrever o plano metodológico utilizado no desenvolvimento do projeto na disciplina Desenvolvimento de Software, além de detalhar as técnicas e as metodologias aplicadas durante a elaboração do projeto. Utiliza-se de conceitos e práticas de múltiplas metodologias de modo a fazer uma adaptação ao contexto do trabalho.

## Metodologias

### Scrum

No Projeto, adota-se elementos metodológicos do scrum com encontros definidos no **[Plano de Comunicaçao](communication-plan.md)**, que utilizam como base o **[Quadro de Disponibilidade](availability-board.md)** para decisão dos horários. Utiliza-se principalmente os seguintes artefatos do Scrum [^2]:

- **_Sprint_**: período de tempo durante o qual é produzida uma versão incremental do produto. No projeto, uma _sprint_ possui 7 dias;
- **_Daily_**: acompanhamento diário do desenvolvimento da _sprint_ de modo a identificar o que foi feito, o que será feito e as dificuldades a fim de mitigar e prevenir riscos. No projeto, a _daily_ ocorre durante um período de 15 minutos;
- **Revisão de _sprint_**: reunião para validar o incremento do produto produzido na _sprint_ atual e adaptar o backlog do produto (se necessário).
- **Retrospectiva da _Sprint_**: momento da equipe inspecionar a si própria de modo a criar um plano para melhorias a serem aplicadas na próxima _sprint_.
- **Planejamento da _Sprint_**: com a colaboração de todos os papéis, define-se nessa etapa o trabalho a ser realizado na nova _sprint_.

### Kanban

Para monitorar o trabalho da equipe, utiliza-se a metodologia Kanban através da ferramenta [ZenHub](https://www.zenhub.com/) integrada às _issues_ do GitHub [^4]. Nesse sentido, definiu-se um fluxo de trabalho dividido em cinco etapas: _product backlog_, _sprint backlog_, _in progress_, _review/QA_ e _closed_.

- Ferramenta _ZenHub_ [^3]: auxilia na geração de relatórios de métricas do desenvolvimento das _sprints_.
- Categorização (labels): os artefatos presentes no fluxo do Kanban são categorizados com os rótulos.

### Extremming Programming (codificação)

No projeto, adotou-se metodologias do Extremming Programming (XP) no processo de desenvolvimento de código, como pode-se citar: programação em pares, refatorações (se aplicável), integração contínua e _feedback_ constante, tanto da parte interessada do projeto como da equipe de desenvolvimento e gerência[^2].

No projeto, adota-se os pares de programação conforme expertise dos membros relativo a tecnologia, metodologia, entregas, entre outros fatores, de modo a homogeneizar o conhecimento e melhorar as entregas no contexto da equipe.

## Comunicação

A comunicação da equipe ocorre conforme definido no **[Plano de Comunicaçao](communication-plan.md)**, ademais, o grupo realiza reuniões conforme definido no texto acima, além de interações para manter a equipe alinhada. 

## Referências

[^1]: BECK, Kent et al. Manifesto para Desenvolvimento Ágil de Software. 2001. Disponível em: https://agilemanifesto.org/iso/ptbr/manifesto.html. Acesso em: 23 mar. 2021.

[^2]: SCRUM e XP. 2013. Disponível em: https://www.desenvolvimentoagil.com.br/scrum/. Acesso em: 22 mar. 2021.

[^3]: RACASAN, Mariana. GitHub for Project Management - How to Organize and Track Your Agile Processes. Disponível em: https://blog.zenhub.com/how-to-use-github-agile-project-management/. Acesso em: 22 mar. 2021.

[^4]: FIRMINO, Júlia. O que é kanban e como ele pode ajudar na organização do trabalho. Disponível em: https://blog.runrun.it/o-que-e-kanban/. Acesso em: 23 mar. 2021.
