# BMIN5030 Final Project - Exploring Association between Early Antibiotic Administration and Improved Outcomes in Sepsis Treatment: A MIMIC-IV Analysis

## Key Files:
* `Association between TTA and Improved Outcomes.qmd`: The main R notebook for analysis.
* `Association between TTA and Improved Outcomes.html`: The rendered report.

## Prerequisite:
* **MIMIC-IV Data:**
  * **Demo Version:** used for dictionary for final pipeline.
  * **Full Version:** Required to reproduce the complete analysis and final results.

* **R Packages:**
`tidyverse` (includes dplyr, ggplot2, tidyr, lubridate, stringr, etc.),`zoo`,`gridExtra`,`scales`,`table1`,`broom`,`DBI`,`bigrquery`

## Overview

This project primarily investigates the association between early antibiotic administration and patient outcomes among ICU patients diagnosed with sepsis using the MIMIC-IV dataset. The study aims to evaluate whether earlier intervention is associated with improved outcomes which is defined through a range of metrics, such as in-hospital mortality rate, ventilator-free days, and organ dysfunction progression. The goal is to identify potential clinical implications for optimizing the sepsis management processes. Some of these discrepancies stem from challenges in accurately defining the onset of sepsis, handling the time discretization for data analysis, or confounding factors such as illness severity and treatment bias. The analysis reveals that while a linear relationship between time-to-antibiotics and mortality was trivial, delayed treatment posits a negative effect on the patient outcomes; also a threshold-based analysis suggests a significant protective effect for treatment administered within one hour of sepsis onset.

## Introduction
Sepsis is a leading cause of death in intensive care units (ICUs) and continues to pose major challenges to clinicians due to its complexity. Early antibiotic administration has long been considered a cornerstone of sepsis treatment, based on evidence suggesting that delays in treatment may increase mortality and worsen organ function. This concept is often operationalized as the “Golden Hour”, emphasizing immediate intervention upon sepsis onset. However, the optimal timing of antibiotic administration remains controversial, as observational studies have produced mixed results. Specifically, there are strong controversies around the risk of over-resuscitation and implementation challenges.

This project is interdisciplinary, combining insights from biomedical informatics, clinical medicine, and data science. From a clinical perspective, the project draws on principles of critical care and infectious disease management to define sepsis onset, select relevant outcomes, and interpret physiological indicators such as acuity scores (e.g. SOFA) trajectories; from a informatics standpoint, it involves working with high-dimensional EHR data and addressing issues such as timestep discretization and alignment, modeling, and the mitigation of confounding factors such as illness severity and treatment bias.
