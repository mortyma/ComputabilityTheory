PROJECT = computability_ex1.tex

.PHONY: all clean

all: $(PROJECT).pdf

$(PROJECT).pdf: $(PROJECT).tex
	latexmk -pdf -use-make $(PROJECT).tex

clean:
	latexmk -CA
