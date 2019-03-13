# SSE Dissertation Template

Before you do anything else, make sure you can build the template. You need:

* A recent version of LaTeX, [MacTeX](https://www.tug.org/mactex/) for Mac or [MikTeX](https://miktex.org/) for Windows.
* Requires fonts Avant Garde and Garamond, see instructions below.
* When you have everything installed, try building `dissertation.tex` preferably using [LatexMK](https://mg.readthedocs.io/latexmk.html). Make sure that the bibliography is being parsed correctly. If you are using TeXStudio or a similar program, you might want to change your default compiler to `LaTeXMk`.

## Installing Garamondx

According to SSE guidelines, text should be in the font Garamond and headlines in Century Gothic. Century Gothic is not easily available in LaTeX (if one does not use XeLaTeX and system fonts) but the [similar](http://www.identifont.com/differences?first=Avant+Garde+&second=Century+Gothic&q=Go) Avant Garde is, using the `Avant` package. There exists a Garamond package as well, but for legal reasons it cannot be supplied with the LaTeX distribution. Instead, one needs to use the `getnonfreefonts` program to install it, following [these instructions](https://tug.org/fonts/getnonfreefonts/).

### Mac

* Open the Terminal (can be found in Applications)
* Write: `curl --remote-name https://www.tug.org/fonts/getnonfreefonts/install-getnonfreefonts` and press enter.
* Write: `sudo texlua install-getnonfreefonts`, press enter and make sure the program was installed correctly.
* If everything looks good, write: `sudo getnonfreefonts --sys garamondx` and press enter. The font should now be installed.
