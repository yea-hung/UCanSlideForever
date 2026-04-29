## Motivation

Dragging items around in PowerPoint, or clicking around, is tedious and can distract from the ultimate goal of producing good content. 😢

Using [Markdown](https://en.wikipedia.org/wiki/Markdown) to create content may help minimize distractions, resulting in better content. 🥳

## Overview

This is a UCSF-style theme for [Quarto-with-reveal.js presentations](https://quarto.org/docs/presentations/revealjs/). This should be mostly compatible with accessibility guidelines. Please file a GitHub issue or email me if you believe it is not, or have any other suggestions. 😊

## Use

You'll need [RStudio](https://posit.co/download/rstudio-desktop), [Positron](https://positron.posit.co/download.html), or [VS Code](https://code.visualstudio.com/download).

For any one slide deck, you'll always have two files:

- a behind-the-scenes file: a **Quarto file** (`.qmd` extension)
- the visible slide deck: an **HTML file** (`.html` extension) that you can open, and present, in any web browser

You will directly create and edit the Quarto file. The software (see above) will use that Quarto file to update ("render") the HTML file.

Write content in the Quarto file using [Markdown](https://en.wikipedia.org/wiki/Markdown). Begin section titles with the hash symbol (`#`) and begin slide titles with two hash symbols (`##`). 

See `demo.qmd` for a demonstration. 

The theme itself is fully contained in `ucsf.scss`. 

## Settings

- `title`: the title
- `subtitle`: the subtitle (delete this line if you don't have a subtitle)
- `author`: the authors
- `date`: the date in YYYY-MM-DD format

## Optional settings

- `embed-resources`: change this to `true` if you intend to share the HTML slide deck
- `data-background-image`: optionally, use a more logo that is specific to your school, department, or project

## Further reading

- [guide to Quarto](https://quarto.org/docs/guide/)
- [guide to using Quarto with reveal.js](https://quarto.org/docs/presentations/revealjs/)
