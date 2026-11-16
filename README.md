<!--
COMO USAR ESTE MODELO
1. Substitua tudo que está entre [colchetes].
2. Preencha também o CITATION.cff (autores, título, palavras-chave).
3. Escolha a licença: LICENSE (MIT) vale para código; LICENSE-docs.md (CC BY 4.0) para textos, protocolos e figuras. Apague a que não se aplicar.
4. Em "About" (engrenagem na página do repositório), adicione os topics de tipo, pessoa e financiamento — veja CONTRIBUTING da organização.
5. Apague este bloco de comentário.
-->

# [Título do projeto]

[Uma ou duas frases: o que este repositório contém e para que serve.]

**Tipo:** [protocolo | pipeline | análise | dados | ensino]
**Status:** [em desenvolvimento | estável | arquivado]

## Autores

| Nome | Função | ORCID |
| --- | --- | --- |
| [Nome Sobrenome] | [autor(a) principal — mestrado/doutorado/IC/pós-doc] | [0000-0000-0000-0000] |
| Gabriela Procópio Camacho | Orientação / coordenação | [0000-0000-0000-0000] |

Laboratório de Hymenoptera — Museu de Zoologia da Universidade de São Paulo (MZUSP).

## Financiamento

<!-- Use o nome completo do financiador e o número do processo, como exigido pelas regras de cada agência. Inclua o projeto do laboratório e as bolsas individuais. -->

- Fundação de Amparo à Pesquisa do Estado de São Paulo (FAPESP), processo nº [AAAA/NNNNN-N] — [modalidade, ex.: bolsa de mestrado].
- [Coordenação de Aperfeiçoamento de Pessoal de Nível Superior (CAPES) — Código de Financiamento 001.]
- [Conselho Nacional de Desenvolvimento Científico e Tecnológico (CNPq), processo nº [número].]

As opiniões, hipóteses e conclusões ou recomendações expressas neste material são de responsabilidade dos autores e não necessariamente refletem a visão da FAPESP.

## Estrutura

```
.
├── scripts/      # código (R, Python, shell…)
├── dados/        # dados pequenos ou metadados; dados brutos ficam em repositório público (SRA, Zenodo)
├── resultados/   # tabelas e figuras geradas pelos scripts
└── docs/         # protocolos, notas e documentação
```

## Como usar

[Requisitos (programas e versões), instalação e um exemplo mínimo de execução.]

## Dados

[Onde estão os dados brutos (ex.: SRA BioProject PRJNAxxxxxx, Zenodo DOI) e como obtê-los. Não versionar arquivos > 50 MB nem dados sensíveis, como coordenadas de espécies ameaçadas.]

## Como citar

Veja o botão **"Cite this repository"** (gerado a partir do `CITATION.cff`). Após o primeiro *release*, inclua aqui o DOI do Zenodo:

> [Autores] ([ano]). [Título] (versão [x.y]). Zenodo. https://doi.org/[DOI]

## Licença

[Código: MIT (ver `LICENSE`). Textos, protocolos e figuras: CC BY 4.0 (ver `LICENSE-docs.md`).]
