# Boston House Pricing Prediction

**Author:** Shivam Shende  
**Role:** Data Analyst | SQL · Python · Power BI · Machine Learning  
📍 Finance & Operations Analytics  

---

## 🚀 Why This Project Matters
This project demonstrates an end-to-end Machine Learning workflow — from data exploration and feature analysis to model deployment. The focus is on building an interpretable model that supports real-world business and decision-making use cases.

---

## 📌 Project Overview
A Machine Learning web application that predicts housing prices using **Linear Regression** trained on the Boston Housing dataset. The trained model is deployed using **Flask** to enable real-time predictions via a web interface.

---

## 🎯 Business Problem
Accurate house price estimation is essential for:
- Real estate valuation
- Investment decision-making
- Risk assessment
- Urban planning insights

This project identifies key price drivers and delivers interpretable predictions suitable for stakeholder use.

---

## 🧠 Analytics Workflow

### 1️⃣ Data Exploration & Preparation
- Dataset inspection and summary statistics
- Missing value and outlier analysis
- Correlation analysis and feature relationships
- Data preparation for modeling

### 2️⃣ Feature Insights
- **RM (Average number of rooms):** Strong positive impact on house price
- **LSTAT (% lower status population):** Strong negative impact
- Environmental and neighborhood factors significantly influence pricing

### 3️⃣ Model Building
- Algorithm: **Linear Regression**
- Focus on interpretability and business relevance
- Feature importance and coefficient analysis

---

## 📊 Model Performance

| Metric | Value |
|------|------|
| R² Score | 0.71 |
| MAE | 3.16 |
| RMSE | 4.64 |

The model achieves a strong balance between accuracy and interpretability.

---

## 🌐 Web Application
- Built using **Flask**
- User-friendly input form
- Real-time house price prediction
- Model serialized using **Pickle**

---

## ⚙️ Tech Stack
- Python (Pandas, Numpy, scikit-learn, matplotlib, Seaborn)
- Flask (for web app)
- HTML templates
- Pickle (for model serialization)
## Software and Tools Requirments

1. [Github Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```
conda create -p venv python==3.7 -y 
```
