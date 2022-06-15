# Thesis template

Uses XeLaTeX, TeX Live and texmk. Made for use in VS Code with the LaTeX Workshop extension.

## Installation

### Git repository
* Fork this repository
* Initialize Git Large File Storage (LFS) by running `git lfs install` (this is for storing binary files, images, pdfs, etc.). Additional files can be specified in `.gitattributes`


### LaTeX and VS code
* Install TeX Live
* Install VS Code and the LaTeX Workshop extension.
* Open the `thesis-template.code-workspace` in VS Code (maybe rename this file)
* Build the pdf from the TeX menu on the left hand side. This package used `xelatexmk` that should take care of the proper amount of runs to get everything working.
* Settings for LaTeX Workshop are stored in the `.code-workspace` file.

### Bibliography
I recommend Zotero for organizing the bibligraphy as it works much better with biblatex than other solutions I tried. Make sure to install the extension Better Bibtex and use "Better BibLaTeX" when exporting the library (not "Better BibTeX"). Tick the "Keep updated" box to automatically sync the library.