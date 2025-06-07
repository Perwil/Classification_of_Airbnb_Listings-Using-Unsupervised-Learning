# 🏠 Unsupervised Learning & Classification of Airbnb Listings with Scikit-learn

This project is part of **Week 4** of the *Python for Machine Learning* course by Uplimit. In this final project, we combine everything we've learned in the course—preprocessing, clustering, classification, pipelines, and deployment—to explore and model Airbnb listings data using **unsupervised** and **supervised** machine learning techniques.

---

## 📌 Project Highlights

- 💡 Cluster Airbnb listings using **KMeans** (unsupervised learning)
- 🎯 Use cluster labels to build a **classification model** (supervised learning)
- ⚙️ Built with **Scikit-learn Pipelines** and **ColumnTransformers**
- 📊 Visualizations powered by **Plotly**
- 🚀 Designed to be deployed as a **Streamlit App**
- 📁 Hands-on with custom dataset preprocessing and feature engineering

---

## 📂 Dataset

The dataset includes cleaned Airbnb listings and is loaded via `pickle` files from Google Drive. It contains features like:

- Room type
- Price
- Location coordinates
- Number of reviews
- Availability and more

---

## 🧠 Technologies Used

- `pandas` for data manipulation  
- `scikit-learn` for preprocessing, clustering, and classification  
- `plotly` for interactive data visualization  
- `pickle` for data storage and loading  
- `Streamlit` (optional) for UI deployment

---

## 🧪 How It Works

1. **Data Loading & Cleaning**
   - Load listing data from `pickle` files
   - Perform exploratory analysis and feature engineering

2. **Unsupervised Learning**
   - Apply KMeans clustering
   - Analyze cluster composition and relationships

3. **Supervised Learning**
   - Use cluster labels as pseudo-targets
   - Build classification models using pipelines
<img src="https://github.com/Perwil/Classification_of_Airbnb_Listings-Using-Unsupervised-Learning/blob/main/Pipeline.png" alt="Pipelines" width="400"/>   

4. **Model Evaluation**
   - Compare model accuracy
   - Visualize predictions and decision boundaries

---

## 🚀 Getting Started

### ✅ Prerequisites

Install the required libraries:

```bash
pip install -r requirements.txt
