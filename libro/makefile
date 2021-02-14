all: short clean

short:
	pdflatex estadisticaRepensada.tex

full:
	pdflatex estadisticaRepensada.tex
	bibtex estadisticaRepensada.aux
	pdflatex estadisticaRepensada.tex
	pdflatex estadisticaRepensada.tex

clean:
	- rm -f *.log
	- rm -f *.soc
	- rm -f *.toc
	- rm -f *.aux
	- rm -f *.out
	- rm -f main.idx
	- rm -f *.bbl
	- rm -f *.bbg
	- rm -f *.dvi
	- rm -f *.blg
	- rm -f *.lof
	- rm -f *.nav
	- rm -f *.snm
	- rm -f *~

