# Personal Resume

Updated Chinese and English resumes:

| Language | One-page PDF | Editable LaTeX | Detailed Markdown |
| --- | --- | --- | --- |
| 中文 | [resume_ZH.pdf](resume_ZH.pdf) | [resume_ZH.tex](resume_ZH.tex) | [简历-中文.md](简历-中文.md) |
| English | [resume.pdf](resume.pdf) | [resume.tex](resume.tex) | [resume-english.md](resume-english.md) |

## Build the PDFs

Install a TeX Live distribution with XeLaTeX, xeCJK, fontspec, fontawesome, and the standard TeX Gyre Termes and Fandol fonts. The repository uses those bundled fonts and does not distribute font binaries.

Run each command twice to refresh PDF bookmarks:

~~~powershell
xelatex -interaction=nonstopmode -halt-on-error resume_ZH.tex
xelatex -interaction=nonstopmode -halt-on-error resume_ZH.tex
xelatex -interaction=nonstopmode -halt-on-error resume.tex
xelatex -interaction=nonstopmode -halt-on-error resume.tex
~~~

Both PDFs are A4, one page, and are committed for direct download.
