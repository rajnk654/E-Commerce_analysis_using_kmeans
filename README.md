
# E-Commerce Customer Analysis using K-Means

## 📌 Project Overview
This project analyzes e-commerce customer data to **segment customers** using the **K-Means clustering algorithm**.  
The goal is to **identify patterns** in customer behavior to help businesses improve marketing and sales strategies.

---

## 🛠️ Technologies Used
- **Python**  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – K-Means clustering  

---

## 🔍 Dataset
- Source: E-Commerce customer data (CSV file)  
- Key features:
  - `CustomerID` – Unique ID for each customer
  - `Gender` – Male / Female
  - `Age` – Customer age
  - `Annual Income (k$)` – Customer income
  - `Spending Score (1-100)` – How much the customer spends  

---

## 📊 Steps Performed

1. **Data Exploration & Cleaning**
   - Checked for missing values
   - Explored distributions of features
   - Visualized relationships between variables

2. **Data Visualization**
   - Histograms for age, income, and spending score
   - Scatter plots to detect clusters
   - Pairplots for feature correlation

3. **Feature Scaling**
   - Standardized numerical features to improve K-Means performance

4. **K-Means Clustering**
   - Used the **Elbow Method** to find the optimal number of clusters
   - Applied K-Means clustering
   - Assigned cluster labels to customers

5. **Cluster Analysis**
   - Visualized clusters in 2D/3D scatter plots
   - Interpreted customer segments based on income and spending score

---

## Requirements

- Python 3.7+  
- pandas, numpy, matplotlib, seaborn, scikit-learn  

Install dependencies:

```bash
pip install -r requirements.txt

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/rajnk654/E-Commerce_analysis_using_kmean.git
