# Ultimate LaTeX Makers Comparison

[![Build
Status](https://travis-ci.org/ultimate-comparisons/ultimate-deployment-tool-comparison.svg?branch=master)](https://travis-ci.org/ultimate-comparisons/ultimate-deployment-tool-comparison)

This is an ultimate comparison of LaTeX makers.
LaTeX makers are tools to automate the production of PDFs (oder DVIs) out of latex (`.tex`) files.

## Start the comparison

1. Install dependencies `npm install`
2. Start webserver `npm start`
3. Alternatively start development mode `npm run dev`

## Deploy comparison with github and travis

1. [Setup Git](https://help.github.com/articles/set-up-git/)
2. [Setup Travis](https://docs.travis-ci.com/user/getting-started/)
    - Changes to `.travis.yml` are not required
3. [Create a personal access token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/)
4. [Add the environment variable `GITHUB_TOKEN` to travis](https://docs.travis-ci.com/user/environment-variables#Defining-Variables-in-Repository-Settings)

## Ultimate-latex-makers-Comparison Element Specification

The code below shows a sample element.

    # AutoLaTeX - http://www.arakhne.org/autolatex/
    AutoLaTeX is a tool for managing small to large sized LaTeX documents. The user can easily perform all required steps to do such tasks as: preview the document, or produce a PDF
    file.

    ## Implementation
    - Perl
    - Python

    ## Date
    - 2014

    ## Supported Tools
    - latex
    - pdflatex
    - xelatex
    - lualatex
    - bibtex
    - biber
    - makeindex
    - makeglossaries
    - dvips

    ## Detect Changes for TeX
    - all

    ## Detect Changes for BibTeX
    - all

    ## Detect Changes for Images
    - all

    ## Automatic File Convertions to PS/PDF/PNG
    - asta
    - dia
    - dot
    - fig
    - ggb
    - gxl
    - odg
    - plot
    - svg
    - vsd
    - xmi

    ## Automatic File Convertions to TeX
    - c/c++
    - java
    - matlab
    - ml
    - perl
    - python
    - ruby
    - sql
    - Beamer

    ## Automatic File Convertions to PSTeX/PdfTeX
    - fig
    - plot
    - dia
    - svg
    - Beamer

    ## Export to Elsevier
    - Yes

    ## Editor Plugins
    - Gedit3
    - Gtk3
    - Sublime Text 3
    - Gedit2
    - Sublime Text 2
    - Gtk2

## License

The content is licensed under [CC0-1.0].

  [CC0-1.0]: https://creativecommons.org/publicdomain/zero/1.0/
