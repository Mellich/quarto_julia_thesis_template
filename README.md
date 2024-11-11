# Quarto Thesis Template

This thesis project is using Quarto to generate a Website and PDF book from the same source files. It comes with a ready-to-use theme for the Paderborn University based on this [Eisvogel pandoc template](https://github.com/Wandmalfarbe/pandoc-latex-template).

The template was adjusted and fit into partials supported by Quarto.

## Build Dependencies

- Quarto 1.4+
- Quarto Extensions:
    - [acronyms](https://github.com/Mellich/acronyms)
- Julia Programming Language
- Latex Installation (also possible to use tinylatex provided by Quarto)

- Install quarto
- install the required Quarto extensions by executing the following command in the project root directory: `quarto add mellich/acronyms@master`
- Install Julia
- Install IJulia and the Julia Jupyter kernel: `IJulia.installkernel("julia")`

## How to Build

Run 

    quarto render

in the root directory of the project to build the website and PDF.
Both are located in the *_output* directory after execution.
