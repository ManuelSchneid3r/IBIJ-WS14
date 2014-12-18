pdf:
	pdflatex  praxis-seminar.tex
	
bib:
	pdflatex  praxis-seminar.tex
	bibtex praxis-seminar 
	pdflatex  praxis-seminar.tex
	pdflatex  praxis-seminar.tex
	
clean:
	rm -f *.aux *.bbl *.log *.swp *.toc *.out *.blg *.lof

veryclean: clean
	rm *.pdf .*.swo .*.swp
