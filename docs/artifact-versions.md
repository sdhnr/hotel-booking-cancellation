# Artifact versions and portfolio changes

The supplied folder contains artifacts from two stages of the capstone. They are kept distinct so that results remain traceable.

| Artifact | Result or status |
| --- | --- |
| `notebooks/02-cancellation-modeling.ipynb` and `outputs/modeling/` | Earlier solution-development stage. Logistic Regression selected; ROC-AUC 0.8577. |
| `reports/final-report.pdf` and `presentations/final-presentation.pdf` | Later team deliverables. Report optimized Gradient Boosting at ROC-AUC 0.8798 and an operating threshold of 0.25. |
| `dashboards/hotel-cancellation.pbix` | Supplied Power BI file, with Dashboard and Action List pages. Preserved unchanged; refresh and numerical reconciliation have not been validated in Power BI Desktop during portfolio preparation. |

The final report describes additional optimization, including removing a calendar feature, threshold tuning, and dashboard reconciliation. The corresponding final pipeline is not present in the supplied project folder. Running the included notebooks therefore reproduces the earlier workflow, not the final report's optimized solution. Results reported in the PDF are documented team results, not newly verified training results.

## Changes made for this portfolio

- Renamed and grouped deliverables into descriptive folders; see `file-map.csv`.
- Made notebook paths relative to the repository, so notebooks can be opened from the project root or the notebooks folder.
- Restored a commented-out `plt.savefig(` line whose remaining arguments caused an indentation error.
- Renamed confusion-matrix display objects so they no longer overwrite the callable IPython `display` function.
- Removed machine-specific paths from saved notebook text outputs while retaining plots and useful tables.
- Added setup instructions, source attribution, dependency ranges, and generated-file exclusions.

The modeling logic and historical saved performance results were not upgraded or replaced. Course rubrics, assignment instructions, duplicate checkpoints, interim slide decks, draft Word reports, serialized model binaries, and duplicate generated datasets are excluded from the public portfolio. Original files remain in the source folder.

## Attribution

Said Huner served as Data and Machine Learning Lead and contributed across the project. The final report specifically credits Said with the solution-development notebook, temporal split, preprocessing, model comparison and tuning, evaluation charts, scoring and action-list exports, business scenarios, design diagrams, and technical review.

The final report credits Asaad Razeq with project management, documentation and later pipeline optimization; Nora Yong with data/ML review and validation support; and Cassidy Taillon with dashboard implementation and visualization. The repository preserves these team credits and does not represent all deliverables as solo work.
