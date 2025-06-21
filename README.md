# 🧠 Programming of AI – Practice Assignment

📘 **Subject:** Programming of AI  
👨‍🎓 **Name:** Santosh  
🎓 **Roll Number:** 22/F-BSAI-63  
🏛️ **University:** Dawood University of Engineering and Technology (DUET), Karachi  
🏫 **Department:** Artificial Intelligence  
📅 **Assignment Type:** Practice Submission  

## 📄 Overview

This repository contains a **practice assignment** for the *Programming of AI* course. It covers data analysis, visualization, hypothesis testing, and ODE-based modeling using Python and popular data science libraries.


## 📦 Libraries Used

python
pandas  
numpy  
seaborn  
matplotlib  
scikit-learn  
scipy

To install them, use:

```bash
pip install -r requirements.txt
```


## 🚀 How to Run

1. Clone this repository or download ZIP
2. Install libraries: `pip install -r requirements.txt`
3. Open and run:

   * `Health_Analytics_Assignment.ipynb` (Jupyter Notebook)
   * or `Health_Analytics_Assignment.py` (Python script)
4. Run all cells/blocks to view outputs and plots



## 📊 Visual Outputs

### 1️⃣ Blood Pressure by Risk Category

> Shows how blood pressure varies across different risk categories using a boxplot.

![Blood Pressure by Risk](Output%20Plots/Blood_Pressure_by_RishCategory.PNG)


### 2️⃣ Patient Count by Region and Risk Category

> Countplot showing how patients are distributed by region and categorized by risk.

![Patient Count](Output%20Plots/patients_in_each%20RiskCategory_per_Region.PNG)




### 3️⃣ ODE Solution – Medication Level Over Time

> Compares results from `odeint` and `solve_ivp` in modeling a medication’s concentration over time.

![ODE Solution](Output%20Plots/ODE_solution_for_medication_level_over_time.PNG)



## 📘 Topics Covered

### ✅ Outlier Detection & Feature Reduction

* Used `VarianceThreshold()` to remove constant features
* Filled missing values using mean
* Removed outliers using Z-score method

### ✅ Data Visualization

* Boxplot and countplot created using **Seaborn** and **Matplotlib**

### ✅ Hypothesis Testing

* One-sample **t-test** for cholesterol vs 200 mg/dL
* **Chi-square test** for Region vs RiskCategory

### ✅ Health System Modeling

* Used ODEs to simulate medication level over time
* Implemented with both `odeint` and `solve_ivp`



## 📂 Folder Structure

```
📁 AI-Programming-Assignment/
│
├── assignment_code.ipynb                  # Jupyter notebook version
├── assignment_code.py                     # Python script version
├── requirements.txt                       # Required libraries
├── README.md                              # This file
├── Output Plots/
│   ├── Blood_Pressure_by_RishCategory.png
│   ├── ODE solution for medication level over time.png
│   └── patients in each RiskCategory per Region.png
```



## ✍️ Submitted By

**Santosh**
🎓 Roll No: 22/F-BSAI-63
📘 Department of Artificial Intelligence
🏫 Dawood University of Engineering & Technology (DUET), Karachi



📌 *Note: This assignment was prepared for learning and practice purposes only.*
