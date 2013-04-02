all: final

final: report cover letter
	latexmk -pdf -use-make crdueck_PD2Report.tex

report:
	latexmk -pdf -pdflatex="pdflatex -interaction=nonstopmode" -use-make report.tex

cover:
	latexmk -pdf -use-make cover_page.tex

letter:
	latexmk -pdf -use-make letter_of_submittal.tex

clean:
	latexmk -c

.PHONY: clean
