# letterbox theme

A [Quarto](https://quarto.org) extension for authoring letterbox styled Reveal.js presentations. This style is inspired of [xaringan](https://slides.yihui.org/xaringan/), and is an extension of the work of [Charlotte](https://twitter.com/charliejhadley) [seen here](https://www.visibledata.co.uk/posts/2022-08-04_how-i-learned-to-stop-replicating-everything-from-xaringan-and-love-quarto/).

## Installation

To start a new presentation:

``` bash
quarto use template EmilHvitfeldt/quarto-revealjs-letterbox
```

## Build the presentation

``` bash
quarto render mydocument.qmd
```

## Further Modifying theme

If you want to modify theme, you can specify the `.scss` my modifying the yaml to look like this

```yaml
format: 
  letterbox-revealjs:
    theme: [default, style.scss]
```

## Going further

Read the [Quarto documentation on reveal.js format](https://quarto.org/docs/presentations/revealjs/)
