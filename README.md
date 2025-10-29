# 🩺 HealthLens AI: Disease Prediction from Symptoms

**Author:** D. R. Suja  
**Internship:** Data Science Internship 
---

## 📘 Project Overview
**HealthLens AI** is an AI-powered disease prediction system that uses **machine learning algorithms** to predict possible diseases based on user-reported symptoms.  
The project demonstrates how **data science** and **machine learning** can enhance healthcare through **early disease detection**, **predictive analytics**, and **interactive dashboards**.

It integrates:
- **Python** for model development  
- **Streamlit** for web-based user interaction  
- **Power BI** for data visualization  
- **Google Maps** for hospital recommendations  

This project bridges the gap between raw medical data and practical healthcare insights.

---

## 🧠 Objectives
- Develop a machine learning model to predict diseases based on symptoms.  
- Compare multiple algorithms — *Linear Regression, Decision Tree, Logistic Regression, KNN, Naive Bayes, Random Forest* — to identify the best performer.  
- Create a user-friendly **Streamlit** web application for real-time disease prediction.  
- Use **Power BI dashboards** to visualize disease trends and insights.  
- Support healthcare decision-making by suggesting treatments and nearby hospitals.  

---

## ⚙️ System Workflow
1. User enters symptoms through the **Streamlit interface**.  
2. The system preprocesses the input and encodes it for model prediction.  
3. The **K-Nearest Neighbors (KNN)** algorithm predicts the most probable disease.  
4. The app displays the result, with insights and Power BI dashboards.  
5. The system also provides treatment info and nearby hospital details using Google Maps.

---

## 🧩 Technologies Used

| Category | Tools / Libraries |
|-----------|------------------|
| **Programming Language** | Python |
| **Machine Learning** | Scikit-learn, Pandas, NumPy |
| **Visualization** | Power BI, Matplotlib, Seaborn |
| **Frontend** | Streamlit |
| **Deployment** | Pyngrok |
| **Database** | SQL |
| **Maps Integration** | Google Maps API |

---

## 📊 Machine Learning Models
The following algorithms were tested and compared:
| Model | Accuracy |
|--------|-----------|
| Linear Regression | 0.615 |
| Decision Tree | 0.654 |
| Logistic Regression | 0.632 |
| **K-Nearest Neighbors (KNN)** | **0.679 (Best)** |
| Naive Bayes | 0.641 |
| Random Forest | 0.666 |

✅ **KNN achieved the highest accuracy of 67.9%**, offering a balance between interpretability and performance.

---

## 🌐 Streamlit App Features
- 🔹 **Real-time disease prediction** from user symptoms.  
- 📊 **Visualization** of Chronic vs Contagious diseases.  
- 💊 **Treatment and cost details** for common diseases.  
- 🌱 **Health tips** for daily well-being.  
- 🏥 **Hospital booking system** and appointment record management.  

Run the Streamlit app with:
```bash
streamlit run healthlens_app.py
