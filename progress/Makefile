
all:
	pdflatex proposal
	bibtex proposal
	pdflatex proposal
	pdflatex proposal
	mv -f proposal.pdf RainCloud-2nd.pdf

clean:
	rm -f *.pdf *.aux *.bbl *.blg *.log
