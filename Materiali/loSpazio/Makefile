texDir=tex
pdfDir=pdf

all : $(pdfDir)/loSpazio.pdf clean
.PHONY: all
.ONESHELL:
$(pdfDir)/loSpazio.pdf: $(texDir)/*.tex
	export TEXINPUTS="../$(texDir):"
	cd $(pdfDir) 
	pdflatex main
clean:
	rm -f pdf/*.{aux,out}
