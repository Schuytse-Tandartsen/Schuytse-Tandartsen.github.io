# Website

## Gebruik
### Aanpassingen
Aanpassingen kunnen worden aangepast via de Github-website.

In het mapje pages staan alle paginas van de website.

**Let op:** Als je een permalink aanpast dien je ook [de navigatie](https://github.com/Schuytse-Tandartsen/website/blob/main/_data/navigation.yml) aan te passen.

Aanpassingen worden redelijk snel gereleased naar [https://schuytse-tandartsen.github.io/](https://schuytse-tandartsen.github.io/)

### Notatie

Bij het aanpassen van de website maak je gebruik van [Markdown](https://www.markdownguide.org/cheat-sheet/), daarnaast kun je gebruik maken van secties en kolommen.

Secties zijn horizontale scheidingen en worden beschreven met `+++`, kolommen geef je aan door middel van `///`.

### Live zetten
1. Ga naar de [Actions-pagina voor Production deploy](https://github.com/Schuytse-Tandartsen/website/actions/workflows/production.yml).
2. Klik op "Run workflow" en dan in het dropdown nogmaals op de groene knop "Run workflow".

### Tarieven
De tarieven-pagina bestaat uit 2 delen, de data kun je vinden in `_data/tarieven.xlsx`. De tekst en mark-up staat in `_layouts/prices.html`.

## Installation
Use ruby 3.0.1:
```
rbenv local 3.0.1
```

Install Gems:
```
bundle
```

## Development
Run with live reload:
```
bundle exec jekyll serve --livereload
```

## Pricing page

- The plugin is inside the \_plugins-folder.
- The config is inside the config.yml-file.
- The layout used is layouts/prices.html.
