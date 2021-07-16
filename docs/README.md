# Website

## Gebruik
### Aanpassingen
Aanpassingen kunnen worden aangepast via de Github-website. Aanpassingen worden redelijk snel gereleased naar [https://schuytse-tandartsen.github.io/](https://schuytse-tandartsen.github.io/)


### Live zetten
1. Ga naar de [Actions-pagina voor Production deploy](https://github.com/Schuytse-Tandartsen/website/actions/workflows/production.yml).
2. Klik op "Run workflow" en dan in het dropdown nogmaals op de groene knop "Run workflow".

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
