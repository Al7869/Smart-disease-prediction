# Smart-disease-prediction
Tech Stack: Python, scikit-learn, Pandas, NumPy, Streamlit, Render, Kaggle Dataset

The Smart Disease Prediction System is a machine learning-based web application designed to predict potential diseases based on user-reported symptoms. The aim of the project is to provide early health insights and assist in decision-making regarding medical attention, especially in underserved or remote areas.

The system leverages a curated dataset sourced from Kaggle, which includes a wide range of symptoms and corresponding disease labels. Multiple machine learning models were trained and evaluated, including Random Forest, Support Vector Machine (SVM), and Logistic Regression. After extensive tuning and validation, the models achieved a prediction accuracy ranging from 88% to 95% depending on the complexity of the disease and the input symptoms.

A clean and interactive Streamlit-based interface was developed to allow users to select symptoms from a list and get instant predictions. The model provides the top likely diseases along with a recommendation to consult a medical professional. The entire system was deployed on Render, making it publicly accessible.

Key Highlights:
Preprocessed and encoded symptom data for over 40+ disease classes.

Implemented model selection, confusion matrix evaluation, and cross-validation for reliability.

Achieved high performance with Random Forest as the best-performing model.

Designed an intuitive UI with a focus on user experience and real-time feedback.

Deployed the application online using Render, ensuring easy accessibility.

This project demonstrates practical application of machine learning in healthcare and showcases a full development cycle—from data preparation and model training to deployment and user interaction.
