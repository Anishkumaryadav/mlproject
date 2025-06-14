# End-to-End Machine Learning Project: Student Performance Prediction📝 #

## Introduction 🔬
This project is an end-to-end machine learning industry followed path project that predicts student math scores based on various factors like gender, ethnicity, parental education level, lunch type, and test preparation. The project includes data ingestion, preprocessing, model training, evaluation, and a Flask-based web application for predictions.

**Model Training:**
We trained multiple models (Ridge, Random Forest, XGBoost) and evaluated them using R² score.

**Best Model:**
Ridge Regression achieved the highest R² score (0.89), outperforming others.

**Reason:**
Its L2 regularization effectively handled feature correlations while preventing overfitting.

**Accuracy**
![alt text](<Screenshot 2025-06-15 005949.png>)

## Key Features 🛠️
- **Data Processing**: Handles both numerical and categorical features with robust preprocessing
- **Multiple Models**: Evaluates various regression models (Random Forest, XGBoost, CatBoost, etc.)
- **Hyperparameter Tuning**: Uses GridSearchCV for optimal model performance
- **Web Interface**: Flask-based web application for easy interaction
- **Modular Code**: Well-organized components following software engineering best practices


## Project Structure🎯 
<pre>
mlproject/
├── artifacts
├── notebooks
├── src
│   ├── components
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py 
│   │   └── model_trainer.py
│   ├── exception.py 
│   ├── logger.py 
│   ├── pipeline
│   └── utils.py 
├── static
├── templates
├── app.py 
├── application.py 
├── requirements.txt 
└── setup.py