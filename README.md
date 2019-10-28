
This repository contains literature on my master's level thesis, which is
about Distributed Web Crawling and Indexing. I will also start making
bi-weekly incremental updates about my progress on the work onto my site very soon.

https://rihbyne.github.io/blog/

You can use this latex code as a template to produce your thesis as well. Just run
the below command to compile the tex file to pdf.

```
pdflatex <thesis>.tex && bibtex <thesis> && pdflatex <thesis>.tex && pdflatex <thesis>.tex
```

Note that you only want to touch `thesis-template.tex` and `references.bib` to 
add your content, rest all other files are generated by tex engine and therefore
shouldn't be modified by hand.

insert pdf after a given page number
```
pdftk A=initialwriteup.pdf B=formalities/distributionlicense.pdf cat A1-3 B A4-end output output.pdf
```
