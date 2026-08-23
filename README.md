# Automated ML Evaluation & PDF Reporting

## Overview

This project combines Machine Learning with Python automation to
automatically evaluate a classification model and generate a
professional PDF report from its results.

Instead of manually inspecting ML metrics and charts in a notebook,
the workflow collects the results and automatically produces a
structured report containing the important findings.

---

## Problem

During ML model development, a single experiment can produce many
results:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Feature Importance
- Visualizations
- Model findings

Manually organizing these results into a report is repetitive.

This project automates that reporting process.

---

## Solution

The workflow is:

```text
Dataset
   ↓
Random Forest Model
   ↓
Predictions
   ↓
Model Evaluation
   ↓
Metrics & Visualizations
   ↓
Automated Report Generation
   ↓
PDF Report
