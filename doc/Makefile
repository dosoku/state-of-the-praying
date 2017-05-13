pdf:
	mdc <index.md | pandoc --template template.tex -o book.tex
	platex book.tex
	dvipdfmx book

clean:
	rm -f book.* *.aux *.log
