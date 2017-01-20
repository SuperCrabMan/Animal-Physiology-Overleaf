# 2017 Animal Physiology Overleaf Textbook Project

This is an attempt at generating a course-specific textbook as a crowd-source project in an Animal Physiology course at the University of Missouri.  It is based on a D&D 5e LaTeX template (see copyright information at the bottom of this file). The fonts chosen are included by default in TeX Live.

The template compiles with pdflatex.



### Installation of the core template

To install the original template, just clone the repo. From terminal:

```sh
$ git clone https://github.com/anoderay/DND-5e-LaTeX-Template.git 5e-template
$ cd 5e-template
$ pdflatex example.tex
```

If you don't have LaTeX installed, the following should help you out:
#### Ubuntu
```sh
sudo apt-get install texlive-full
```
#### Arch
```sh
sudo pacman -S texlive-bin texlive-core texlive-latexextra
```
It's a bit unclear exactly what subset of features this module needs. As a general rule, we'd recommend installing one of larger ones.

### Package Options
- bg-letter: Loads a letter-sized background-image
- bg-a4: Loads an A4-sized background-image
- bg-print: Loads a printer-friendly background-image (only decal at the bottom)
- bg-full: Loads the full background-image

Per default "bg-letter" and "bg-full" are loaded.



### Image Credit

 - Credit for the background image goes to http://lostandtaken.com/

### Version
0.5

### License
The MIT License (MIT)

Copyright (c) 2016 Evan Bergeron

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
