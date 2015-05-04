# A.J. Grant, trans., *Early Lives of Charlemagne by Eginhard and the Monk of St Gall* (London: Moring, 1905)

English translations of Einhard’s *Vita Karoli Magni*, as well as *De Carolo Magno*, traditionally ascribed to Notker Balbulus, with commentary. E-book available through [Project Gutenberg](http://www.gutenberg.org/ebooks/48870). Grant’s rendition of Einhard is a substantial improvement over the [1880 translation by Samuel Epes Turner](http://catalog.hathitrust.org/Record/000455670) commonly found in collections of medieval primary sources.

I have corrected errors in punctuation and spelling, encoding the book using the [Project Gutenberg RST format](http://epubmaker.pglaf.org). The electronic text is from the [scans by the University of Toronto Libraries](https://archive.org/details/earlylivesofchar00einh) (clearer than other available copies), which is a 1907 reprint by Chatto and Windus. The frontmatter is taken from a [1905 copy from Princeton University](http://catalog.hathitrust.org/Record/009022209). The cover image is from [the 1922 reprint scanned by the University of California Libraries](https://archive.org/details/earlylivesofchar00einhiala); it has a slightly different title page, and makes limited corrections, fixing for example ‘hi church’ on page 52, but not ‘willy-willy’ on page 67 or ‘Allelulia’ on page 87.

I have linked the notes to the text, revealing several errors in the referencing: the most significant of these are noted in the comments to the RST file, but I have freely moved the links to the footnotes by several lines to better fit the context. Results have been compared with the Notker text by Holly Ingraham available through [Medieval Sourcebook](http://legacy.fordham.edu/halsall/basis/stgall-charlemagne.asp). One feature from the print edition has been lost: there is no satisfactory method of including the running heads that summarize the text, but I did not consider these sufficiently important to merit using TEI for encoding.

The ‘handout’ version provided in Markdown and PDF format was created for teaching purposes, in which I have modernized some of the spelling and abridged Grant’s notes. To recreate the PDF, use [Pandoc](http://pandoc.org/) and LaTeX (BasicTeX plus the `tufte-latex` and `lineno` packages should be sufficient), with the command `pandoc einhard-handout.md -sS --template=handout.tex -V linenos -o einhard-handout.pdf`. The template has been modified slightly from a version by Caleb McDaniel.

The original text is [public-domain](https://creativecommons.org/publicdomain/mark/1.0/). To any extent that my contributions may be subject to copyright in some jurisdictions, they are licensed [CC0](https://creativecommons.org/publicdomain/mark/1.0/).
