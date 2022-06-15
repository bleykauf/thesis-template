# Thesis template

Uses XeLaTeX, TeX Live and `xelatexmk`. Made for use in VS Code with the LaTeX Workshop extension.

## Installation

### Git repository
* Fork this repository
* Initialize Git Large File Storage (LFS) by running `git lfs install` (this is for storing binary files, images, PDFs, etc.). Additional files can be specified in `.gitattributes`


### LaTeX and VS Code
* Install TeX Live
* Install VS Code and the LaTeX Workshop extension.
* Open the `thesis-template.code-workspace` in VS Code (maybe rename this file)
* Build the PDF from the TeX menu on the left-hand side. This package used `xelatexmk` that should take care of the proper amount of runs to get everything working.
* Settings for LaTeX Workshop are stored in the `.code-workspace` file.

### Bibliography
I recommend Zotero for organizing the bibliography as it works much better with biblatex than other solutions I tried. Make sure to install the extension Better BibTeX and use "Better BibLaTeX" when exporting the library (not "Better BibTeX"). Tick the "Keep updated" box to automatically sync the library.

## Notes
### Color map
The standard color map of Matplotlib for usage in Inkscape can be found in the graphics subfolder.

### Spell and grammar checking
The LTeX extension for VS Code seems to work pretty well.

### `latexmkrc`
To make glossaries work, a `latexmkrc` configuration file is used. See also https://tex.stackexchange.com/questions/1226/how-to-make-latexmk-use-makeglossaries.

### `cleverref`
Note that when using `\Cref` the prefix will not be abbreviated. This is expected behavior since in English the first word of a sentence should not be abbreviated according to the documentation.

### `pst-optexp`
This package might be useful for drawing optical setups: https://ctan.org/pkg/pst-optexp?lang=en