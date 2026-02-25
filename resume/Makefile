# Makefile for compiling the LaTeX resume
# Uses tectonic — a self-contained LaTeX engine.
#
# Usage:
#   make          - compile the resume to PDF
#   make clean    - remove build artifacts

TEX = main.tex
PDF = main.pdf

.PHONY: all clean

all: $(PDF)

$(PDF): $(TEX)
	tectonic $(TEX)

clean:
	rm -f $(PDF)
