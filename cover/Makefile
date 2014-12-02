.PHONY: build preview clean

TARGET=sample.pdf
SOURCE=sample.tex
RELATEDS=guocover.sty guo.cls cover.tex

all: build preview

build: ${TARGET}

${TARGET}: ${SOURCE} ${RELATEDS}
	xelatex $<

preview:
	xdg-open ${TARGET}

clean:
	rm -fv *.aux *.log *.toc *.ind *.gls *.glo *.idx *.ilg *.out *.bbl *.thm *.blg *.lot *.lof *~
