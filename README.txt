Author: 
<pre>
W. de Kraker
Student no. 0815283
0815283@hr.nl
</pre>

This thesis was written in LaTeX [1], BibTeX [2] was used as bibligraphy, compiled using MacTeX [3].
The Layout model is provided by Rotterdam University [4].


*Build a publishable version* (no titlepage, credits, evaluation or attachments)
* open thesis.text
* uncomment line 12 by removing the %
```\publictrue```
* follow steps from normal version build

*Build normal version (terminal)*
In terminal or cygwin:
* cd to the dictionairy containing thesis.tex
```> cd ~/Downloads/thesis_0815283
* build LaTeX files```
```> pdflatex thesis.tex
* build BibTeX files (via thesis.tex)
```> bibtex thesis.tex```
* combine both to finish the proces
```> pdflatex thesis.tex```

or:

*Build normal version (TeXShop)*
In TeXShop:
* open thesis.tex
* Typeset LaTeX
* Typeset BibTeX
* Typeset LaTeX again to complete the process


À propos, thesis.pdf

	[1]: http://www.latex-project.org       "LaTeX"
	[2]: http://www.bibtex.org      "BibTeX"
	[3]: http://www.tug.org/mactex/2011      "MacTex"
	[4]: http://med.hro.nl/bropj/afstuderen/afstudeerverslag-1.5.zip       "Rotterdam University"