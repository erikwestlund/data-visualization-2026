# Data Visualization Course

This repository contains the student-facing course materials.

## Start Here

1. Open `data-visualization-course.Rproj` in RStudio, or open this folder in Positron.
2. Open `modules/00_preclass-tech-check/01_pre-class-directions.qmd`.
3. Open and render `modules/00_preclass-tech-check/02_setup-check.qmd`.
4. Use `syllabus.html` for the course syllabus.

## Folders

- `data/`: course datasets, rendered codebooks, and `data/data.html` index.
- `slides/`: rendered course slides as HTML files.
- `modules/`: lesson notebooks and setup checks as Quarto `.qmd` files.
- `assignments/`: rendered problem set and project instructions as HTML files.

## Rendering

Module notebooks render to self-contained HTML files. The included `_quarto.yml` files set `embed-resources: true` so rendered notebooks can be submitted or shared as single HTML files.

If rendering fails, check that R, Quarto, and the required packages are installed.

Required R packages for the first part of the course:

```r
install.packages(c("dplyr", "ggplot2", "readr", "stringr", "here"))
```
