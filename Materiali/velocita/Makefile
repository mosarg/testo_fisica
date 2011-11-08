texDir=tex
pdfDir=pdf

all : $(pdfDir)/loSpazioTraGeometriaEFisica.pdf clean
.PHONY: all
.ONESHELL:
$(pdfDir)/loSpazioTraGeometriaEFisica.pdf: $(texDir)/*.tex
	export TEXINPUTS="../$(texDir):"
	cd $(pdfDir) 
	pdflatex main
clean:
	rm -f pdf/*.{aux,out}
