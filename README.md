# Reanalyzing scRNA-seq dataset of glioblastomas from Neftel et al.

In the Jupyter notebooks in this repository, I have reanalyzed the SMART-Seq2 data from Neftel, Laffy, et al. 2019, [An Integrative Model of Cellular States, Plasticity, and Genetics for Glioblastoma](https://www.cell.com/cell/fulltext/S0092-8674(19)30687-7).

I have provided a .csv file of the meta-modules identified by Neftel et al. The raw file, which is used at the beginning of Part 1, is available through the Broad Institute Single Cell Portal (https://portals.broadinstitute.org/single_cell/study/SCP393/single-cell-rna-seq-of-adult-and-pediatric-glioblastoma).

Some code is borrowed and modified from [the Single-cell best practices book](https://www.sc-best-practices.org/), especially in Part 1.

## Contents

[Part 1: Finding Malignant Cells](./Part1_FindingMalignantCells.ipynb) details quality control, normalization, and dimensionality reduction of the dataset, as well as identifying the malignant cells and filtering the dataset to only contain those cells.

[Part 2: Exploring Malignant Cells](./Part2_ExploringMalignantCells.ipynb) details the exploration of the dataset, especially in terms of the cellular states identified by Neftel et al., using the defined meta-modules from the paper. Finally, it also shows identification of cell subtypes and identification of hybrid cell subtypes.

## References

Neftel C, Laffy J, Filbin MG, et al. An Integrative Model of Cellular States, Plasticity, and Genetics for Glioblastoma. Cell (2019). https://doi.org/10.1016/j.cell.2019.06.024

Heumos L, Schaar AC, Lance C, et al. Best practices for single-cell analysis across modalities. Nat Rev Genet (2023). https://doi.org/10.1038/s41576-023-00586-w

Li Q, Aishwara S, Li J, et al. Gene Expression Profiling of Glioblastoma to Recognize Potential Biomarker Candidates. Frontiers in Genetics (2022). https://doi.org/10.3389/fgene.2022.832742