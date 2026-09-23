# Smart Manufacturing Predictive Maintenance

## 📌 Project Overview

Smart Manufacturing Predictive Maintenance is a machine learning project focused on predicting potential machine failures before they occur.

The project uses the **AI4I 2020 Predictive Maintenance Dataset** to analyze machine operating conditions and build machine learning models for predictive maintenance. The objective is to reduce unexpected machine downtime and support data-driven maintenance decisions.

## 🎯 Objectives

* Analyze manufacturing machine sensor data.
* Perform data preprocessing and exploratory data analysis.
* Handle missing values and prepare the dataset for machine learning.
* Apply **dimensionality reduction** where appropriate.
* Build and evaluate regression and classification models.
* Predict machine failure and related maintenance outcomes.
* Compare different machine learning approaches.
* Develop a foundation for a smart manufacturing predictive maintenance system.

## 📊 Dataset

The project uses the **AI4I 2020 Predictive Maintenance Dataset**.

Important features include:

* Air temperature
* Process temperature
* Rotational speed
* Torque
* Tool wear
* Machine type
* Machine failure
* Different failure-mode indicators

The dataset is available in the `Datasets/` directory.

## 🧠 Machine Learning Techniques

The project explores multiple machine learning approaches, including:

### Classification

Classification models are used to predict whether a machine is likely to experience failure.

Examples include:

* Naive Bayes
* Decision Tree
* Other classification algorithms explored in the notebooks

### Regression

Regression techniques are explored to predict continuous machine-related values and study relationships between features.

### Clustering

Clustering techniques are used to explore patterns and group similar machine operating conditions.

### Dimensionality Reduction

Dimensionality reduction techniques can be used to reduce the number of features while preserving important information, making the dataset easier to analyze and visualize.

## 📁 Project Structure

```text
Smart-Manufacturing-Predictive-Maintenance/
│
├── app/
│   └── Application files
│
├── Datasets/
│   ├── AI4I-PMDI.csv
│   ├── ai4i2020.csv
│   └── ai4i+2020+predictive+maintenance+dataset/
│
├── models/
│   └── Trained machine learning models
│
├── notebooks/
│   ├── classification_4.ipynb
│   └── regression_1.ipynb
│
├── requirements.txt
├── .gitignore
└── README.md

## ⚙️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* Machine Learning
* Data Preprocessing
* Exploratory Data Analysis

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <repository-url>
cd "Smart Manufacturing Predictive Maintanance"
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks inside the `notebooks/` directory and run the required cells.

## 🔄 Project Workflow

```text
AI4I 2020 Dataset
        ↓
Data Understanding
        ↓
Data Preprocessing
        ↓
Missing Value Handling
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Dimensionality Reduction
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Predictive Maintenance Analysis
```

## 📈 Expected Outcome

The project aims to develop machine learning models capable of identifying patterns associated with machine failures and providing useful predictions for predictive maintenance.

Such a system can help manufacturing environments:

* Reduce unexpected machine downtime
* Improve maintenance planning
* Identify potential failures earlier
* Improve machine utilization
* Support data-driven maintenance decisions

## 👥 Team

This project is developed as a collaborative academic project.

### Contributors

* Amritha 
* Sribalan
* Suvakkeen Manoj

> Update the contributor names and GitHub profiles according to your team members.

## 📚 References

* AI4I 2020 Predictive Maintenance Dataset
* Scikit-learn Documentation
* Pandas Documentation
* NumPy Documentation
* Matplotlib Documentation
* Jupyter Documentation

---

⭐ If you find this project useful, consider giving the repository a star!
