.PHONY:all

all:
	pandoc paper.md -o paper.from_md.tex || true
	pandoc paper.md -o paper.from_md.html || true
	pandoc paper.md -o paper.from_md.pdf || true

	pandoc paper.docx -o paper.from_docx.md || true
	pandoc paper.docx -o paper.from_docx.html || true
	pandoc paper.docx -o paper.from_docx.pdf || true

	pandoc paper.tex -o paper.from_tex.md || true
	pandoc paper.tex -o paper.from_tex.html || true
	pdflatex -interaction=nonstopmode --jobname=paper.from_tex paper.tex || true
