# UGA thesis tempalte for `pandoc`

This folder includes all the required files for a beamer presentation creation in [University Grenoble Alpes](https://univ-grenoble-alpes.fr) and [Grenoble INP](https://grenoble-inp.fr) styles.
The template in a pure LaTeX format is available at [http://www.kamick.org](http://www.kamick.org).

Currently the template requires usage of LaTeX commands directly within the `.rmd` file, which reduces the advantages of markdown. 
The is an ongoing work on template migration to the exclusive `markdown` syntax.

The folder structure is as follows:

```
.
├── backgrounds
│   ├── background_gscop-gael.png
│   └── background_gscop.png
├── bibliography
│   └── bibliography.bib
├── example.pdf
├── example.rmd
├── LICENSE
├── README.md
└── templates
    └── gscopposter.tex
```

The `templates` and `backgrounds` folders should be left as is due to hardcoded paths in the proposed style.
