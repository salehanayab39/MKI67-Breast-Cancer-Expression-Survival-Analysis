# MKI67-Breast-Cancer-Expression-Survival-Analysis
Analysis of MKI67 gene expression and overall survival in breast cancer using GEPIA2.
Project Overview
This project investigates MKI67 gene expression in breast invasive carcinoma (BRCA) and explores its association with overall survival using GEPIA2.

Objectives

- Compare MKI67 expression between breast tumour and normal samples.
- Explore the relationship between MKI67 expression and overall survival.

Methods

- Platform: GEPIA2
- Gene: MKI67
- Cancer type: BRCA (Breast Invasive Carcinoma)
- Expression comparison: 1,085 tumour samples and 291 normal samples.
- Survival analysis: Kaplan–Meier analysis using median expression split.

Results

1. Tumour vs Normal Expression

MKI67 expression was higher in tumour samples compared with normal samples.

"MKI67 Tumour vs Normal" (Figure 1 MKI67_boxplot_Tumour vs normal.png)

2. Overall Survival Analysis

- High-expression group: 534 patients.
- Low-expression group: 535 patients.
- Hazard ratio: 1.1.
- Log-rank p-value: 0.51.

The survival analysis did not show a statistically significant difference between the two groups.

"MKI67 Overall Survival" (figure 2 MKI67_overall survival.png)

Conclusion

MKI67 showed higher expression in breast tumour samples than in normal samples. However, the median-split overall survival analysis did not demonstrate a statistically significant survival difference. These findings distinguish differential expression from evidence of prognostic significance.

Limitations

- Analysis relied on publicly available datasets through GEPIA2.
- Survival findings depend on the selected expression cutoff.
- Association does not establish causation.

Tools

GEPIA2, gene-expression analysis, Kaplan–Meier survival analysis, data visualisation.
