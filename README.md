# Programming cheatsheets
These community driven cheatsheets inspired by <https://learnxinyminutes.com/> 
are meant to be quick reference guide for people having problems with 
remembering the syntax of language.
Therefore they are totally unsuitable for learners with no prior knowledge.

*Pull requests are welcome.*

## Languages
1. Haskell,
2. Python,
3. Bash (and most popular CLI tools).

## Requirements
* *pdflatex*
* the following LaTeX packages: *Alegreya*, *amssymb*, *color*, *enumitem*, *fancyhdr*, *fontenc*, *geometry*, *hyperref*, *inputenc*, *lastpage*, *minted*, *multicol*, *parskip*, *textcomp*, *titlesec*, *xcolor* (each of them is included in vanilla TeX Live)
* Pygments from http://pygments.org/ (`pip install Pygments`)

## Compilation guide
To generate a pdf file, just execute 
`pdflatex -shell-escape [language-name].tex` in a proper directory.
