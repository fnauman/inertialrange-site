# InertialRange Labs AB Website

This is the official website for [InertialRange Labs AB](https://inertialrange.com), an AI and data-platform consulting practice run by Farrukh Nauman.

## About

InertialRange Labs AB provides senior consulting in:
- Enterprise data platforms (Snowflake, Databricks, Spark, Snowpark)
- AI coding-agent workflows for migration, validation, and analytics automation
- Time series / telemetry ML for industrial production and edge deployment
- Fractional / interim technical leadership

See [fnauman.com](https://fnauman.com) for case studies and writing.

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
