#makefile for pdflatex
#modifica di prova limiti 

outputdir=../pdf
texfile=Master


clean: 
	rm *.{out,nav,log,fls,snm,toc,fdb*,aux,gz}

$(texfile).pdf: $(texfile).tex
	pdflatex -output-directory=$(outputdir) $(texfile).tex

pdf: $(texfile).pdf
	evince ${outputdir}/$(texfile).pdf
