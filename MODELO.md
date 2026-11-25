# Modelo das publicações semanais

Toda segunda-feira saem **um artigo** (em `artigos/`) e **uma edição do boletim** (em `boletins/`), as duas com a data daquela segunda.

## Artigo — `artigos/AAAA-MM-DD-titulo-curto.md`

```
---
titulo: Título claro, com o assunto e o efeito prático
data: AAAA-MM-DD
autor: diogo-muniz
tema: um dos temas da lista abaixo
resumo: Duas frases (até 300 caracteres) dizendo o problema e o que o leitor leva do texto.
palavras_chave: [termo 1, termo 2, termo 3, termo 4]
---
Texto em Markdown, começando por um parágrafo de abertura (sem título).

## Seções com ##
...

## Referências
- Lei nº ..., art. ... — [link oficial](https://...)
```

**Temas** (use exatamente um destes): Contabilidade pública · Orçamento e planejamento · Responsabilidade fiscal · Prestação de contas e TCE-SP · Educação e FUNDEB · Saúde · Pessoal e previdência · Licitações e contratos · Receita e tributos · Transferências e convênios · Controle interno · Câmaras municipais.

**Regras de redação**
- Autoria de Diogo Muniz: texto técnico, direto, em português claro, para prefeitos, secretários, contadores, controladores e vereadores de municípios paulistas.
- 1.000 a 1.800 palavras. Abertura com o problema concreto; fechamento com o que fazer (lista de verificação ou passos).
- Toda afirmação normativa com a fonte: lei e artigo, comunicado do TCE-SP com número e data, manual da STN com edição. Nada de número, prazo ou dispositivo de memória: conferir na fonte oficial antes de escrever.
- Não copiar texto de concorrentes nem de notícias: o artigo é análise própria. Citação literal só de norma, curta e entre aspas.
- Não citar município cliente, nem dado que identifique cliente.
- Sem promessas de resultado e sem críticas a pessoas ou partidos.
- Variar os temas de uma semana para outra (não repetir o tema das 3 últimas semanas, salvo urgência).

## Boletim — `boletins/NNN.md`

```
---
numero: N
data: AAAA-MM-DD
titulo: frase curta com o destaque da semana
resumo: uma frase para o RSS e a busca
artigos: [AAAA-MM-DD-titulo-curto]
---
Parágrafo curto de abertura (2 a 3 frases).

## Radar da semana
- **Fonte — assunto.** O que mudou e o que o órgão deve fazer, em 1 a 3 frases próprias. [Fonte oficial](https://...)

## Agenda de obrigações
| Prazo | Obrigação | Base |
|---|---|---|
| dd/mm | ... | ... |

## Leitura recomendada
- [Título](https://...) — por que vale a leitura (fontes oficiais: TCE-SP, STN, FNDE, Ministério da Saúde, CNM).

## Fale com a Tema
Uma frase convidando a falar com a consultoria pelo [formulário do site](/#contato).
```

**Fontes da semana** (ler o que saiu desde a edição anterior):
- TCE-SP: https://www.tce.sp.gov.br/publicacoes e notícias/comunicados em https://www.tce.sp.gov.br
- STN / Fazenda: https://www.gov.br/fazenda/pt-br/assuntos/noticias/AAAA (ano corrente)
- Concorrentes (só para saber o que estão cobrindo, nunca para copiar): Metapública https://www.metapublica.com.br/informacoes · Alves https://alvesconsultoriaegestao.com.br/boletim.html · Gepam https://gepam.adm.br/noticias/ · Brigadeiro https://brigadeiroassessoria.com.br/revistas-brg-agn/

Radar: 3 a 6 itens. Agenda: prazos das próximas 2 a 6 semanas, cada um conferido na fonte.
