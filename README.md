# POLIMI Marp Template

> This template is based on the [TUM Marp Template](https://github.com/hofbi/tum-marp-template).

This is a template for [Marp](https://marp.app/) presentations at Politecnico di Milano ([POLIMI](https://polimi.it)). Marp is the simplest presentation writer with Markdown.

The exported pdf is available [here](slide-deck.pdf).

## Setup

To setup this template in VS Code, you need to install the [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) extension and add the following to your workspace preferences available in `settings.json`:

```json
"markdown.marp.themes": [
    "./themes/polimi.css"
]
```

## Build

```shell
# Generate PDF
npx @marp-team/marp-cli@latest slides/slide-deck.md -o slide-deck.pdf

# Generate PowerPoint
npx @marp-team/marp-cli@latest slides/slide-deck.md -o slide-deck.pptx
```

## How To Use Marp

- [Get Started](https://github.com/marp-team/marp)
- [Documentation](https://marpit.marp.app/)
- [CLI](https://github.com/marp-team/marp-cli)
