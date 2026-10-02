# Sales Prediction 📈

This project is part of my **CodeAlpha Data Science Internship**.

In this project, I built machine learning models to predict sales based on advertising expenditure across different media channels.

## What I Did

- Loaded the sales and advertising dataset using Pandas
- Checked the dataset structure and data types
- Checked for missing values
- Checked for duplicate records
- Performed statistical analysis
- Explored relationships between advertising channels and sales
- Calculated correlation between variables
- Prepared features and target variables
- Split the data into training and testing sets
- Trained Linear Regression and Random Forest models
- Evaluated both models using MAE, MSE, RMSE and R²
- Created actual vs predicted sales visualization
- Compared model performance
- Tested the model with a sample prediction

## Dataset

The dataset contains advertising expenditure and sales information.

Main columns:

- TV
- Radio
- Newspaper
- Sales

The target variable is:

```text
Sales

Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Data Preprocessing
The dataset was loaded using Pandas and checked for missing values and duplicate records.
The dataset contained 0 duplicate records.
The numerical variables were explored using descriptive statistics and correlation analysis.

Exploratory Data Analysis
The project includes visualizations showing:
1. TV advertising vs Sales
2. Radio advertising vs Sales
3. Newspaper advertising vs Sales
4. Actual vs Predicted Sales
5. Model Performance Comparison

Machine Learning Models

Two regression models were trained:
Linear Regression
The Linear Regression model was evaluated using:
- MAE
- MSE
- RMSE
- R² Score

Random Forest
The Random Forest model was also evaluated using:
- MAE
- MSE
- RMSE
- R² Score

The model results are generated directly in the notebook.


Dataset Split

The dataset was divided into:
- 80% Training Data
- 20% Testing Data

The split used:
random_state = 42


Example Prediction

The notebook also tests the Linear Regression model on one sample from the test dataset and compares:
Actual Sales
Predicted Sales
Difference

Project Structure
CodeAlpha_SalesPrediction/
│
├── Sales_Prediction.ipynb
├── Advertising.csv
├── README.md
├── requirements.txt
└── .gitignore

How to Run
Clone the repository:
git clone YOUR_GITHUB_REPOSITORY_URL

Move into the project folder:
cd CodeAlpha_SalesPrediction

Create a virtual environment:
python3 -m venv .venv

Activate it:
source .venv/bin/activate

Install the required libraries:
pip install -r requirements.txt

Open:
Sales_Prediction.ipynb

Run the notebook cells from top to bottom.


What I Learned
Through this project, I gained practical experience in exploratory data analysis, correlation analysis, regression modeling, model evaluation, and data visualization using Python.

The project also helped me understand how advertising expenditure can be used as input features for predicting sales.


Internship
CodeAlpha Data Science Internship

Author
Sourav Kumar