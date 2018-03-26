all:	
	latex cv.tex
	dvips -o cv.ps cv.dvi
	pdflatex cv.tex
	yes | cp cv.ps ~/public_html
	yes | cp cv.pdf ~/public_html
	gv cv.ps &
	latex ecv.tex
	dvips -o ecv.ps ecv.dvi
	pdflatex ecv.tex
	yes | cp ecv.ps ~/public_html
	yes | cp ecv.pdf ~/public_html
