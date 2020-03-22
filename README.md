# SSE Dissertation Template

Before you do anything else, make sure you can build the template. You need a recent version of LaTeX, [MacTeX](https://www.tug.org/mactex/) for Mac or [MikTeX](https://miktex.org/) for Windows.

When you have everything installed, try building `dissertation.tex` preferably using [LatexMK](https://mg.readthedocs.io/latexmk.html). Make sure that the bibliography is being parsed correctly. If you are using TeXStudio or a similar program, you might want to change your default compiler to `LaTeXMk`.

Once you have managed to build `dissertation.tex`, consider reading through `SSEthesisPreamble.sty` and `SSEthesisLayout.sty` as well as the `.tex` files in the chapters folder to get a sense of what is going on under the hood.

## Regarding fonts

According to SSE guidelines, text should be in the font Garamond and headlines in Century Gothic. Century Gothic is not easily available in LaTeX (if one does not use XeLaTeX and system fonts) but the [similar](http://www.identifont.com/differences?first=Avant+Garde+&second=Century+Gothic&q=Go) Avant Garde is, using the `Avant` package. Instead of Garamond, we use the `ebgaramond-maths` package to get the [similar](http://www.identifont.com/differences?first=Garamond&second=EB+Garamond&q=Go) EB Garamond.
