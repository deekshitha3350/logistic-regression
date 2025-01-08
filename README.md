# logistic-regression

This project leverages logistic regression to predict passenger survival on the Titanic based on features such as age, gender, and passenger class. It includes data preprocessing, model evaluation, and an interactive Streamlit-based deployment for predictions.

📁 Repository Structure
bash
Copy code
Titanic-Survival-Prediction/
|— README.md                # Project documentation
|— Titanic_train.csv        # Training dataset
|— Titanic_test.csv         # Test dataset for prediction
|— titanic_model.pkl        # Trained logistic regression model
|— titanic_streamlit_app.py # Streamlit application script
|— submission.csv           # Survival predictions for test dataset
🚀 Features
End-to-End Pipeline:
Data Cleaning & Preprocessing
Feature Engineering
Logistic Regression Model Building
Model Evaluation with Metrics & Visualizations
Interactive Deployment:
A user-friendly Streamlit app for making predictions.
Reusable Components:
Modular scripts for training, evaluation, and deployment.
🧪 Steps to Reproduce
Prerequisites
Ensure the following libraries are installed:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib seaborn streamlit
Run Locally
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/Titanic-Survival-Prediction.git
Navigate to the Directory:
bash
Copy code
cd Titanic-Survival-Prediction
Run the Streamlit App:
bash
Copy code
streamlit run titanic_streamlit_app.py
Online Deployment
Upload the repository to your GitHub account.
Deploy the app on Streamlit Community Cloud by linking your GitHub repository.
📊 Key Insights
Model Evaluation
Metrics:
Accuracy: ~80%
Precision, Recall, F1-Score
ROC-AUC Score: ~0.85
Visualizations:
Survival distribution
ROC Curve for classification performance
Feature Importance
Top Predictors:
Sex: Significant correlation with survival (female passengers had higher survival rates).
Pclass: Higher classes had better survival chances.
Age: Younger passengers were more likely to survive.
🖥️ Interactive App Features
The Streamlit app allows:

Input of Passenger Details:
Age
Sex
Passenger Class
Prediction: Displays survival probability and classification (Survived/Not Survived).
🛠️ Technical Details
Libraries Used
Data Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Modeling: Scikit-learn
Deployment: Streamlit
Model
Algorithm: Logistic Regression
Hyperparameters: Increased maximum iterations (max_iter=1000) for convergence.
🎉 Results
The logistic regression model performs well in predicting survival with a robust ROC-AUC score, making it a practical solution for binary classification problems.

🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature-name
Commit changes and push to your fork:
bash
Copy code
git push origin feature-name
Submit a pull request for review.
📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

🌟 Acknowledgements
Titanic dataset provided by Kaggle.
Inspired by classic machine learning problems.
Special thanks to Scikit-learn, Pandas, Seaborn, and Streamlit for their robust libraries.
