# Clinical & Survival Analysis Pipeline for Endometrial Cancer

An R-based biostatistical data pipeline simulating clinical endpoints for endometrial cancer patients, evaluating serum CA-125 biomarker stratification across FIGO stages, and structuring prognostic risk factors.

## 📌 Project Overview
As a Statistics student interested in epidemiology and health data science, I developed this reproducible pipeline to demonstrate how statistical computing can interpret complex oncological data. 

The project focuses on clinical indicator modeling, baseline patient metrics, and advanced data visualization to understand disease progression.

## 📊 Key Features
* **Clinical Data Simulation:** Generates a synthetic cohort ($n=100$) mimicking real-world oncology metrics (age distribution, tumor size, and international FIGO stages).
* **Biomarker Stratification:** Uses `ggplot2` to visualize the distribution and density of Serum CA-125 biomarker levels across different cancer stages using boxplots.
* **Prognostic Framework:** Structuring time-to-event components to analyze overall survival probabilities using `survival` packages.

## 🛠️ Technologies Used
* **Language:** R (v4.6.0)
* **Libraries:** `tidyverse`, `survival`, `survminer`

## 📈 Methodology & Output
The pipeline successfully visualizes the clinical distribution of data. Below is the focus area of the visualization:
* **Serum CA-125 Boxplot:** Explores how clinical markers skew and distribute as the pathological severity (Stage I to Stage IV) changes.

---
*Developed as part of my ongoing research portfolio in Biostatistics and Public Health Analytics.*
