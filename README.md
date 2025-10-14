# Anomaly Detection in Well Log Data

## Project Overview
This repository contains code, data, and reports for detecting anomalies in well log data using machine learning techniques. The project explores multiple approaches including Autoencoder and Isolation Forest models to identify irregularities in well measurements.

---

## Contents

| Folder/File | Description |
|------------|-------------|
| `plots/` | Contains visualizations and plots generated during analysis. |
| `Anomalies_All_Wells.xlsx` | Excel file summarizing detected anomalies across all wells. |
| `Anomaly Detection.ipynb` | Jupyter notebook with general anomaly detection workflow. |
| `Anomaly_Detection_Isolation_Forest.ipynb` | Notebook implementing Isolation Forest-based anomaly detection. |
| `Auto.ipynb` | Notebook implementing Autoencoder-based anomaly detection. |
| `Well_1_cleaned.csv`, `Well_2_cleaned.csv`, etc. | Cleaned well log data for analysis. |
| `autoencoder_model.h5` | Trained Autoencoder model for anomaly detection. |
| `*.pdf` | Various reports summarizing the results of the analysis. |
| `Anomaly_Summary_All_Wells.csv` | CSV summary of anomalies detected in all wells. |

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/uzakariyya/Anomaly-Detection-Model.git
cd Anomaly-Detection-Model
