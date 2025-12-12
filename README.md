📘 Python Libraries & Linear Regression – Quick Guide
🧰 Python Libraries

Libraries in Python are pre-written collections of functions, classes, and modules that help us perform tasks easily without writing code from scratch.

Common Libraries

Pandas – Data analysis and working with tables (rows & columns).

Matplotlib – Creating graphs and charts.

Math – Provides mathematical functions like sqrt(), sin(), cos(), etc.

Statsmodels – Used for linear regression, logistic regression, and other statistical analyses.

📈 Simple Linear Regression

Simple Linear Regression shows the relationship between:

One independent variable (X)

One dependent variable (Y)
by fitting a straight line to the data.

🔹 Estimating Model Coefficients

Finding the best slope and intercept so the regression line fits the data accurately.

🔹 Interpreting Model Coefficients

Intercept – Value of Y when X = 0

Slope – How much Y changes for a one-unit increase in X

🔹 Plotting the Least Squares Line

Drawing the best-fit line that minimizes the total distance between data points and the line.

🔹 Confidence in Our Model

Shows how reliable the regression predictions are and whether the relationship is due to chance.

🧪 Hypothesis Testing & p-values

Hypothesis testing checks if the relationship between variables is real.

Null Hypothesis (H₀): No relationship (slope = 0)

Alternative Hypothesis (H₁): There is a relationship (slope ≠ 0)

p-value: Tells how likely it is that our results happened by random chance.

Example:

H₀: TV ads do not affect Sales

H₁: TV ads do affect Sales

📊 Multiple Linear Regression

A statistical method that models the relationship between:

One dependent variable (Y)

Two or more independent variables (X₁, X₂, X₃, …)

🧠 Feature Selection

Choosing the most important predictors for the model.

✔️ Which Features to Include

Keep features with small p-values

Include features that increase R-squared

⚠️ Drawbacks

Linear models rely on strong assumptions

p-values may select irrelevant features

R-squared always increases (may cause overfitting)

Adjusted R-squared still under-penalizes complexity

✅ Better Method – Cross-Validation

Checks how well the model performs on unseen data, making it more reliable.

🤖 Linear Regression in scikit-learn

A machine learning approach to fit regression models easily using simple code.

Why We Use It

Predict continuous values (marks, prices, sales, etc.)

Understand how each feature affects the output

Faster and simpler implementation

🔤 Handling Categorical Predictors
1️⃣ Two Categories

Convert into binary (0 or 1) values.

Use:

Allows linear regression to use categorical data

Measures the effect of each category

2️⃣ More Than Two Categories

Convert into multiple binary variables — dummy variables.

Use:

Handles multi-category predictors

Measures the effect of each category separately
