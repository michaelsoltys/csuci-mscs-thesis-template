This page is mainted by Michael Soltys, Chair of Computer Science at
CSU Channel Islands, and director of the Computer Science masters
program. See:

http://www.msoltys.com

### Introduction

This repository contains the files required for a proper LaTeX
submission of an MSCS thesis. Follow the instructions in
```
EU MS Thesis Submission Procedure.pdf
```
for the technicalities of a submission to EU. See the Computer Science
Web site for general information about MSCS:

https://compsci.csuci.edu/degrees/mscs/index.htm

The files `ThesisTemplate.*` contain the templates for writing the
thesis in LaTeX in the required format (double spaced, proper margins,
cover pages, etc.).

### Required files for Thesis Submission to the Broome Library

- Page 1: Cover Page
- Page 2: Copyright Page
- Page 3: Signature Page
- Page 4: Distribution License Page
- Page 5+: Thesis Pages

### Using Thesis Template

1. Make sure to replace Names, Titles, and Dates with real values
2. References should be put in `references.bib` file in bibtex format
3. Building is done with pdflatex and bibtex with the following commands
```
pdflatex <thesis>.tex && bibtex <thesis> && pdflatex <thesis>.tex && pdflatex <thesis>.tex
```

Best of Luck!
