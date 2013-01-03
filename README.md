CPPReport
=========

Software
---------
If you are a Mac user please install [Bibdesk] [bibdesk], it will make your referecning lives so much easier.
Load `references.bib` into it and add new references. 
When done save and exit.

Compliation
-----------
In order to compile with the bibliography you must run pdflatex once then bibtex then pdflatex twice as follows:
    pdflatex report.tex
    bibtex
    pdflatex report.tex
    pdflatex report.tex


 [bibdesk]: http://bibdesk.sourceforge.net/  "Bibdesk Site"
