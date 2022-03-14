# Makefile for CV creation

TEX = xelatex

# For future use with pandoc and prameters
# TEX = pandoc
# src = template.tex details.yml
# FLAGS = --latex-engine=xelatex

# output.pdf : $(src)
#	$(TEX) $(filter-out $<,$^ ) -o $@ --template=$< $(FLAGS)

default:	pdf

pdf:
	$(TEX) cv-example-1.tex

# %pdf:	%.tex
# 	$(TEX) $(@);

.PHONY: clean
clean :
	rm *.pdf *.log *.aux
