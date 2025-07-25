# Differential Gene Expression in SV/HLHS Patients

This repository provides interactive visualizations of differential gene expression across 15 immune cell types, derived from single-cell RNA sequencing (scRNA-seq) of peripheral blood mononuclear cells (PBMCs) in patients with Single Ventricle / Hypoplastic Left Heart Syndrome (SV/HLHS).

The data includes two searchable gene expression tables:

- 🔗 **[Main DE Genes Table](https://huiqi-qu.github.io/SV_HLHS_DE_genes/index.html)** — Log₂ fold changes for 6,660 genes across immune cell types
- 🔗 **[Opposite-Direction DE Genes Table](https://huiqi-qu.github.io/SV_HLHS_DE_genes/opposite.html)** — Subset of 822 genes showing opposite regulation across different cell types

Each table allows users to search by gene name, filter by cell type, and explore expression patterns interactively.

## Data Description

- **Rows**: Genes
- **Columns**: Cell types (e.g., B cells, monocytes, CD4+ and CD8+ T cell subsets)
- **Values**: Log₂ fold changes between SV/HLHS patients and controls

Missing values indicate no significant expression difference in that cell type. Column headers have been simplified to remove formatting issues (e.g., no commas or superscripts).

## Reference

Qu HQ, Ostberg K, Slater DJ, Wang F, Snyder J, Hou C, Connolly JJ, March M, Glessner JT, Kao C, Hakonarson H.  
**Single-cell RNA Sequencing of Peripheral Blood Mononuclear Cells in Patients with Single Ventricle/Hypoplastic Left Heart Syndrome.** *Journal of Gene Medicine.*

