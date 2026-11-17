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
- `engage.qmd` - Offers (also served at `services.html`)
- `contact.qmd` - Contact page
- `theme.scss` - Theme (palette, typography, cards)
- `styles.css` - Intentionally empty; styles live in `theme.scss`
- `_site/` - Generated website (not committed to git)

## Enquiry path and measurement

The company site is the offer and contracting destination; technical writing and
case studies stay on fnauman.com. The homepage routes a visitor by problem to a
specific offer. Each offer's email link opens a draft with its name in the subject
and a short project brief. The contact page also provides the direct address and
an intro-call link. No form backend or new tracking service is required.

When sharing the site, link to the relevant offer anchor (`engage.html#reliability-audit`,
`#build-sprint`, `#reliability-retainer`, or `#embedded-engineering`). Use the technical
case study as supporting evidence for that audience.

Evaluate the change using actual enquiries, qualified conversations, proposals,
and signed engagements. Record the source when the enquirer provides it and use
the offer-specific subject to identify interest. An email click or a calendar
visit is not a completed enquiry. Without visit counts by source, zero enquiries
cannot distinguish insufficient relevant traffic from a conversion problem.
