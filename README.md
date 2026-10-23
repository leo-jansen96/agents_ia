# Agentes de IA

Repositório para centralizar agentes de IA criados para apoiar diferentes situações de desenvolvimento de software. Cada agente reúne instruções e responsabilidades específicas para orientar tarefas como arquitetura de APIs e engenharia de software.

## Agentes disponíveis

| Agente | Categoria | Descrição |
| --- | --- | --- |
| `api-architect` | Arquitetura | Apoia o desenho de APIs e integrações, considerando contratos, resiliência, segurança e observabilidade. |
| `principal-software-engineer` | Engenharia | Oferece orientação técnica em arquitetura, implementação, revisão de código, qualidade e evolução de sistemas. |

## Organização

```text
.
├── architect/
│   └── api-architect.agent.md
├── engeneer/
│   └── principal-software-engineer.agent.md
└── README.md
```

Cada arquivo `.agent.md` define um agente, incluindo seu nome, descrição, ferramentas disponíveis e instruções de atuação. As pastas agrupam os agentes por área.

## Como usar

Para usar um agente em outro projeto com o GitHub Copilot no VS Code:

1. Escolha o arquivo `.agent.md` adequado à tarefa.
2. Copie-o para a pasta `.github/agents/` do projeto em que deseja trabalhar.
3. Abra o projeto no VS Code e selecione o agente no seletor de agentes do Copilot Chat.

Consulte as instruções do agente escolhido: alguns definem etapas ou informações que precisam ser fornecidas antes de começar.

## Como contribuir

- Crie um arquivo `.agent.md` para cada novo agente.
- Inclua no cabeçalho as informações necessárias para identificá-lo e descreva claramente sua missão, escopo e modo de atuação.
- Salve o arquivo na pasta correspondente à sua área; crie uma nova pasta quando necessário.
- Atualize a tabela de agentes disponíveis neste README.
