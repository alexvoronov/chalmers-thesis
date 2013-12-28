Thesis template for PhD/Lic thesis at Chalmers
----------------------------------------------

This is a LaTeX template for a PhD/Lic thesis follows Chalmers [recommendations on thesis layout](https://www.chalmers.se/insidan/EN/education-research/doctoral-student/phd-degree-examination/layout-thesis).

A PhD thesis in Sweden is either a _monograph_, which is a coherent scientific work, or a _compilation_, which is a collection of papers tied together by a short summary (20-50 pages) called _kappa_. Advantage of a monograph is its coherence. Compilation, on the other hand, usually requires less work. This template shows how to typeset a compilation thesis.


Files and folders
-----------------

- `main.tex` -- main file to compile
- `frontmatter/` -- cover, copyrights, abstract, abbreviations etc.
- `frontmatter/common-basic-info.tex` -- thesis author, year, etc.
- `kappa/body.tex` -- introductory chapters that tie together the appended papers
- `paper-...` -- the appended papers 
- `main-for-defence-announcement.tex` -- defence announcement flyer (printed separately)


Compiling
---------

Compilation is straightforward:

  pdflatex main
  biber main
  pdflatex main
  pdflatex main
  pdflatex main

Make sure that you have the latest versions of [Biber](http://biblatex-biber.sourceforge.net/) and LaTeX packages.



Disclaimer
----------
THIS SOFTWARE IS PROVIDED ``AS IS'' AND WITHOUT ANY EXPRESS OR
IMPLIED WARRANTIES, INCLUDING, WITHOUT LIMITATION, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.
