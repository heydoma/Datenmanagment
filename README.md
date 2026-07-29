## LaTeX-Projekt

### Bauen

Im Ordner `Latex`:

```sh
latexmk -pdf main.tex
```

oder falls SVGs zum ersten mal eingefügt werden:

```sh
latexmk -pdf -shell-escape main.tex
```

Alternativ:

```sh
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Die fertige Datei liegt unter `Latex/main.pdf`.

### Wichtige Verzeichnisse

- Metadaten und Titelseite: `Latex/main.tex`
- Inhalt: `Latex/chapters/`
- Literatur: `Latex/bib/quellen.bib`
- Abbildungen: `Latex/images/`
- Abkürzungen und Abstract: `Latex/frontmatter/`