# 🛢️ Machine Learning-Based Anomaly Detection in Well Log Data

## 🔍 Project Overview
This project presents a **prototype application** for detecting anomalies in **well log data** using **Machine Learning (ML)** techniques.  
The goal is to identify irregular readings in geophysical well logs that may indicate lithological changes, borehole instability, or sensor errors.  

Two complementary models were implemented:
- **Isolation Forest (IF)** – a tree-based unsupervised algorithm that isolates outliers efficiently.  
- **Autoencoder (AE)** – a neural network-based approach that reconstructs normal patterns and flags deviations as anomalies.  

Both methods were compared across multiple wells to assess performance, anomaly overlap, and feature influence.

---

## 📁 Repository Structure

| Folder/File | Description |
|--------------|-------------|
| `plots/` | Contains visualizations and plots generated during analysis. |
| `data/` | Cleaned well log datasets (`Well_1_cleaned.csv`, `Well_2_cleaned.csv`, etc.). |
| `models/autoencoder_model.h5` | Trained Autoencoder model for anomaly detection. |
| `notebooks/Anomaly_Detection_Isolation_Forest.ipynb` | Isolation Forest anomaly detection workflow. |
| `notebooks/Autoencoder_Anomaly_Detection.ipynb` | Autoencoder training and reconstruction analysis. |
| `Anomalies_All_Wells.xlsx` | Detailed metrics of anomalies for each well. |
| `Anomaly_Summary_All_Wells.csv` | Consolidated summary of anomaly results across all wells. |
| `Prototype_Report.pdf` | Final report (includes plots, tables, and visual validation). |

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/uzakariyya/Anomaly-Detection-Model.git
cd Anomaly-Detection-Model
pip install -r requirements.txt
