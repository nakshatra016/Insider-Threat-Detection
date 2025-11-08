# Insider-Threat-Detection
Insider Threat Detection using Behavioral Data Analysis with Unsupervised Learning and Interactive Dashboards

# 🛡️ Insider Threat Detection Dashboard

This project detects abnormal insider activities in defense organizations using unsupervised learning and interactive dashboards.

## 🚀 Features
- Synthetic behavioral dataset (3,500 records, 10% anomalies)
- Data cleaning, EDA, and unsupervised anomaly detection
- Isolation Forest, LOF, and DBSCAN models
- Ensemble anomaly scoring (`anom_rank`)
- Interactive dashboard built with Plotly & Dash
- Standalone browser-based visualization (HTML)

## 🧠 Tech Stack
**Python Libraries:**  
`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `plotly`, `dash`, `nbformat`, `shap`

**Tools:** Google Colab, Jupyter, HTML/JS (Plotly.js)

## 📊 Data Summary
| Property | Description |
|-----------|--------------|
| Records | 3,500 |
| Features | 10 (logins, files, emails, privileges, etc.) |
| Missing Values | ~8% |
| Anomalies | 10% (synthetic) |

## 📈 Visualizations
- **Bar chart:** Top users with flagged anomalies  
- **Scatter plot:** Files accessed vs emails sent  
- **Heatmap:** Weekly file access pattern  

## ⚙️ How to Run
1. Open `notebooks/insider_threat_detection_v5.ipynb` in Colab.  
2. Run all cells to generate `anomaly_results_v5.csv`.  
3. Open `dashboard/insider_dashboard.html` in a browser.  
4. Upload the CSV (or click *Use Sample Data*).  

## 📦 Requirements
See `requirements.txt`

## 🧩 Future Work
- Integrate real CERT/LANL datasets  
- Add NLP-based insider risk scoring  
- Deploy via SIEM system or Azure Functions  

## 👨‍💻 Authors
Nakshatra R
Anumitha Rajesh
Ashwitha M

---

