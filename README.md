# Emulsifiers — Analysis code

This repository contains analysis code used in the published study: PLOS Biology article (https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3002171).

Overview
- The primary analysis contributed here is the anxiety z-score workflow used in the paper. See [`Anxiety_Zscore.Rmd`](Anxiety_Zscore.Rmd) for the full R Markdown script that implements the calculations and generates figures/tables.

Contents
- [`Anxiety_Zscore.Rmd`](Anxiety_Zscore.Rmd) — R Markdown analysis implementing the anxiety z-score and associated plots/tables.

Reproducing the analysis
- Install R (version >= 4.0 recommended) and the R packages listed at the top of [`Anxiety_Zscore.Rmd`](Anxiety_Zscore.Rmd).
- Render the R Markdown locally (RStudio: click "Knit") or from the command line:
```sh
R -e "rmarkdown::render('Anxiety_Zscore.Rmd')"
```
- Outputs (figures, tables, HTML) are produced according to the YAML output settings in [`Anxiety_Zscore.Rmd`](Anxiety_Zscore.Rmd).

Citation
- If you use these scripts, please cite the associated paper: https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3002171

Notes
- This repository contains the analysis script(s) only. Check the R Markdown header for required package versions and any data access instructions.
- For questions or issues, open an issue on this repository: https://github.com/elenu/Emulsifiers
