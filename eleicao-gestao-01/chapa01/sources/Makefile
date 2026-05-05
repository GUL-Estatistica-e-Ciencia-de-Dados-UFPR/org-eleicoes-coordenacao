TEX_FILES := $(wildcard *.tex)
PDF_FILES := $(TEX_FILES:.tex=.pdf)
HTML_FILES := $(TEX_FILES:.tex=.html)
MD_FILES := $(TEX_FILES:.tex=.md)

LATEXMK := latexmk
PANDOC := pandoc

.PHONY: all pdf html md clean clean-intermediate clean-all

all: pdf html md clean-intermediate

pdf: $(PDF_FILES)

html: $(HTML_FILES)

md: $(MD_FILES)

%.pdf: %.tex
	$(LATEXMK) -pdf -interaction=nonstopmode -halt-on-error "$<"

%.html: %.tex
	$(PANDOC) "$<" -s -o "$@"

%.md: %.tex
	$(PANDOC) "$<" -s -t gfm -o "$@"

clean-intermediate:
	$(LATEXMK) -c
	rm -f *.aux *.bbl *.bcf *.blg *.fdb_latexmk *.fls *.log *.out *.run.xml *.toc *.lof *.lot *.nav *.snm *.vrb *.synctex.gz

clean:
	$(MAKE) clean-intermediate

clean-all: clean-intermediate
	rm -f $(PDF_FILES) $(HTML_FILES) $(MD_FILES)