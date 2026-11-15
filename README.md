# InertialRange Labs AB Website

This is the official website for [InertialRange Labs AB](https://inertialrange.com), an AI and data-platform consulting practice run by Farrukh Nauman.

## About

InertialRange Labs AB provides senior consulting in:
- AI engineering and agentic systems: agents on analytics data, Text-to-SQL, coding agents, evaluation and tracing
- Enterprise data platforms (BigQuery, Snowflake, Databricks, Spark, Snowpark)
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
- `engage.qmd` - Engagement models (also served at `services.html`)
- `contact.qmd` - Contact page
- `theme.scss` - Theme (palette, typography, cards)
- `styles.css` - Intentionally empty; styles live in `theme.scss`
- `_site/` - Generated website (not committed to git)
