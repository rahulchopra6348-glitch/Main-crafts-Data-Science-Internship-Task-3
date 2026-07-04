# 🚢 Data Science with Python Internship – Task 3

## 📌 Project Title

**Mini Exploratory Data Analysis (EDA) on Titanic Dataset**

---

## 📖 Project Overview

This project is a part of my **Data Science with Python Internship** at **Maincrafts Technology**.

The objective of this task is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset by cleaning the data, handling missing values, analyzing passenger survival patterns, and creating meaningful visualizations.

The project demonstrates essential data analysis techniques using **Python, Pandas, Matplotlib, and Seaborn**.

---

## 🎯 Objectives

The main objectives of this project are:

- Clean the Titanic dataset.
- Handle missing values using appropriate techniques.
- Remove unnecessary columns.
- Perform group-based analysis.
- Create informative visualizations.
- Extract meaningful insights from the data.

---

## 📂 Dataset

**Dataset Name:** Titanic Dataset

The dataset contains information about passengers aboard the Titanic, including:

- Passenger ID
- Passenger Class
- Name
- Gender
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket
- Fare
- Cabin
- Embarked Port
- Survival Status

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## 📋 Steps Performed

### 1️⃣ Data Loading

- Imported the Titanic dataset using Pandas.
- Displayed the first few rows.
- Checked dataset structure.

---

### 2️⃣ Data Exploration

Performed basic exploration using:

- Dataset Shape
- Column Names
- Dataset Information
- Missing Values

---

### 3️⃣ Data Cleaning

The following preprocessing steps were performed:

- Filled missing values in the **Age** column using the mean.
- Filled missing values in the **Embarked** column using the mode.
- Removed the **Cabin** column due to excessive missing values.

---

### 4️⃣ Feature Engineering

Created two new features:

### Age Group

Passengers were divided into five categories:

- Child
- Teen
- Young Adult
- Adult
- Senior

### Family Size

A new feature was created using:

Family Size = SibSp + Parch

---

## 📊 Analysis Performed

### ✅ Survival Rate by Age Group

Analyzed how survival varied across different age categories.

---

### ✅ Survival Rate by Embarkation Port

Compared passenger survival rates based on their boarding location.

Ports:

- C → Cherbourg
- Q → Queenstown
- S → Southampton

---

### ✅ Survival Rate by Family Size

Analyzed the relationship between family size and survival.

---

## 📈 Visualizations Created

The following visualizations were generated:

### 📌 Age Distribution Histogram

Shows the distribution of passenger ages.

---

### 📌 Survival Rate by Age Group

Bar chart showing survival rates across different age groups.

---

### 📌 Survival Rate by Embarkation Port

Bar chart comparing survival rates among embarkation ports.

---

### 📌 Survival Rate by Family Size

Bar chart showing the effect of family size on survival.

---

### 📌 Correlation Heatmap

Displays relationships among numerical variables in the dataset.

---

## 🔍 Key Insights

- Missing Age values were successfully handled using the mean.
- Cabin column was removed due to a large number of missing values.
- Young Adults and Adults had comparatively higher survival rates.
- Passengers embarking from Cherbourg showed the highest survival rate.
- Small family groups had better survival chances than passengers travelling alone or in very large families.
- Most passengers were between the ages of 20 and 40 years.
- Fare showed a positive relationship with survival.
- Passenger Class showed a negative relationship with survival.

---

## 📁 Project Structure

```
Task_3
│
├── Task_3_Titanic_EDA.ipynb
├── Titanic-Dataset.csv
└── README.md
```

---

## ▶️ How to Run the Project

1. Download the repository.
2. Open the project in Jupyter Notebook or VS Code.
3. Install the required libraries:

```bash
pip install pandas matplotlib seaborn
```

4. Open:

```
Task_3_Titanic_EDA.ipynb
```

5. Run all cells.

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data Cleaning
- Handling Missing Values
- Exploratory Data Analysis (EDA)
- GroupBy Operations
- Feature Engineering
- Data Visualization
- Correlation Analysis
- Data Storytelling using Python

---

## 📌 Conclusion

This project successfully demonstrates the process of performing Exploratory Data Analysis (EDA) on the Titanic dataset. By cleaning the data, creating new features, analyzing survival trends, and building visualizations, valuable insights were extracted that help understand passenger survival patterns.

This task strengthened my practical understanding of Python-based data analysis and visualization techniques, which are fundamental skills for every Data Scientist.

---

## 👨‍💻 Internship Details

**Internship:** Data Science with Python Internship

**Organization:** Maincrafts Technology

**Task:** Task 3 – Mini Exploratory Data Analysis (EDA)

---

⭐ Thank you for visiting this repository!
