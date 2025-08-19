# 🏠 LeadScorify – AI-Powered Real Estate Lead Scoring Platform  

LeadScorify is an **AI-driven platform** that empowers real estate businesses to prioritize high-value leads using predictive analytics.  
It predicts **ROI**, detects **market hotspots**, and generates **lead scores** automatically from uploaded property data.  

---

## 🚀 Features
- 📊 **AI Lead Scoring** – Dynamic ranking of leads using Random Forest & XGBoost.  
- 💰 **ROI Prediction** – Calculates expected return on investment with >99% accuracy (R² > 0.99).  
- 📍 **Hotspot Detection** – Identifies high-demand property areas (ROC-AUC = 0.85).  
- ⚙️ **Data Pipeline** – Label Encoding, MinMax Scaling, log transforms, and SMOTE for balanced learning.  
- 📈 **Model Validation** – Bootstrap CI (44.49–45.47) ensures prediction stability.  
- 🖥 **Interactive UI** – Streamlit app for CSV upload, insights table, and downloadable results.  
- 🔄 **Scalable Solution** – Easily adaptable to multiple regions and CRM integrations.  

---

## 🛠 Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Imbalanced-learn  
- **Frameworks:** Streamlit (UI), Flask (optional backend API)  
- **Tools:** Git, Jupyter Notebook  

---

## 📂 Project Structure
LeadScorify/
│── data/ # Sample CSV files
│── notebooks/ # Jupyter notebooks (EDA, modeling)
│── src/ # Core scripts (preprocessing, models, evaluation)
│── app/ # Streamlit app files
│── results/ # Output CSVs & evaluation metrics
│── README.md # Project documentation
│── requirements.txt # Python dependencies


---

## ⚡ Installation & Usage
1. **Clone the repo**  
```bash
git clone (https://github.com/Maansitomer/Lead_score_system)
cd LeadScorify
