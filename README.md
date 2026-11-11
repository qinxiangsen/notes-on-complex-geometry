# Notes on Complex Geometry

Lecture notes by **Xiangsen Qin**, presented under the title *Lectures on Complex Geometry*. The notes are intended for advanced undergraduates and beginning graduate students and include a proposed two-semester teaching plan.

## Read or download

- [Compiled PDF](Notes_on_Complex_Geometry.pdf) (344 pages)
- [LaTeX source](Notes_on_Complex_Geometry.tex)

## Scope

The notes develop a route from local complex analysis to global complex geometry. Topics include complex manifolds and differential forms; holomorphic vector bundles and curvature; sheaf cohomology and the Dolbeault theorem; coherent sheaves and local algebra; elliptic regularity and Hodge theory; positive currents, singular weights, and multiplier ideals; heat kernels and holomorphic Morse inequalities; and applications to vanishing, projective embeddings, positivity, and Stein manifolds.

The text also includes worked examples, sixteen tutorials with solutions, further questions and student projects, and an appendix collecting background theorems. The teaching plan selects a core course from the larger body of material; several later topics are intended for seminars or further reading.

As explained in the preface, the principal references are Jean-Pierre Demailly's *Complex Analytic and Differential Geometry* and *Analytic Methods in Algebraic Geometry*. The notes also draw on material prepared for the seminar organized by Professor Fusheng Deng at the University of the Chinese Academy of Sciences in spring 2025. Further sources are cited in the text and bibliography.

## Build the PDF

Use a recent TeX Live or MiKTeX installation with pdfLaTeX and `latexmk`, including the packages listed in the source preamble. Then run:

```sh
latexmk -pdf -pdflatex="pdflatex -no-shell-escape -interaction=nonstopmode -halt-on-error %O %S" Notes_on_Complex_Geometry.tex
```

Alternatively, run `pdflatex -no-shell-escape Notes_on_Complex_Geometry.tex` repeatedly until cross-references and the table of contents are up to date. The bibliography is included in the source; no separate `.bib` file or BibTeX run is required.
