# Hi, I'm Dorsa Hayati

PhD researcher in bioinformatics at [LUMC](https://www.lumc.nl/) (Leiden University Medical Center), the Netherlands.
I build transcriptomics and machine-learning tools for colorectal cancer, from tumour subtyping to liquid-biopsy biomarkers.

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:dorsa.hayati@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/TODO-LINKEDIN-HANDLE/)
[![GitHub](https://img.shields.io/badge/GitHub-dorsahayati-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dorsahayati)

## About

My research asks how well a cancer signal found in tumour tissue carries over to what can be measured in blood.
I work on RNA-seq data from colorectal cancer: tumour tissue, plasma extracellular-vesicle and cell-free RNA, and whole blood.
I write the code behind each step myself, including QC, differential expression, feature selection and the classifiers used for Consensus Molecular Subtype (CMS) calling and biomarker panels.
I care about reproducible pipelines and honest validation, so a result should hold up on data the model has not seen.

I'm open to conversations about bioinformatics, computational biology and cancer-genomics roles and collaborations.

## Research interests

- Liquid-biopsy transcriptomics (EV-RNA, cfRNA, whole blood)
- Biomarker discovery and cross-sample-type validation
- Molecular subtyping of colorectal cancer (CMS)
- Machine learning on gene-expression data

## Skills

- **Languages:** Python, R, Bash
- **Python:** pandas, NumPy, scikit-learn, XGBoost, PyDESeq2, matplotlib
- **R / Bioconductor:** DESeq2, edgeR, limma, ggplot2
- **Other omics:** single-cell analysis (scanpy, Seurat), variant calling
- **Workflows & compute:** Snakemake, Nextflow, Linux, SLURM (HPC), conda, Docker

## Selected projects

- **[RNA-seq Cancer vs Control Biomarker Pipeline](https://github.com/dorsahayati/RNAseq-data-analysis-pipeline)**:
  a Python pipeline that goes from raw counts to a ranked biomarker panel compared across tumour tissue, plasma and blood.
  It runs QC, PyDESeq2 differential expression, condition × sample-type interaction tests and cross-material validation, then writes a single HTML report.
- **[CMSmark](https://github.com/dorsahayati/CMSmark-AI-based-application)**:
  a GUI application that classifies colorectal tumours into Consensus Molecular Subtypes using trained machine-learning models.
- **[CMSmark-X classifier](https://github.com/dorsahayati/XGBoost-and-MLP-models-for-CMSmark-X-calssifier)**:
  training and testing workflow for the advanced CMSmark-X models (XGBoost and MLP) on gene-expression features.
- **[CMSmark baseline models](https://github.com/dorsahayati/logistic-regression-and-random-forest-model-for-CMSmark)**:
  logistic-regression and random-forest baselines for CMS classification.
- **[CMS feature selection pipeline](https://github.com/dorsahayati/feature_selection_pipeline)**:
  finds CMS-specific gene markers in colorectal cancer RNA-seq by screening with Pearson correlation, ANOVA F-tests and mutual information.

## Experience

| Role | Organization | When |
|---|---|---|
| PhD researcher, bioinformatics | Leiden University Medical Center (LUMC) | TODO |

## Get in touch

The fastest way to reach me is by [email](mailto:dorsa.hayati@gmail.com).
For questions about one of my tools, please open an issue in that repository.
