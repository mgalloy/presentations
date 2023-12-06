.PHONY: all pdf open notes

OPTIONS=--pdf --allow-local-files

all: pdf notes open

pdf:
	marp $(OPTIONS) jupyter-notebooks.md

notes:
	marp --notes jupyter-notebooks.md

open:
	open jupyter-notebooks.pdf
