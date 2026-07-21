# copy-lp-ratos

Skill de Claude Code que escreve a **copy e a estrutura de seções de uma landing page**, adaptando ao tipo de página. Ela te entrevista, define a ideia central e o avatar, e entrega a página seção por seção, pronta pra colar num builder.

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
- Define a **big idea** (uma ideia central) e o **avatar**, e confirma com você antes de escrever tudo.
- Entrega a página **seção por seção**, cada uma com o princípio de conversão que aplica, pra você aprender o porquê e não só receber o texto.
- Tom **honesto**: constrói a crença pela lógica e pela prova, sem hype vazio. Marca `[FALTA PROVA]` onde falta prova real, em vez de inventar.

## O que ela NÃO faz

- Não monta o HTML nem o design da página (isso é outra etapa).
- Não escreve copy de anúncio nem de email.

## Instalação

```bash
cp -r copy-lp-ratos ~/.claude/skills/
```

Ou cole o link deste repositório no seu Claude Code e peça pra instalar.

## Como usar

Chame `/copy-lp-ratos` (ou peça "escreve a copy da minha landing page") e responda a entrevista. No fim, você recebe a página inteira em markdown, com variações de headline pra teste e as pendências de prova marcadas.

## Créditos

Feita pela DobraLabs / Ratos de IA. A doutrina de copy que ela aplica (em `references/doutrina-copy-lp.md`) foi destilada de fontes públicas de copywriting e CRO.
