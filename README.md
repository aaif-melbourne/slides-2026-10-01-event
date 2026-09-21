# Agentic AI Melbourne — September 2026

Intro and outro MC slides for Agentic AI Melbourne on 2 September 2026, built with [Slidev](https://sli.dev/).

## Requirements

- [Bun](https://bun.sh/)

## Run the deck

```sh
make
```

The first run installs dependencies and opens the presentation in a browser.

## Export

```sh
make pdf  # writes slides.pdf
make ppt  # writes slides.pptx
```

PowerPoint slides are exported as images, while presenter notes remain attached to each slide.

## Build

```sh
make build
```

Pushes to `main` build and deploy the deck to GitHub Pages. The workflow can also be run manually from the Actions tab.

## License

Copyright © 2026 Ryan Djurovich ([ryan0x44.com](https://ryan0x44.com/)).

This presentation is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). See [`LICENSE`](LICENSE) for the full terms.
