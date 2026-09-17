# Portfolio validation

Validated on 2026-09-17 using Python 3.11, pandas 1.5.3, NumPy 1.23.5, Matplotlib 3.7.0, and scikit-learn 1.2.1.

- All code cells in both notebooks passed Python syntax validation.
- The complete data-preparation notebook executed sequentially after the documented portability fixes.
- All four internal reproducibility checks passed: cleaned, rejected, model-ready, and Power BI datasets matched on row count, column count, column order, and values.
- The included raw CSV's SHA-256 matches the original source manifest.
- Both final PDF deliverables were text-extracted for version and attribution review; the presentation cover was rendered and visually checked.
- The PBIX archive contains Dashboard and Action List pages. Power BI Desktop refresh was not performed.

The model-training and hyperparameter-search workflow was not rerun. Published model metrics and notebook plots are historical outputs from the source project. The final report's later optimized pipeline was not supplied, so its model and dashboard totals could not be independently reproduced here.
