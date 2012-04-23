
all:
	pdflatex final-paper
	bibtex final-paper
	pdflatex final-paper
	pdflatex final-paper
	mv -f final-paper.pdf RainCloud-3rd.pdf

clean:
	rm -f *.pdf *.aux *.bbl *.blg *.log
