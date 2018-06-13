all: mipt-thesis-bs.cls mipt-thesis.sty thesis.tex thesis.bib
	pdflatex thesis.tex
	biber thesis
	pdflatex thesis.tex

clean:
	rm -f thesis.pdf thesis.log thesis.aux thesis.toc
