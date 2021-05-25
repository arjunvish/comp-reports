all: 
	latexmk -latexoption="-shell-escape" -pdf report2old.tex

clean:
	latexmk -CA
	rm -f report2old.bbl
	rm -rf _minted-report2old
