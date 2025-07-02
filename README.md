# Research Template

A template repository for reproducible research projects using Quarto and R.

## Overview

This template provides a structured foundation for academic research projects with:
- **Quarto** for literate programming and document generation
- **R** for statistical analysis and data processing
- **renv** for package management and reproducibility

## Getting Started

### Setup

1. Clone this repository or use it as a template
2. Open the project in yout IDE
3. Restore the R environment:
   ```r
   renv::restore()
   ```
4. Install additional packages if needed:
   ```r
   renv::install("package_name")
   ```

## Project Structure

```
├── data/              # Raw and processed data
├── manuscript/        # Manuscript files
├── playground/        # Exprerimentation and exploratory analysis
├── slides/            # Presentation files
├── _quarto.yml        # Quarto configuration
├── index.qmd          # Main document/report
├── renv/              # Package environment
├── renv.lock          # Package lockfile
└── README.md          # This file
```

## Key Features

- **Reproducible**: All dependencies tracked with `renv`
- **Flexible**: Multiple output formats via Quarto
- **Collaborative**: Version control ready with `.gitignore` configured

## Usage

1. Add your data to the `data/` directory
2. Create analysis functions in `R/`
3. Write your report in `playground/exemple/analysis_exemple.qmd` or create additional `.qmd` files
4. Render your documents with Quarto

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run `renv::snapshot()` to update the lockfile
5. Submit a pull request

