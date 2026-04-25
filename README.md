# Pupillography-Based Machine Learning Analysis for Multiple Sclerosis

This repository contains the anonymized code, analysis outputs, and supplementary files supporting the manuscript:

**Exploratory Analysis of Pupillography-Based Machine Learning for Detecting Autonomic Dysfunction in Patients with Multiple Sclerosis**

## Repository Contents

### 1. `ms_pupillography_ml_completed_updated2.zip`
This file contains the main machine learning pipeline, including feature extraction, model training, evaluation scripts, and publication-related figures.

### 2. `Clinical_Validation_Results_Complete.zip`
This file contains the independent validation analysis, including the confusion matrix, ROC analysis, performance comparison, and validation metrics.

The updated performance values are:

| Dataset | Accuracy | Sensitivity | Specificity | AUC-ROC |
|---|---:|---:|---:|---:|
| Test Set | 89.3% | 93.8% | 83.3% | 94.5% |
| Independent Test Set | 75.0% | 88.9% | 57.1% | 62.7% |

### 3. `demegraphic_EDSS_study.zip`
This file contains the demographic, EDSS correlation, and disease-duration subgroup analyses. The analyses include:

- Correlation between extracted pupillography features and EDSS
- Feature–clinical variable correlation matrix
- Early MS versus late MS subgroup comparison

### 4. `ms_pupillografi_anonymized.xlsx`
This file contains the anonymized clinical/demographic information used for analysis. Patient identifiers were anonymized using folder-level IDs such as:

- `1_ms`, `2_ms`, ..., `25_ms` for MS patients
- `HC_001`, `HC_002`, ..., `HC_038` for healthy controls

No real patient names are included.

## Data Privacy and Availability

Raw clinical data and original pupillography images are not publicly shared due to ethical and privacy restrictions. Only anonymized analysis files and reproducible code are provided in this repository.

The full dataset may be made available from the corresponding author upon reasonable request, subject to ethical approval and institutional data-sharing regulations.

## Software and Dependencies

The analyses were performed using Python and common scientific libraries, including:

- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- OpenCV
- SciPy

Relevant scripts and package information are included in the ZIP files.

## Purpose of This Repository

This repository was prepared to support transparency and reproducibility during peer review. It provides the code, anonymized analysis outputs, and figures used in the manuscript revision process.

## Citation

If this repository is used, please cite the associated manuscript once published.
