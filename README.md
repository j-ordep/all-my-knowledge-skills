# All My Knowledge Skills

Skills e exemplos genéricos para transformar estudos e problemas resolvidos em conhecimento fácil de encontrar, lembrar e aplicar. Markdown é a fonte principal; HTML apresenta o mesmo conteúdo quando solicitado.

## Exemplos para começar

| Exemplo | Markdown | HTML |
| --- | --- | --- |
| Relatório de um tema | [Ver tópicos sugeridos](relatorios/0001-exemplo/README.md) | [Ver apresentação](relatorios/0001-exemplo/index.html) |
| Conceito reutilizável | [Ver nota de exemplo](conhecimento/0001-exemplo.md) | — |

Os exemplos mostram onde cada informação pode ficar. O agente pode escolher títulos, juntar, remover ou acrescentar seções e adaptar a apresentação ao assunto. Use apenas o que ajudar a leitura, preservando resumo, fontes e limites da verificação.

## Como usar

Abra a cópia destinada à sua base no agente e indique o material e o destino do registro. O [AGENTS.md](AGENTS.md) reúne as convenções e encaminha cada pedido à skill pertinente.

> Leia `skills/capturar-aprendizado/SKILL.md` e registre o que aprendi neste projeto. Adapte os tópicos do exemplo ao caso e gere HTML se eu pedir.

> Leia `skills/revisar-semana/SKILL.md` e revise meu trabalho dos últimos sete dias, usando as fontes disponíveis e perguntando quando faltar a relação entre tarefa e código.

Este catálogo mantém skills e exemplos genéricos. Use uma cópia independente e privada para seus registros pessoais ou de trabalho. Os exemplos não representam estudos realizados, resultados medidos ou domínio de alguém.

## Organização dos arquivos

```text
all-my-knowledge-skills/
├── AGENTS.md
├── README.md
├── relatorios/
│   └── 0001-exemplo/
│       ├── README.md
│       └── index.html
├── conhecimento/
│   └── 0001-exemplo.md
└── skills/
    ├── capturar-aprendizado/SKILL.md
    ├── revisar-semana/SKILL.md
    ├── planejar-aprendizado/SKILL.md
    ├── revisar-conhecimento/SKILL.md
    └── gerar-relatorio/SKILL.md
```

- **Relatórios:** contexto, experiência, aprendizado, fontes e próximos passos ficam juntos no tema. HTML, quando houver, fica ao lado do Markdown e acompanha suas atualizações.
- **Conhecimento:** crie uma nota separada apenas quando o conceito merecer reutilização. Conecte as notas por links, sem duplicar explicações.

Na base de uso, numere os itens conforme o AGENTS.md e mantenha neste README um índice dos estudos. No Obsidian, abra a pasta como um vault; os links também funcionam no GitHub e em editores de Markdown.

## Skills disponíveis

| Skill | Para quê |
| --- | --- |
| [Capturar aprendizado](skills/capturar-aprendizado/SKILL.md) | Guardar um estudo, descoberta ou problema resolvido |
| [Revisar semana](skills/revisar-semana/SKILL.md) | Relacionar trabalho, contribuição, impacto e aprendizado |
| [Planejar aprendizado](skills/planejar-aprendizado/SKILL.md) | Escolher próximos estudos a partir de objetivos e lacunas |
| [Revisar conhecimento](skills/revisar-conhecimento/SKILL.md) | Praticar explicações e exercícios, uma pergunta por vez |
| [Gerar relatório](skills/gerar-relatorio/SKILL.md) | Apresentar o conteúdo em HTML local |

O catálogo em `skills/` pode ser lido pelo agente a partir do AGENTS.md ou de um pedido explícito. As skills usam os acessos disponíveis na sessão; não configuram conectores, publicações ou agendamentos por conta própria.

## Estilo e evidências

Texto claro, conciso e pouco formal. Analogias e código entram quando ajudam. Separe o que foi observado, relatado, interpretado ou usado como exemplo; registre fontes e diga o que foi efetivamente verificado. As seções dos exemplos são sugestões, e o agente deve adequar o nível de detalhe ao pedido.
