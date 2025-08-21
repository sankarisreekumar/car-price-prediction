🚗 Car Price Prediction

This project predicts the selling price of used cars based on their features using Machine Learning. The model is trained on a dataset containing various car attributes such as brand, year, fuel type, transmission, and mileage.

📌 Project Overview

Implemented data preprocessing and exploratory data analysis (EDA).

Applied feature engineering for categorical and numerical attributes.

Built and trained machine learning models for price prediction.

Evaluated model performance using metrics like R² score, MAE, and RMSE.

🛠️ Technologies Used

Python

Pandas, NumPy for data manipulation

Matplotlib, Seaborn for visualization

Scikit-learn for model building and evaluation

Jupyter Notebook for experimentation

📊 Dataset

Contains car details such as:

Car Name

Year of Manufacture

Selling Price

Present Price

Kilometers Driven

Fuel Type

Seller Type

Transmission

Owner Count

⚙️ Workflow

Data Collection & Cleaning

Exploratory Data Analysis (EDA)

Feature Encoding & Scaling

Model Training (Linear Regression, Decision Tree, Random Forest, etc.)

Model Evaluation

Prediction on new data

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook Car_Price_Prediction.ipynb

📈 Results
The best performing model achieved an R² score of  0.50.

Random Forest provided the most accurate predictions compared to other models.

🔮 Future Work

Deploy the model using Flask / Streamlit for web-based predictions.

Enhance dataset with more car attributes (e.g., insurance, service history).

Experiment with deep learning models for better accuracy.
