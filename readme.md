Customer Churn Prediction Using Artificial Neural Network (ANN)
📌 Project Overview

This project focuses on predicting whether a customer will stay with the company or churn (leave) using an Artificial Neural Network (ANN).
The model is trained on a customer churn dataset and deployed as an interactive web application using Streamlit.

The system consists of three main components:

Model Training

Model Prediction

Web Application & Deployment

🧠 Model Description

An Artificial Neural Network (ANN) is built to learn patterns from historical customer data such as demographics, account information, and service usage.
After training, the model predicts the probability of a customer leaving the company.

⚙️ Project Workflow
1. Model Training

Data preprocessing (encoding, scaling, handling missing values)

Splitting dataset into training and testing sets

Building ANN using deep learning framework

Training and evaluating the model

Saving trained model and preprocessor

2. Model Prediction

Loading the saved ANN model

Loading the preprocessor

Accepting new customer inputs

Predicting churn probability

Classifying as Churn or Not Churn

3. Streamlit Web Application

User-friendly interface for entering customer details

Real-time churn prediction

Display of prediction results

Model deployed locally or on cloud using Streamlit

🛠️ Tech Stack

Programming Language: Python

Deep Learning: TensorFlow / Keras

Machine Learning: Scikit-learn

Data Processing: Pandas, NumPy

Model Serialization: Pickle

Web App Framework: Streamlit

Visualization: Matplotlib / Seaborn (optional)

🚀 How to Run

Install dependencies

pip install -r requirements.txt


Run the Streamlit app

streamlit run app.py


Open the browser and interact with the churn prediction system.

📂 Project Structure
├── model_training.py
├── model_prediction.py
├── app.py
├── churn_model.h5
├── preprocessor.pkl
├── dataset.csv
└── README.md

👩‍💻 Author
Anuradha Kumari
BTech | Python | SQL | AI & ML Enthusiast

⭐ Acknowledgement

Thanks to open-source datasets and libraries that made this project possible.


---

.

🚀 Connect With Me

📧 Email: krianuradha024@gmail.com
🔗 LinkedIn:https://www.linkedin.com/in/anuradha-kumari-b453a02b5/
🐙 GitHub: - https://github.com/anuradha-kri 
Thanks for checking out this project!

If this project helped you, feel free to ⭐ star the repo and share it with others learning 

This project is for educational purposes only.
