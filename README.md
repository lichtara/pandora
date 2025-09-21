# Campo Informacional e Comunidades Sistêmicas

Projeto LaTeX para o artigo "Campo Informacional e Comunidades Sistêmicas: entrelaçamento de consciência, informação e organização coletiva".

## Estrutura

- `main.tex` – arquivo principal do artigo.
- `resumo.tex`, `introducao.tex`, `referencial_teorico.tex`, `metodologia.tex`, `resultados_esperados.tex`, `discussao.tex`, `conclusao.tex` – seções do manuscrito.
- `referencias.bib` – base bibliográfica no formato BibTeX.
- `dna_tecnologico_espiritual.md` – material complementar ainda não integrado ao texto principal.

## Como compilar

Instale uma distribuição LaTeX completa (TeX Live ou MikTeX) e execute:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

O PDF será gerado como `main.pdf`.
