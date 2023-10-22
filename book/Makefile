all: book

clean:
	rm *.log *.aux *.out *.toc 

veryClean:
	rm *.log *.aux *.out *.toc *.idx *.pdf *.synctex.gz
#book/beyond.idx book/beyond.pdf book/beyond.synctex.gz


book:
	pdflatex beyond.tex
	makeindex beyond.idx
	pdflatex beyond.tex

sbook:
	pdflatex beyond.tex
	makeindex beyond.idx
	pdflatex beyond.tex

ebook:
	pdflatex kinder_en.tex
	makeindex kinder_en.idx
	pdflatex kinder_en.tex
