# Investigating Binge Drinking and Military Service


## Abstract

This study investigates the association between military service and binge drinking using logistic regression on data from the 2021--2023 NHANES survey. After controlling for income, physical activity level, and education level, results show a lack of statistically significant association at the 0.05 level, though association was observed at the 0.1 level. The model identified income and education as stronger predictors of binge drinking behavior. Validity concerns limit the strength of the conclusions, prompting further research with improved control variables.

[Read the Full Paper](output/paper.pdf)

## Repository Structure

- `paper/` -- LaTeX source and figures for the technical report
- `analysis/` -- R Markdown code for data processing and modeling
- `data/` -- NHANES source data and cleaned project data
- `output/` -- Generated outputs (compiled PDF, tables, etc.)

## Compiling the Paper

From the `paper/` directory:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Or use `latexmk`:

```bash
latexmk -pdf main.tex
```

## Running the Analysis

1. Install R and required packages.
2. Open `analysis/MA376_Code.Rmd` in RStudio.
3. Ensure data files are in `data/`.
4. Knit the document or run chunks interactively.

See `analysis/README.md` for details.

## Data Sources

National Health and Nutrition Examination Survey (NHANES) 2021--2023, National Center for Health Statistics, CDC.

See `data/README.md` for variable descriptions.

## Author

Connor Durand
