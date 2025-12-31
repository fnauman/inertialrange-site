# InertialRange Labs AB Website

This is the official website for InertialRange Labs AB, a consulting company specializing in AI solutions.

## About

InertialRange Labs AB provides consulting services in:
- Time Series Forecasting
- Classification
- Computer Vision
- Large Language Models (LLMs)

## Building the Website

This website is built using [Quarto](https://quarto.org/).

### Prerequisites

- Quarto (version 1.4 or later)

### Build Instructions

To render the website:

```bash
quarto render
```

To preview the website locally:

```bash
quarto preview
```

The generated website will be in the `_site/` directory.

## Project Structure

- `_quarto.yml` - Quarto project configuration
- `index.qmd` - Home page
- `about.qmd` - About page
- `services.qmd` - Services page
- `styles.css` - Custom CSS styles
- `_site/` - Generated website (not committed to git)
