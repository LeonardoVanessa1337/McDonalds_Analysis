# 🍔 McDonald's Nutrition Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on McDonald's menu nutrition data to uncover patterns, trends, and health insights.  
Using **Python, Pandas, and Matplotlib**, the analysis focuses on calories, sugar, fat, protein, cholesterol, and serving sizes across different food categories.

The goal is to help users better understand nutritional trade-offs when choosing menu items.

---

## 📂 Dataset
- **Source:** McDonald's menu nutrition dataset (`menu.csv`)
- **Key Features:**
  - Category
  - Item Name
  - Calories
  - Serving Size
  - Total Fat
  - Sugars
  - Protein
  - Cholesterol
  - Other nutritional values

---

## 🛠️ Tools & Libraries
- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 🔍 Analysis Steps

### 1. Initial Exploration
- Loaded dataset and inspected structure
- Used `describe()` to summarize numerical and categorical features
- Checked for missing values and unique entries

### 2. Data Preparation & Cleaning
- Extracted numeric serving size (grams) from text values
- Checked missing data and unique value counts
- Ensured data consistency for analysis

### 3. Exploratory Questions Answered
- How many items are there in each category?
- Which items contain the **highest sugar**?
- Which menu items are the **most calorie-dense**?
- How do nutrients vary across categories?

### 4. Data Visualization
- 📊 **Calorie Bomb Analysis**  
  - Identified items with more than **800 calories**
- 📊 **Category Distribution**  
  - Visualized the number of items per category
- 📊 **Cholesterol by Category**  
  - Compared average cholesterol levels across categories

---

## 📈 Key Observations
- **Chicken McNuggets (40 pieces)** are among the highest-calorie items
- **Coffee & Tea** has the largest number of menu items
- **Breakfast** items tend to have higher cholesterol
- **Beverages** generally contain very low cholesterol
- Sugary items are mostly concentrated in desserts and drinks

---

## ✅ Conclusion
- McDonald's menu items vary widely in nutritional value
- High-calorie and high-sugar items are easy to consume unintentionally
- Category-level analysis helps customers make healthier, goal-oriented choices
- The analysis can support decisions such as **weight loss**, **low-cholesterol diets**, or **high-protein meals**

---

## 🚀 How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/LeonardoVanessa1337/mcdonalds-nutrition-eda.git
