texDir=tex$
pdfDir=pdf$
$
all : $(pdfDir)/teoriaDellaMisura.pdf clean$
.PHONY: all$
.ONESHELL:$
$(pdfDir)/teoriaDellaMisura.pdf: $(texDir)/*.tex$
	export TEXINPUTS="../$(texDir):"$
	cd $(pdfDir) $
	pdflatex main$
clean:$
	rm -f pdf/*.{aux,out}$
