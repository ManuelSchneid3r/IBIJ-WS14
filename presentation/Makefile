pdf:
	pdflatex document.tex

bib:
	pdflatex document.tex
	bibtex document
	pdflatex document.tex
	pdflatex document.tex

clean:
	rm -f *.aux *.bbl *.log *.swp *.toc *.out *.blg *.lof

veryclean: clean
	rm *.pdf .*.swo .*.swp
