# Minimalist LaTeX Template for Academic Books

This repository contains a [LaTeX](https://github.com/latex3/latex2e) template to create an academic book. The template follows typographical best practices and has a minimalist design. It is well suited for research monographs, textbooks, and lecture notes. It is designed so books are comfortable to read and easy to scan, both in print and on screen.

## Documentation

The template is documented at https://pascalmichaillat.org/g/.

## Illustration

+ The book produced by the template can be viewed at https://pascalmichaillat.org/g.pdf.

## Usage

+ Clone the repository to your local machine.
+ Edit the main file `book.tex` to set the title, subtitle, author, and date, and to add or remove parts and chapters.
+ Edit the chapter files (`chapter1.tex`, `chapter2.tex`, and so on), appendix files (`appendixA.tex`, `appendixB.tex`, and so on), `preface.tex`, and `acknowledgements.tex` to replace the boilerplate with your content.
+ Replace the figures in the PDF file `figures.pdf` with the figures to be included in your book (one figure per page).
+ Replace the references in the BibTeX file `book.bib` with the references to be included in your book.
+ Compile `book.tex` with pdfTeX. This will generate a PDF file of your book named `book.pdf`.
+ To build the index, run `makeindex` after the first pdfTeX run, then run pdfTeX again.

A few files in the repository are required to use the book template but do not need to be modified. These files must remain in the same folder as `book.tex`:

+ The LaTeX style file `book.sty` formats the book.
+ The BibTeX style file `book.bst` formats the bibliography.

The file `book.pdf` illustrates the output of the template. It will be overwritten when `book.tex` is compiled. It is not required to use the book template.

## Software

+ The template is currently operational with TeX Live 2025 on macOS.
+ Other LaTeX distributions and operating systems may require minor adjustments. Please [report any issues](https://github.com/pmichaillat/latex-book/issues) to help improve compatibility.

## License

This repository is licensed under the [MIT License](LICENSE.md).

## Related resources

- [latex-paper](https://github.com/pmichaillat/latex-paper) – This LaTeX template produces academic papers that follow the same typographic principles as the book template.
- [latex-presentation](https://github.com/pmichaillat/latex-presentation) – This LaTeX template produces academic presentations that follow the same typographic principles as the book template.
- [latex-math](https://github.com/pmichaillat/latex-math) – These LaTeX commands simplify writing mathematical expressions. They can be used in combination with this book template.
- [matlab-figures](https://github.com/pmichaillat/matlab-figures) - This MATLAB template produces minimalist scientific figures that can be inserted into your book.