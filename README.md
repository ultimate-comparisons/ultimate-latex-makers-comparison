# Ultimate Tex Makers Comparison

[![Build 
Status](https://travis-ci.org/ultimate-comparisons/ultimate-deployment-tool-comparison.svg?branch=master)](https://travis-ci.org/ultimate-comparisons/ultimate-deployment-tool-comparison)

This is an ultimate comparison of tex makers.

## Test it
1. Install [node.js](https://nodejs.org/en/)
2. Intall [Java JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
3. Install [pandoc](http://pandoc.org/installing.html) (Version 1.17.2) [pandoc-citeproc](https://hackage.haskell.org/package/pandoc-citeproc)
        
        wget https://github.com/jgm/pandoc/releases/download/1.17.2/pandoc-1.17.2-1-amd64.deb
        sudo dpkg -i pandoc-1.17.2-1-amd64.deb
        
4. Update npm (sudo): `npm install -g npm`
5. Test dependencies:

        java -version
        npm -version

6. `npm install`
7. `npm start` (starts the web page)
8. [Setup automatic deployment of `www` directory using Travis CI](https://github.com/ultimate-comparisons/ultimate-comparison-BASE/wiki/Build-and-deploy-project-with-Travis-CI)


## Ultimate-tex-makers-Comparison Element Specification
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

The code is licensed under [MIT], the content (located at `comparison-elements`) under [CC-BY-SA-4.0].

  [MIT]: https://opensource.org/licenses/MIT
  [CC-BY-SA-4.0]: http://creativecommons.org/licenses/by-sa/4.0/
