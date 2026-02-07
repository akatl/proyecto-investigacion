# Important packages
- Biber
- Hyperref

# Compilation
Run in order:
`pdflatex main.tex -o main.pdf`
`biber main`
`pdflatex main.tex -o main.pdf`

If _latexmk_ is installed then you can just run:
`latexmk`
or 
`latexmk -pdf` 
if you want to explicitly want a .pdf file. 