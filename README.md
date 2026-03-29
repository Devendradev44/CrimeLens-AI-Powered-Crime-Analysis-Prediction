# 🚨 CrimeLens: AI-Powered Crime Analysis & Prediction

## 🌐 Live Demo

🔗 https://crimelensunravel.netlify.app/

---

## 📌 Project Overview

CrimeLens is a machine learning-based project that analyzes crime data across Indian states and predicts whether a region falls under **High Crime** or **Low Crime** category.

The system uses real-world datasets (Murder, Fraud, Auto Theft) and applies **ensemble learning techniques** to improve prediction accuracy. It also includes **data visualization and optional geo-mapping** for deeper insights.

---

## 🎯 Objectives

* Analyze real-world crime datasets
* Perform data cleaning and preprocessing
* Build a robust ML classification model
* Visualize crime patterns and correlations
* Predict high-crime regions using ensemble models
* Deploy the solution as a live web application

---

## ✨ Key Features

* 📊 Crime trend analysis across states
* 🤖 ML-based classification (High Crime vs Low Crime)
* ⚡ Ensemble model (Random Forest + Gradient Boosting)
* 📈 Interactive visualizations (bar charts, heatmaps)
* 🗺️ Geo-based crime mapping (optional)
* 🌐 Live deployment using Netlify

---

## 🧠 Machine Learning Models Used

* Random Forest Classifier
* Gradient Boosting Classifier
* Voting Classifier (Ensemble Model)

---

## 📊 Features Used

### Input Features:

* Murder cases
* Fraud cases
* Auto theft cases

### Engineered Feature:

* **Total Crime = Murder + Fraud + Theft**

### Target Variable:

* **High Crime (1)** → Above median crime
* **Low Crime (0)** → Below median crime

---

## 🏗️ Project Workflow

1. 📂 Data Collection (CSV files)
2. 🧹 Data Cleaning & Preprocessing
3. 🧮 Feature Engineering (Total Crime)
4. 🤖 Model Training (Ensemble Model)
5. 📊 Model Evaluation (Accuracy, Confusion Matrix)
6. 📈 Data Visualization
7. 🌍 Geo Visualization (optional using shapefiles)
8. 🚀 Deployment (Netlify)

---

## ⚙️ Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
* **Geo Visualization:** GeoPandas
* **Environment:** Google Colab
* **Deployment:** Netlify

---

## 📂 Project Structure

```
crime-analysis-ml/
│── data/                # Dataset files (CSV)
│── notebooks/           # Jupyter/Colab notebooks
│── images/              # Screenshots of outputs
│── README.md
│── requirements.txt
```

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/crime-analysis-ml.git
cd crime-analysis-ml
```

### 2️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run the Project

* Open in Google Colab or Jupyter Notebook
* Upload required CSV files:

  * Murder dataset
  * Fraud dataset
  * Auto theft dataset
* (Optional) Upload India shapefile (.shp, .shx, .dbf)
* Run all cells

---

## 📈 Output

* ✅ Model Accuracy
* 📊 Classification Report
* 🔢 Confusion Matrix
* 📉 Correlation Heatmap
* 📊 State-wise Crime Comparison
* 🗺️ Crime Intensity Map (Geo Visualization)

---

## 📸 Project Preview

> Add screenshots from your project here

```
![Confusion Matrix](images/confusion.png)
![Heatmap](images/heatmap.png)
![Bar Chart](images/barchart.png)
```

---

## 🔮 Future Improvements

* 🔹 Add more crime categories
* 🔹 Build a real-time data pipeline
* 🔹 Deploy using Streamlit / Flask
* 🔹 Improve model with Deep Learning
* 🔹 Add user input-based prediction system

---

## 💼 Resume Description

Built a crime analysis and prediction system using ensemble machine learning models (Random Forest + Gradient Boosting), integrating real-world datasets and interactive visualizations, and deployed using Netlify.

---

## 👨‍💻 Author

**Devendra Pujari**

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
