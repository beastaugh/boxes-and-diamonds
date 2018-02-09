# Boxes and Diamonds

![Book Cover](http://builds.openlogicproject.org/courses/boxes-and-diamonds/bd.png)\ 

A textbook for modal and other intensional logics based on the Open
Logic Project.

This repository/directory only contains the LaTeX files and
illustrations needed to typeset the textbook _Boxes and Diamonds_,
which in turn requires the _[Open Logic
Text](http://github.com/OpenLogicProject/OpenLogic/)_.

You can [download the
PDF](http://builds.openlogicproject.org/courses/boxes-and-diamonds/bd-screen.pdf)
of the most recent version from the [Open Logic builds
site](http://builds.openlogicproject.org/).

To install and compile:

- Download/install the _Open Logic Text_ from
  [GitHub](http://github.com/OpenLogicProject/OpenLogic/), including [photos](https://github.com/OpenLogicProject/photos) if you want those.
- Navigate to the subdirectory `courses/`
- Put the content of [this repository](https://github.com/rzach/boxes-and-diamonds) into a subdirectory of it, say
  `courses/boxes-and-diamonds`.

If you use `git`, this should do it:
```
# git clone https://github.com/OpenLogicProject/OpenLogic.git
# cd OpenLogic/courses
# git clone https://github.com/rzach/boxes-and-diamonds.git
```
Inside `courses/boxes-and-diamonds`, you can now compile:
```
# cd boxes-and-diamonds
# pdflatex bd-screen
```
or just `# make` if you have `latexmk` installed.

The file `bd-screen.tex` produces a color version of the text
with smaller margins for screen reading. `bd-print` produces a
black-and-white version designed for printing on Crown Quarto stock
(without cover).

Both versions load `bd.tex`, which contains the actual
material. It in turn includes other files, most of them from the
`OpenLogic` repository. So you won't get a complete book unless you
download into the right subdirectory of and compile from there.

[![Creative Commons License](http://mirrors.creativecommons.org/presskit/buttons/88x31/png/by.png)](http://creativecommons.org/licenses/by/4.0/) 

_[Boxes and Diamonds](https://github.com/rzach/phil379/)_ by [Richard
Zach](http://richardzach.org/) is licensed under a [Creative
Commons Attribution 4.0 International
License](http://creativecommons.org/licenses/by/4.0/).
