tensor_b1: 
	latex  tensor_b1.tex
	bibtex tensor_b1
	latex  tensor_b1.tex
	dvips -t letter -o tensor_b1.ps tensor_b1.dvi
	ps2pdf tensor_b1.ps

clean:
	rm -f *.aux *.bbl *.blg *.log *.lof *.lot *.toc *.dvi