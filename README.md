# Marked Line-art Vectorization Thesis

LaTeX sources for the thesis on Semantically Meaningful Vectorization of Line Art in Drawn Animation.

Most graphics and tables (located in the `graphics` and `tables` directory, respectively) are dynamically generated and can be reproduced by following the instructions of the [main repository](https://github.com/nopperl/marked-lineart-vectorization).

## Requirements
CJK fonts have to be installed. For Debian:

`apt install texlive-lang-cjk`

## Build

To build the thesis:

```
pdflatex -shell-escape main.tex
bibtex main
makeglossaries main
pdflatex -shell-escape main.tex
pdflatex -shell-escape main.tex
```
