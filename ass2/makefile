TEX=pdflatex
SOURCE=report.tex

all: report

report:
	latexmk -pdf -pdflatex="pdflatex -interactive=nonstopmode" -use-make $(SOURCE)

clean:
	rm -rf *.aux *.log *.pdf *.bbl *.blg *.lot *.lof *.toc *.fdb_latexmk *.fls

.PHONY: report clean
