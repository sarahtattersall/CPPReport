CPPReport
=========

Compliation
-----------
Compliation should happen from the root directory and in order to compile with the bibliography you must run pdflatex once then bibtex then pdflatex twice as follows:
    pdflatex report.tex

    bibtex report

    pdflatex report.tex

    pdflatex report.tex



Structure
---------
Please structure the code in the following way:
* All sections to be made in directory made after their section name.
  E.g. Software Management section must be in software_management directory
* All subsections must be in seperate tex files in their section directory
  E.g. Team Management, Choosing Between Technologies etc all come under software_management
  and are included into the section
* All include and input paths must be relative to the root directory
