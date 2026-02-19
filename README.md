# Predicting Applicant Withdrawal Risk – TFA Case (R)

## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Techniques & Methods](#techniques--methods)
- [Repository Structure](#repository-structure)
- [Tools & Libraries](#tools--libraries)
- [Key Outcomes](#key-outcomes)
- [Usage](#usage)
- [License](#license)

---

## Project Overview
This project focuses on predicting applicant withdrawal risk in the TFA admissions process using R. The goal is to analyze factors influencing withdrawal and build machine learning models that support proactive admissions strategies.

---

## Objective
- Identify applicants likely to withdraw early from the admissions pipeline.
- Enable better resource planning and improve engagement with candidates.
- Provide insights for data-driven admissions strategies.

---

## Techniques & Methods
- Exploratory Data Analysis (EDA)
- Handling imbalanced datasets using:
  - **Downsampling**
  - **Upsampling**
- Building and evaluating multiple classification models in R
- Performance evaluation using:
  - Confusion matrices
  - Accuracy
  - Sensitivity
  - Specificity

---

## Repository Structure
```
TFA-Withdrawal-Risk/
│
├── R-Scripts/                    # Folder containing R scripts
│   ├── upsampling.R              # Implements upsampling and model training
│   └── downsampling.R            # Implements downsampling and performance comparison
│
├── Reports/                      # Folder containing reports and outputs
│   └── TFA-Predictive_Analytics_R.pdf  # Final report summarizing analysis & results
│
└── README.md                     # Project documentation
```

---

## Tools & Libraries
- **R Packages:** caret, C50, e1071, kernlab, class, nnet, NeuralNetTools

---

## Key Outcomes
- Compared downsampling and upsampling techniques for imbalanced datasets.
- Identified the best-performing model to predict applicant withdrawal risk.
- Improved reliability of predictions for proactive admissions engagement.

---

## Usage
The original dataset used in this project is proprietary and cannot be shared publicly. 

To replicate the analysis or run the R scripts:

1. Prepare your own dataset with a similar structure (applicant features and withdrawal label).
2. Place your dataset in the `R-Scripts/` folder.
3. Open R or RStudio.
4. Update the file path in the R scripts (`upsampling.R` or `downsampling.R`) to point to your dataset.
5. Run the scripts to perform preprocessing, model training, and evaluation.

Note: The scripts include handling of imbalanced datasets (upsampling and downsampling) and classification model evaluation.



## Repository Structure
