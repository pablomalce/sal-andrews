# Sal Andrews Ecuador

A static, Spanish-language brand website for Sal Andrews, an effervescent antacid sold in Ecuador by GSK Consumer Healthcare.

## Context

The code was committed in a single commit dated October 2020 and pushed to GitHub in February 2021. The repository does not record who commissioned it or whether this exact version went live; the content is written as a production brand site (GSK legal footer, a GSK promotional material code, links to Ecuadorian pharmacy chains).

## What it does

Seven hand-written HTML pages. Six share one navbar and all seven share one footer:

- `index.html`: home with the hero banner and links to the FAQ and "where to buy" pages
- `productos.html`: product benefits, flavours and pack sizes
- `que_es_la_acidez.html`: an explainer on heartburn, its causes and symptom management
- `preguntas_frecuentes.html`: an FAQ built on a Bootstrap accordion
- `donde_comprar.html`: links to pharmacy retailers in Ecuador
- `contacto.html`: company contact details and an "about us" section (no form)
- `politica_internet.html`: internet privacy policy text (no navbar)

## Stack

HTML5, CSS (one `style/style.css` that imports four component stylesheets, about 290 lines in all), Bootstrap 4.5 loaded from a CDN (five pages also load jQuery, Popper and the Bootstrap JS bundle; `donde_comprar.html` and `politica_internet.html` load only the CSS, so the collapsed mobile menu on `donde_comprar.html` does not open), and Google Fonts (Oswald, Open Sans). There is no build step, no JavaScript of its own and no backend.

## Running it

Open `index.html` in a browser, or serve the folder with any static server, for example `python3 -m http.server`.

Note: the repository is large (about 78 MB) because the full-resolution design exports and stock photos are committed in `img/` without optimisation.

## Status

Archived. Not maintained.
