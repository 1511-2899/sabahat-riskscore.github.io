# WES Diagnostic Yield Predictor

This is an interactive clinical decision support tool designed to estimate the probability of achieving a positive diagnostic yield from Whole Exome Sequencing (WES) in pediatric patients with suspected genetic disorders.

## 🔍 Purpose

Whole Exome Sequencing is a powerful tool in diagnosing rare genetic conditions. However, given cost and accessibility barriers in resource-limited settings, this model helps clinicians prioritize which patients may benefit the most based on key clinical predictors.

## ⚙️ How to Use

1. Enter the patient’s clinical features into the calculator.
2. Click “Calculate Probability”.
3. The tool will output an estimated likelihood of a positive WES result and categorize the patient into Low, Medium, or High yield group.

## 🧠 Clinical Variables Included

- Age at Onset (in years)
- Syndromic Presentation
- Developmental Delay
- History of Seizures
- Family History of Genetic Disorder
- Parental Consanguinity

These were selected using LASSO regularized logistic regression based on their predictive power in our dataset.

## 📄 Citation & Attribution

This tool was developed by Sabahat Hafeez, Department of Pediatrics and Child Health, Aga Khan University Hospital as part of an academic machine learning project on genetic diagnostics.

Please cite as:

> Hafeez S. et al. WISER: Whole-Exome Interpretation Score for Estimated Results — A Machine Learning–Based Tool to Predict Diagnostic Yield of Whole Exome Sequencing in Pediatric Rare Genetic Disorders. 2025 (preprint/poster/etc.)

## 🔒 Disclaimer

This tool is for research and academic purposes only. It does not replace formal genetic evaluation or clinical decision-making. Please consult a qualified healthcare professional for individual patient assessment.

## 🌐 Deployment

The tool will be live at [link to be inserted] and QR code will be available prior to presentation.
