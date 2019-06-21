# Presentatiesjabloon HOGENT

In deze repo vind je een stijlsjabloon voor een sobere presentatie, conform de HOGENT huisstijl, gebaseerd op [reveal.js](https://revealjs.com/).

In `index.md` komt de inhoud van de presentatie, [opgemaakt in Markdown](https://github.com/jgm/pandoc/wiki/Using-pandoc-to-produce-reveal.js-slides). Een `Makefile` zorgt voor de omzetting in een reveal.js-presentatie. De presentatie kan eenvoudig online gepubliceerd worden via Github Pages.

## Vereisten

- [pandoc](https://pandoc.org/) -- tool voor het omzetten tussen tekstformaten (hier: Markdown -> reveal.js)
- XeLaTeX -- voor het genereren van de handouts (pdf)
    - Installeer LaTeX voor jouw platform (Linux: Texlive, MacOS: MacTeX, Windows: MikTeX)
- Lettertypes voor de HOGENT huisstijl (enkel voor de pdf):
    - Montserrat Regular en ExtraBold
    - Inconsolata (voor broncode)

## Aan de slag

1. Download of kloon deze repository
2. Bewerk index.md
3. Voer in een console het commando `make all` uit
4. Open [docs/index.html](docs/index.html) in een webbrowser.

Als je de presentatie bijhoudt op Github, kan je Github Pages activeren om het resultaat online te publiceren:

1. Ga naar de Github repository met de broncode van je presentatie, klik door naar Settings
2. Scoll naar beneden tot je de titel "Github Pages" tegenkomt
3. In het dropdown-menu, kies "master branch /docs" folder
