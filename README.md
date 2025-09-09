California Housing Price Prediction

This project builds a Linear Regression model to predict house prices in California using the California Housing dataset
.

📂 Repository Contents

notebook.ipynb → Jupyter Notebook with data analysis, preprocessing, feature engineering, model training, and evaluation.

housing.csv → Dataset used for training and testing the model.

⚙️ Project Workflow

Data Loading & Exploration

Basic statistics, missing values, distributions.

Feature Engineering

Creating new features (e.g., rooms_per_house, bedrooms_ratio, people_per_house).

Preprocessing

Handling outliers & skewness (custom transformer).

Scaling numeric features.

One-Hot Encoding categorical features.

Modeling

Training a Linear Regression model.

Evaluation

Metrics: MSE, RMSE, MAE, R².

📊 Results

The model shows reasonable performance in predicting median house values.

Feature engineering improved accuracy compared to using raw features.

🚀 Future Improvements

Try more advanced models (Random Forest, Gradient Boosting, Neural Networks).

Hyperparameter tuning.

Deploy as an API with FastAPI or a web app using Streamlit/Gradio.
