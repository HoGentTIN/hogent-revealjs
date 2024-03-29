# Presentatiesjabloon HOGENT

In deze repo vind je een stijlsjabloon voor een sobere presentatie, conform de HOGENT huisstijl, gebaseerd op [reveal.js (v4.3.1)](https://revealjs.com/).

In `index.md` komt de inhoud van de presentatie, [opgemaakt in Markdown](https://github.com/jgm/pandoc/wiki/Using-pandoc-to-produce-reveal.js-slides). Een `Makefile` zorgt voor de omzetting in een reveal.js-presentatie. De presentatie kan dan getoond worden in een webbrowser en/of online gepubliceerd worden via Github Pages.

## Vereisten

- Bash shell met de typische commando's, specifiek: awk, wget, tar, GNU Make
- [pandoc](https://pandoc.org/) -- tool voor het omzetten tussen tekstformaten (hier: Markdown -> reveal.js)
- XeLaTeX -- voor het genereren van de handouts (pdf)
    - Installeer LaTeX voor jouw platform (Linux: Texlive, MacOS: MacTeX, Windows: MikTeX)
- Lettertypes voor de HOGENT huisstijl (enkel voor de pdf):
    - Montserrat Regular en ExtraBold
    - Inconsolata (voor broncode)

## Aan de slag

1. Download of kloon deze repository
2. Bewerk [index.md](index.md). Specifieke Markdown-tips [vind je hier](https://github.com/jgm/pandoc/wiki/Using-pandoc-to-produce-reveal.js-slides)
3. Voer in een console het commando `make all` uit
4. Open `docs/index.html` in een webbrowser.

Als je de presentatie bijhoudt op Github, kan je Github Pages activeren om het resultaat online te publiceren:

1. Zorg er voor dat de presentatie gegenereerd is en dat de `docs/` folder naar Github gepushed is
2. Ga naar de Github repository met de broncode van je presentatie, klik door naar Settings
3. Scoll naar beneden tot je de titel "Github Pages" tegenkomt
4. In het dropdown-menu, kies "master branch /docs" folder

De presentatie is dan zichtbaar via url `https://GEBRUIKER.github.io/REPOSITORY/`. Voor deze repo, bijvoorbeeld: <https://hogenttin.github.io/hogent-revealjs/>
