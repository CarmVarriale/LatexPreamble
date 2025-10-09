# LatexPreamble

A LaTeX preamble to quickly add functionalities that I find useful in my scientific writing.

Most relevant utilities allow to:

- create acronyms that appear in a List of Acronyms
- create acronyms that do not appear in a List of Acronyms
- create symbols that appear in a List of Symbols, categorized by type (Roman, Greek, Subscripts and Superscripts)
- create modified symbols including over-bars, bold, nested subscripts and superscripts
- typeset commonly used maths operators and units
- typeset sub-figures and sub-tables

## How to use

1. Clone or download this repository into a `.preamble/` folder in the root directory of your LaTeX project.
2. Paste the following lines in your LaTeX document preamble:

```latex
\input{.preamble/fonts}
\input{.preamble/abbreviations}
\input{.preamble/maths}
\input{.preamble/colors}
\input{.preamble/figures-tables}
\input{.preamble/charts}
\input{.preamble/cross-references}
\input{.preamble/glossaries}
```

The order in which the preamble instructions are executed is important.

## Contributing

Feel free to open an issue or a pull request if you want to suggest improvements or report bugs.

You are welcome to work on any open issue and submit a Pull Request to make this repository (or its submdodules) better for future users.

## License

This project is licensed under the BSD 3-Clause License - see the [LICENSE](LICENSE) file for details.
