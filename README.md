# DFO-science-report-LaTeX-template
A LaTeX template for science reports published by the Canadian department of Fisheries and Oceans (DFO)

# Reference
For full author instructions refer to the following publication,

Fisheries and Oceans Canada. Fisheries and Oceans Canada Library.
2019. Guide for the production of Fisheries and Oceans Canada science
report series. 2nd edition: v + 24 p.

which can be found here,

https://waves-vagues.dfo-mpo.gc.ca/Library/333125.pdf

# Cover page
Reports must use the Microsoft Word cover page template. However as they must be assembled as pdf documents for submission, the cover page can be generated from the Microsoft Word template and then included to the LaTeX document as a one page pdf. This is the only non-LateX step required to use this template. To edit your cover page,

* Open your report series cover page .doc file (under CoverMaterial/doc/) using Microsoft Word
* Enable modifications
* Edit title, authors, address and year information.
* Export as pdf document and save next to main.tex

# Report series
Choose the report series by un-commenting only one definition block in the preample of main.tex . Report series information an all pages and references will update automatically.

# Bibliographic information
Bibliographic information of the report should be entered in main.tex under the bibliographic information block. Information appearing multiple times in the front matter pages will then update without these pages
being edited.
