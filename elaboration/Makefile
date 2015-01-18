pdf:
	pdflatex  seminar.tex
	
bib:
	pdflatex  seminar.tex
	bibtex seminar 
	pdflatex  seminar.tex
	pdflatex  seminar.tex
	
clean:
	rm -f *.aux *.bbl *.log *.swp *.toc *.out *.blg *.lof

veryclean: clean
	rm *.pdf .*.swo .*.swp
