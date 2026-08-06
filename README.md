# copy-lp-ratos

Escreve a **copy e a estrutura de seções de uma landing page**, adaptando ao tipo de página. Além da **big idea**, ela trabalha o **conceito criativo** (a metáfora/storytelling que dá alma à página) e, antes de escrever, propõe opções pra você escolher (3 big ideas + 3 conceitos criativos + avatar).

A fronteira dura: o **conceito criativo é metáfora e storytelling, nunca decisão de design**. Ele traz "os ratos carregam as pastas por um labirinto até organizar", não "grid amarelo com ratos". Layout, cor e componente ficam abertos pra etapa seguinte (referências + design system do aluno).

Faz parte da trilha **Sites e landing pages com IA**, da **Ratos de IA** (DobraLabs).

## Tipos de página que ela cobre

| Tipo | Pra que serve |
|---|---|
| **Venda** | Vende um produto ou serviço com preço e checkout (curso, mentoria, pacote) |
| **Captura de lead** | Troca contato por um material, aula, lista de espera ou orçamento |
| **Serviço / negócio local** | Apresenta um serviço e leva ao contato (clínica, restaurante, prestador) |
| **Institucional** | Apresenta a empresa ou a pessoa, sem venda direta |

Cada tipo tem uma estrutura de seções própria. Uma página que vende um curso não tem a mesma anatomia de uma que capta email ou de uma que apresenta uma clínica.

## O que faz

- Identifica o **tipo de página** e adapta toda a estrutura a ele.
- Conduz uma **entrevista rápida**: o que é, pra quem, transformação, prova, objeções, qual a única ação da página (mais as perguntas específicas do tipo).
- Propõe **3 big ideas + 3 conceitos criativos + avatar** pra você escolher (com uma combinação recomendada), antes de escrever tudo. Escolher é mais fácil que inventar.
- Define a direção escolhida e usa o **conceito criativo como fio narrativo** da copy: a metáfora costura nomes de seção, transições e chamadas.
- Entrega a página **seção por seção**, cada uma com o princípio de conversão que aplica, pra você aprender o porquê e não só receber o texto.
- Abre o doc com um **brief de conceito criativo (aberto)**, pra a etapa de design não começar fria, sem fixar nenhuma decisão visual.
- Tom **honesto**: constrói a crença pela lógica e pela prova, sem hype vazio. Onde falta prova real, usa placeholder realista listado em "Trocar antes de publicar", em vez de inventar prova de verdade.

## O que ela NÃO faz

- Não monta o HTML nem o design da página (isso é outra etapa).
- **Não fixa decisão de design** — o conceito criativo é metáfora/storytelling, nunca layout, cor, grid ou componente.
- Não escreve copy de anúncio nem de email.

## Instalação

```bash
cp -r copy-lp-ratos ~/.claude/skills/
```

Ou cole o link deste repositório no seu Claude Code e peça pra instalar.

## Como usar

Chame `/copy-lp-ratos` (ou peça "escreve a copy da minha landing page") e responda a entrevista. No fim, você recebe a página inteira em markdown, com o brief de conceito no topo, variações de headline pra teste e as pendências de prova marcadas.

## Créditos

Feita pela DobraLabs / Ratos de IA. A doutrina de copy que ela aplica (em `references/doutrina-copy-lp.md`) foi destilada de fontes públicas de copywriting e CRO.
