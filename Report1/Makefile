all: 
	latexmk -latexoption="-shell-escape" -pdf report1.tex

clean:
	latexmk -CA
	rm -f arxiv.zip
	rm -f report1.bbl
	rm -rf _minted-report1
