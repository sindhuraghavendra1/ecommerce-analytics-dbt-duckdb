# Analytics Engineering Portfolio

A portfolio of analytics engineering work: turning raw data into clean, tested, analysis-ready models.

## Project Structure

```
analytics-engineering-portfolio/
├── data/
│   ├── raw/            # Source data, untouched
│   └── processed/      # Cleaned / transformed outputs
├── models/
│   ├── staging/        # 1:1 with sources: renaming, casting, light cleaning
│   ├── intermediate/   # Joins and business logic building blocks
│   └── marts/          # Final fact & dimension tables for analysis
├── tests/              # Data quality and model tests
├── scripts/            # Ingestion, utilities, and automation
├── README.md
└── .gitignore
```

## Modeling Layers

| Layer | Purpose | Naming |
|---|---|---|
| Staging | Clean and standardize each source | `stg_<source>__<entity>` |
| Intermediate | Reusable transformations and joins | `int_<entity>_<verb>` |
| Marts | Business-facing facts and dimensions | `fct_<entity>`, `dim_<entity>` |

## Getting Started

1. Place source files in `data/raw/`.
2. Build models layer by layer: staging → intermediate → marts.
3. Run tests in `tests/` to validate data quality.

## Projects

_Coming soon._
