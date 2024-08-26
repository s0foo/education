FILE=main

all:
	pdflatex ${FILE}
	bibtex ${FILE}
	pdflatex ${FILE}
	pdflatex ${FILE}

clean:
	@rm -f *.aux *.blg *.bbl *.log *.out *~

.PHONY: all clean
