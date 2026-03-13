# Important packages
- Biber
- Hyperref

# Compilation
Run in order:
\
`pdflatex main.tex -o main.pdf`
\
`biber main`
\
`pdflatex main.tex -o main.pdf`
\
If _latexmk_ is installed then you can just run:
\
`latexmk`
\
or 
\
`latexmk -pdf` 
\
if you want to explicitly get a .pdf file. 
\
Clean up with
\
`latexmk -c`
\
where c is minus so its doesn't delete important _.pdf_, _.div_ or _.ps_ files.


# Readings

- [Manifold learning: what, how, and why](https://arxiv.org/pdf/2311.03757)
- [A Grassmann Manifold Handbook: Basic Geometry andComputational Aspects](https://arxiv.org/pdf/2011.13699)
- [Locality Preserving Projections for Grassmann manifold](https://arxiv.org/pdf/1704.08458)