📌 Medical Cost Prediction Using ElasticNetCV

This project aims to predict individual medical insurance charges using regression techniques, with a primary focus on ElasticNetCV, which combines both L1 (Lasso) and L2 (Ridge) regularization.
The model is trained on the Medical Cost Personal Dataset, a widely used dataset for health economics and insurance analytics.

🚀 Project Overview

The goal of this project is to build a regression model that can estimate a person's medical insurance cost based on features such as:

Age

BMI (Body Mass Index)

Number of Children

Sex

Smoking Status

Residential Region

To improve generalization and reduce overfitting, the project uses:

✔ ElasticNetCV for hyperparameter optimization
✔ StandardScaler for feature scaling
✔ 5-fold Cross Validation
✔ Train–test split structure
✔ Performance metrics (R², RMSE, MSE)

📂 Dataset

The dataset used is Medical Cost Personal Dataset, which includes the following columns:

Feature	Description
age	Age of the individual
sex	male / female
bmi	Body Mass Index
children	Number of children/dependents
smoker	yes / no
region	Geographical region
charges	Target variable — medical insurance cost

Target variable: charges

🛠️ Technologies & Libraries

Python 3.x

Pandas

NumPy

Scikit-learn

ElasticNetCV

Matplotlib / Seaborn (optional visualization)

🔧 Modeling Steps

1️⃣ Load and inspect dataset
2️⃣ Apply one-hot encoding to categorical variables
3️⃣ Scale numerical features using StandardScaler
4️⃣ Split data into training and test sets
5️⃣ Fit ElasticNetCV model
6️⃣ Evaluate using R², MSE, RMSE
7️⃣ Analyze model coefficients

📊 Final Model Performance

After hyperparameter tuning with ElasticNetCV, the final model achieved:

R² Score: ~0.76

RMSE: ~5950

These results indicate a strong predictive performance for this dataset.


