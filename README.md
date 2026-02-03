# Sales-Prediction-using-Random-Forest-Regressor
📌 About the Project

This project aims to predict chocolate sales amounts using a Random Forest Regressor. The model is trained on a chocolate sales dataset containing transactional sales records, including details such as sales person, country, product type, boxes shipped, and transaction date. The objective is to analyze historical sales data and build a machine learning model capable of estimating future sales amounts.

The project follows an end-to-end machine learning workflow, including data cleaning, feature engineering, categorical encoding, model training, evaluation, and visualization.

📂 Dataset Description
The sample dataset is taken from https://www.kaggle.com/datasets/saidaminsaidaxmadov/chocolate-sales
The dataset used in this project consists of chocolate sales transactions with the following attributes:

Sales Person – Name of the salesperson involved in the transaction

Country – Country where the sale occurred

Product – Type of chocolate product sold

Boxes Shipped – Number of boxes shipped in the transaction

Date – Date of the sale

Amount – Total sales amount (target variable)

The dataset does not contain missing values and required preprocessing such as currency conversion and date feature extraction before model training.

🔧 Project Highlights

Cleaned and transformed raw sales data (currency conversion, date processing)

Extracted meaningful features from the date column (day, month, year)

Applied One-Hot Encoding to categorical variables

Built a Random Forest Regressor to predict sales amount

Evaluated model performance using MAE, RMSE, and R² score

Visualized predictions and residuals to assess model accuracy

🤖 Model Used

Random Forest Regressor
Chosen for its ability to model non-linear relationships and handle complex feature interactions

📈 Results

The Random Forest Regressor achieved a positive R² score, indicating a better fit compared to linear regression and demonstrating its effectiveness in predicting chocolate sales.

🛠️ Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

🎯 Conclusion

This project highlights the importance of proper data preprocessing and model selection in sales prediction tasks. Ensemble learning methods such as Random Forest Regressor proved to be more effective for this dataset than traditional linear models.
