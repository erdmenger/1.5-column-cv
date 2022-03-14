# Makefile for CV creation

# TEX = xelatex

# For future use with pandoc and prameters
TEX = pandoc
src = template.tex details.yml
FLAGS = --pdf-engine=xelatex

default:	output.pdf

output.pdf : $(src)
	$(TEX) $(filter-out $<,$^ ) -o $@ --template=$< $(FLAGS)

.PHONY: clean
clean :
	rm *.pdf *.log *.aux
