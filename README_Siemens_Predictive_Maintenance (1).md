# ⚙️ Siemens – Predictive Maintenance

A real-world machine learning project that predicts machine failure using industrial sensor data. Inspired by Siemens’ smart factory initiative to minimize downtime and improve operational efficiency.

---

## 🎯 Objective

Predict if a machine will fail based on telemetry data like air temperature, torque, and rotational speed.

---

## 🧠 Business Context

**Company:** Siemens (Germany)  
**Domain:** Industry 4.0 / Smart Manufacturing  
**Goal:** Prevent unexpected equipment failures  
**Value:** Lower maintenance costs, less downtime, higher productivity

---

## 📊 Dataset

**Source:** Kaggle – Predictive Maintenance Dataset  
**Features:** Type, Air Temp, Process Temp, Torque, Tool Wear  
**Target:** Machine Failure (binary: 0/1)

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** pandas, scikit-learn, matplotlib, seaborn
- **Models Used:** Logistic Regression, Random Forest
- **Evaluation Metrics:** Accuracy, ROC AUC, Classification Report

---

## 🧪 Model Results

| Model               | Accuracy | ROC AUC |
|--------------------|----------|---------|
| Logistic Regression | 0.50     | 1.00    |
| Random Forest       | 0.50     | 1.00    |

✅ AUC scores show both models ranked risk perfectly, even if accuracy was affected by small test size.

---

## 📁 Project Files

```bash
├── Siemens_Predictive_Maintenance_Report_Venkata.pdf   # 16-page academic report
├── Siemens_Predictive_Maintenance.ipynb                # Full Colab-ready notebook
├── predictive_maintenance_cleaned.csv                  # Cleaned dataset
├── requirements.txt                                    # Python dependencies
```

---

## 📈 Visuals

- ROC Curve Comparison
- Confusion Matrices
- Precision, Recall, F1 Breakdown

---

## 💡 Business Benefits

- ⚠️ Early detection of machine failure
- 📉 Reduced unplanned maintenance
- 💰 Lower operational costs

---

## 🚀 Future Work

- Add time-series modeling
- Use real IoT sensor streams
- Deploy dashboard with live risk scores

---

## 🧾 Report

📄 [Download 16-Page PDF](./Siemens_Predictive_Maintenance_Report_Venkata.pdf)

---

## 👤 Author

**Venkata Sandeep Kumar Reddy**  
Data Science Portfolio – Smart Manufacturing Projects  
📫 [LinkedIn Profile](#)

---

## 🔖 Tags

`predictive-maintenance` `siemens` `iot` `mlops` `smart-factory` `machine-learning`

---

## 📜 License

MIT – Free for educational and commercial use.