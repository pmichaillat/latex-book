# Minimalist LaTeX Template for Academic Books

This repository contains a [LaTeX](https://github.com/latex3/latex2e) template to create an academic book. The template follows typographical best practices and has a minimalist design. It is well suited for research monographs and lecture notes. It is designed so books are comfortable to read and easy to scan, both in print and on screen.

## Documentation

The template is documented at https://pascalmichaillat.org/g/.

## Illustration

+ The book produced by the template can be viewed at https://pascalmichaillat.org/g.pdf.

## Usage

+ Clone the repository to your local machine.
+ Edit the main file `book.tex` to set the title, subtitle, author, and date, and to add or remove parts and chapters.
+ Edit the chapter files (`chapter1.tex`, `chapter2.tex`, …), appendix files (`appendixA.tex`, `appendixB.tex`, …), `preface.tex`, and `acknowledgements.tex` to replace the boilerplate with your content.
+ Replace the figures in the PDF file `figures.pdf` with the figures to be included in your book (one figure per page).
+ Replace the references in the BibTeX file `book.bib` with the references to be included in your book.
+ Compile `book.tex` with pdfTeX. This will generate a PDF file of your book named `book.pdf`.
+ To build the index, run makeindex (e.g. `makeindex book`) after the first pdfTeX run, then run pdfTeX again.

A few files in the repository are required to use the book template but do not need to be modified. These files must remain in the same folder as `book.tex`:

+ The LaTeX style file `book.sty` formats the book.
+ The BibTeX style file `book.bst` formats the bibliography.

A few files in the repository are not required to use the book template but are useful for other purposes:

+ The file `book.pdf` illustrates the output of the template. It will be overwritten when `book.tex` is compiled.

## Software

+ The template was developed with TeX Live 2025 on macOS.
+ Other LaTeX distributions and operating systems may require minor adjustments. Please report any issues to help improve compatibility.

## License

This repository is licensed under the [MIT License](LICENSE.md).

## Real-world implementations

- [A Theory of Slack](https://pascalmichaillat.org/18/) – research monograph typeset with this book template.

## Related resources

- [latex-paper](https://github.com/pmichaillat/latex-paper) – LaTeX template for academic papers; same typographic principles and a similar appearance as this book template.
- [latex-presentation](https://github.com/pmichaillat/latex-presentation) – LaTeX template for academic presentations following the same typographic principles.
- [latex-math](https://github.com/pmichaillat/latex-math) – LaTeX commands that simplify writing mathematical expressions. They can be used in combination with this book template.

This book template is part of a [minimalist design suite](https://pascalmichaillat.org/design/) for academic work (papers, books, CVs, slides, websites, figures, and math).
