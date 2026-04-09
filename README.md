# 📊 Data Analysis Tasks Using Pandas (Google Colab)

## 📌 Project Overview

This project consists of two main tasks designed to build foundational skills in data handling and analysis using Python and Pandas. The first task focuses on creating a dataset manually, while the second task applies data analysis techniques on a real-world dataset (Titanic dataset).

---

# 🧩 Task 1: Create Your Own Dataset

## 🎯 Objective

To create a structured dataset using a Python dictionary and convert it into a Pandas DataFrame.

## 📂 Description

* A dataset was created with:

  * **5 columns (features)**
  * **15 rows (records)**
  * A **custom index** (e.g., ID_1 to ID_15)

## 🛠️ Key Concepts Used

* Python dictionary
* Pandas DataFrame creation
* Custom indexing

## ✅ Outcome

A clean and structured dataset was successfully created and displayed.

---

# 🚢 Task 2: Titanic Dataset Analysis

## 📌 Dataset

The Titanic dataset (`train.csv`) is used to analyze passenger survival patterns.

---

## 🔍 Step 1: Exploration

In this step, the dataset is explored to understand its structure and contents using:

* `.head()` → preview data
* `.info()` → check data types and missing values
* `.describe()` → view statistical summary

---

## 🧹 Step 2: Data Cleaning

The dataset is cleaned to prepare it for analysis:

* Missing values in **Age** are filled using the median
* Missing values in **Embarked** are filled using the mode
* The **Cabin** column is dropped due to many missing values
* Duplicate rows are checked and removed if present

---

## 📊 Step 3: Data Analysis

Data is analyzed using `groupby()` to identify patterns:

* Survival rate by gender
* Survival rate by passenger class
* Average age per class
* Survival rate by age groups

---

## 🔍 Step 4: Filtering

Specific groups of passengers are extracted:

* Female passengers who survived
* Children who survived
* First-class passengers with high survival probability

---

## 🧠 Step 5: Insights

### 1️⃣ Gender and Survival

Females were more likely to survive than males, indicating priority during evacuation.

### 2️⃣ Class and Survival

Passenger class had a strong impact:

* 1st class → highest survival
* 3rd class → lowest survival

### 3️⃣ Age and Survival

Children had higher survival rates than adults, showing partial prioritization.

### 4️⃣ Highest Survival Group

The group with the highest survival rate:
**Female passengers in 1st class, especially younger individuals**

---

## ✅ Final Conclusion

Survival on the Titanic was influenced by:

* Gender
* Passenger class
* Age

The safest group overall was:
**Females in 1st class, particularly younger passengers**

---

## 🛠️ Tools & Technologies

* Python 🐍
* Pandas 📊
* Google Colab
