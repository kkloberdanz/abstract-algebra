.PHONY: all
all: kloberdanz_417HW06.pdf

kloberdanz_417HW06.pdf: kloberdanz_417HW06.tex
	pdflatex kloberdanz_417HW06.tex

.PHONY: convert-pdf-to-jpg
convert-pdf-to-jpg:
	pdftoppm -jpeg -r 300 lattice.pdf lattice.jpg

.PHONY: clean
clean:
	rm -f *.pdf
	rm -f *.aux
	rm -f *.log
