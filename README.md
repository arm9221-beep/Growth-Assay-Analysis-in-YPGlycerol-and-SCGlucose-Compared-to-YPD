# Growth Assay in YPGlycerol and SCGlucose Compared to YPD

Website presenting the fluconazole (FLC) growth curve assays and dose-response analyses used to determine the drug concentration for the evolution experiment.

SCGlu is compared to YPD to test whether yeast extract has an effect on CNV (copy number variant) formation, and YPGly is compared to YPD to test whether the carbon source has an effect on CNV formation.

Live site: published via GitHub Pages from this repository's `main` branch.

## Contents

- `index.html` — landing page linking to the growth assay reports and the dose-response analysis reports.
- `reports/july2/` and `reports/july20/` — raw growth curve reports (HTML + Rmd source) for each assay date. Both assays were run for 72 hours to give the strains enough time to grow in YPGlycerol.
- `reports/` — rendered R Markdown HTML dose-response reports and their `.Rmd` source files:
  - `Doseresponse_24hrs_SCGluvsYPD` — SCGlu vs YPD, 24-hour timepoint
  - `Doseresponse_24hrs_YPGlyvsYPD` — YPGly vs YPD, 24-hour timepoint
  - `Doseresponse_72hrs_SCGluvsYPD` — SCGlu vs YPD, 72-hour timepoint
  - `Doseresponse_72hrs_YPGlyvsYPD` — YPGly vs YPD, 72-hour timepoint (combined analysis of July 2 and July 20 data)

Dose-response method adapted from the [Babraham Bioinformatics IC50 tutorial](https://www.youtube.com/watch?v=yZRvzYsWqJw).
