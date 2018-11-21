# rmd-make
Simple continuous compilation of multi file R Markdown projects. Will automatically recompile whenever one of the files used to compile the document is changed.

## Installation
Add rmd-make to a folder in your path.

## Usage
Currently written to expect a main.rmd file and other helper files (.tex or .sty) in your working directory, with other .rmd files in a section folder.

All is needed then is to run `rmd-make` in the working directory and the program will start the compilation process.
