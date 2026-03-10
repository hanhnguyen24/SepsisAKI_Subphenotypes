

# Sepsis-AKI Subphenotype Clustering Analysis

## Overview

This repository provides a **representative analysis pipeline** used in the manuscript to identify subphenotypes of sepsis-associated acute kidney injury (SAKI) using proteomic biomarker data.

The code demonstrates the main analytical workflow used in the study, including:

* Ensemble clustering
* Cluster evaluation
* Biomarker heatmap visualization
* Principal component analysis (PCA)
* Survival analysis
* Clinical outcome comparison
* Pathway enrichment analysis
* Figure generation

---

## Repository contents

```
clustering_analysis.Rmd
README.md
```

`clustering_analysis.Rmd` contains the R Markdown script illustrating the analysis pipeline used to generate the main results and figures described in the manuscript.

---

## Important note

This repository **does not contain the complete internal analysis codebase** used in the project.
Instead, it provides a **simplified pipeline illustrating the core analytical steps** described in the manuscript.

Project-specific scripts, intermediate preprocessing steps, and internal utilities used during the full study are not included.

---

## Data availability

The datasets used in this study contain **protected patient information** and cannot be publicly released due to institutional privacy regulations and data-use agreements.

Therefore, this repository provides the **analysis pipeline only**, without patient-level data.

---

## Software

The analysis was conducted in **R** using commonly used statistical and visualization packages, including:

* tidyverse
* diceR
* survival / survminer
* clusterProfiler
* pheatmap
* EnhancedVolcano
* ggplot2 and related visualization packages

---

## Code availability

The pipeline used to perform the clustering and downstream analyses described in the manuscript is available in this repository.

---

