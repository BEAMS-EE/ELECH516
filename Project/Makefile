all: tp
	echo "done"


tp: *.tex
	pdflatex -shell-escape -jobname="elech516_ex1" elech516_ex1.tex
	pdflatex -shell-escape -jobname="elech516_ex1" elech516_ex1.tex

clean:
	rm elech516_ex1.pdf
	rm -f *.idx *.aux *.log *.nav *.out *.snm *.toc
