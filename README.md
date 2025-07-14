
---

# 📈 Sales Prediction Using Python – OIBSIP Data Science Internship Task 5

### 🔍 Objective

Sales prediction involves estimating the quantity of a product that customers will purchase based on various factors like advertising spend, target audience segment, and advertising platform. Businesses rely on accurate sales forecasts to optimize marketing budgets and inventory management.

This project uses machine learning to predict sales based on advertising expenditures across different media channels.

This was submitted as part of my **Oasis Infobyte Internship (OIBSIP).**

---

### ✅ Steps Performed

1. **Data Acquisition**

   * Downloaded the Advertising dataset using `kagglehub`
   * Loaded and inspected the dataset

2. **Data Cleaning**

   * Removed unnecessary columns (`Unnamed: 0`)

3. **Feature Selection**

   * Selected advertising spends on TV, Radio, and Newspaper as input features
   * Sales as the target variable

4. **Model Training**

   * Split the dataset into training and testing sets (80/20 split)
   * Trained a Linear Regression model on the training data

5. **Evaluation**

   * Predicted sales on the test set
   * Calculated Root Mean Squared Error (RMSE) and R² score to evaluate model performance

6. **Visualization**

   * Plotted Actual vs Predicted sales to visualize prediction accuracy

---

### 🛠️ Tools & Libraries Used

* Python
* pandas
* numpy
* seaborn, matplotlib
* scikit-learn (LinearRegression, train\_test\_split, metrics)
* kagglehub for dataset download automation

---

### 📊 Model Performance (Sample)

| Metric   | Value        |
| -------- | ------------ |
| RMSE     | *e.g., 1.23* |
| R² Score | *e.g., 0.89* |

---

### 📌 Outcome

This project highlights how linear regression can effectively model the relationship between advertising spend and sales revenue. The insights gained can aid businesses in allocating advertising budgets more efficiently to maximize sales.

---
