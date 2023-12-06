.PHONY: all pdf open notes

OPTIONS=--pdf --allow-local-files

all: pdf notes open

pdf:
	marp $(OPTIONS) accessing-hao-db.md

notes:
	marp --notes accessing-hao-db.md

open:
	open accessing-hao-db.pdf
