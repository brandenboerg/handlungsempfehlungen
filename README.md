# Überblick

Dieses Repository enthält die Quelltexte für die Handlungsempfehlungen zur
Verankerung von OER an Brandenburger Hochschulen.

Der jeweils aktuelle Stand der Dokumentation kann unter
[https://handlungsempfehlungen.brandenboerg.de](https://handlungsempfehlungen.brandenboerg.de)
eingesehen werden.

# Übersetzung

## Abhängigkeiten

Die Empfehlungen liegen im [rmarkdown](https://rmarkdown.rstudio.com/)-Format
vor. Zur Übersetzung werden folgende Programe benötigt:

- [R](https://www.r-project.org/) mit folgenden Paketen:
  - [rmarkdown](https://rmarkdown.rstudio.com/)
  - [bookdown](https://www.bookdown.org/)
- [pandoc](https://pandoc.org/) Version 2.3 oder höher)
- XeTeX-kompatible LaTeX-Installation (zur PDF-Erzeugung)

## Mit RStudio

Lade in RStudio die Projektdatei `handlungsempfehlungen.Rproj` und starte die
Übersetzung mit _Build all_.

## Mit RScript

Wechsele auf der Kommandozeile in das Repository-Verzeichnis und starte die
Übersetzung mit:

```
Rscript -e "bookdown::render_book(input='index.Rmd', output_format='all')"
```
