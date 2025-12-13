# BMIN5030 Final Project
## Direct cost of Glaucoma Treatment and Management by Disease Severity

## Overview

Glaucoma is a leading cause of irreversible vision loss worldwide and represents a growing public health issue and economic burden in the United States. Primary open-angle glaucoma (POAG), the most common subtype, is a progressive optic neuropathy that usually remains asymptomatic until significant visual field loss has occurred. And with increasing in the disease severity, the patients require more monitoring, medical and surgical interventions, all of which contribute to rising healthcare costs.

Understanding how costs accumulate across mild, moderate, and severe stages of disease is essential for optimizing the allocation of resources cost-effective care delivery, and the development of personalized management strategies.

This project highlights the direct medical costs associated with POAG management at a single eye center, stratified by disease severity. Through quantifying of costs related to encounter visits, medications, and procedures, this project aims to provide an insight how the costs of this disease evlove between stages as it's progress.

## Methods Summary

* Retrospective, single-center analysis of patients diagnosed with  POAG

* Disease severity classified using ICD-10 codes based on worst-eye severity

* Direct medical costs calculated for encounters, medications, and procedures

* Logistic regression used to evaluate demographic predictors of severe glaucoma

* Model discrimination assessed using receiver operating characteristic (ROC) analysis and area under the curve (AUC)


## Repository Contents

* final_project_5030_Saeed.qmd
Quarto source file containing the full analysis workflow, including data preprocessing, cohort selection, cost calculations, statistical modeling, and visualizations.

* final_project_5030_Saeed.html
Rendered HTML report presenting the complete results, figures, and interpretations.

* README.md
Project overview and description of repository contents.

* BMIN5030_Final_Project.Rproj
RStudio project file used to organize and run the analysis.

* .gitignore
Git configuration file specifying files excluded from version control.

Note: Raw patient-level datasets are not included in this repository. All analyses were conducted on de-identified data processed locally.

<!-- Links -->
[forking]: https://guides.github.com/activities/forking/

