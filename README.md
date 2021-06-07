#  Supreme Court Amicus Briefs in LaTeX

This project [adapts this Overleaf template](https://www.overleaf.com/latex/templates/legal-briefs-and-automatic-legal-citations-with-lawtex/mftmdfccfnyr), in turn based on LawTeX, to the page and formatting requirements of hte United States Supreme Court, and makes use of XeLaTeX rather than the older PDFLaTeX.

## Guide to the Features

The formatting has been updated from the original to meet the [SCOTUS specifications](https://www.law.cornell.edu/rules/supct/rule_33), specifically:
 - Typeset in Century family (accomplished with use of TeX Gyre Schola X)
- paper that is 6 1⁄8 by 9 1⁄4 inches in size (accomplished using the `crop` package and `geometry`)
- the text field, including footnotes, should be approximately 4 1⁄8 by 7 1⁄8 inches (accopmlished with same)
-  12-point type with 2-point or more leading between lines (accomplished using the `leading` package)

# Using the document class

The main variables can be edited in `variables.tex`, while `brief-content.tex` is where to put your argument.  The citations are done using the existing LawTeX implementation of BlueBook.  Frankly, I would have much preferred to use a version of BibLaTeX, having been spoiled by how excellent BibLaTeX-OSCOLA is, but LawTeX works for now.
