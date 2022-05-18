proj4.pdf: proj4.ps
	pdflatex proj4.tex

proj4.ps: proj4.dvi
	dvips -sPAPERSIZE=a4 proj4.dvi

proj4.dvi: proj4.tex 
	latex proj4.tex
	bibtex proj4
	latex proj4.tex
	latex proj4.tex
