# copy-lp-ratos

Skill de Claude Code que escreve a **copy e a estrutura de uma landing page de venda de infoproduto** de alta conversão, com tom honesto. Ela te entrevista, define a ideia central e o avatar, e entrega a página seção por seção, pronta pra colar num builder.

Faz parte da trilha **Sites e landing pages com IA**, da **Ratos de IA** (DobraLabs).

## O que faz

- Conduz uma entrevista rápida: produto, transformação, público, oferta, preço, prova, garantia, objeções.
- Define a **big idea** (uma ideia central) e o **avatar**, e confirma com você antes de escrever tudo.
- Entrega a página **seção por seção**: above the fold, benefícios, prova, oferta, preço ancorado, garantia, objeções/FAQ e CTA, cada uma com o princípio de conversão que aplica.
- Tom **honesto**: constrói a crença pela lógica e pela prova, sem hype vazio. Marca `[FALTA PROVA]` onde falta prova real, em vez de inventar.

## O que ela NÃO faz

- Não monta o HTML/design da página (isso é outra etapa).
- Não escreve landing de captura de lead simples nem página institucional. É pra página que **vende** um infoproduto.

## Instalação

```bash
cp -r copy-lp-ratos ~/.claude/skills/
```

Ou cole o link deste repositório no seu Claude Code e peça pra instalar.

## Como usar

Chame `/copy-lp-ratos` (ou peça "escreve a copy da minha landing page") e responda a entrevista. No fim, você recebe a página inteira em markdown, com variações de headline pra teste e as pendências de prova marcadas.

## Créditos

Feita pela DobraLabs / Ratos de IA. A doutrina de copy que ela aplica (em `references/doutrina-copy-lp.md`) foi destilada de fontes públicas de copywriting e CRO.
