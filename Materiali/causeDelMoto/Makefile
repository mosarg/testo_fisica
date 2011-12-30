texDir=tex
pdfDir=pdf

all : $(pdfDir)/main.pdf clean
.PHONY: all
.ONESHELL:
$(pdfDir)/main.pdf: $(texDir)/*.tex
	export TEXINPUTS="../$(texDir):"
	cd $(pdfDir) 
	pdflatex main
clean:
	rm -f pdf/*.{aux,out}
