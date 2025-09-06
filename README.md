# Liver-disease-classification
Overview
This project's main goal is to classify whether a person has liver disease based on a set of medical parameters. To do this, it walks through the entire process of building and deploying a machine learning model, starting from the very beginning with the data and ending with a simple web application for real-time predictions. The project uses the "Indian Liver Patient Dataset" to train and test the model.

Exploratory Data Analysis (EDA): The notebook begins by exploring the dataset, which contains 583 rows and 11 columns, with features such as age, gender, and various medical measurements like total bilirubin and alkaline phosphatase. It includes visualizations to understand the distribution of these features, the relationships between them, and the balance of the dataset (i.e., how many people have liver disease versus how many don't).

Data Preparation: Before training the model, the project handles any missing values in the data and prepares it for the machine learning algorithm.

Model Training and Evaluation: A classification model is trained on the prepared data. The notebook evaluates the model's performance to ensure it can accurately predict whether a patient has liver disease.

Deployment: Creating a simple, user-friendly web application using Streamlit. This app will allow a user to input medical details and get an instant prediction from the trained model, so it's in progress

Key Takeaways
This project successfully demonstrates how to take a raw dataset and use it to build a functioning machine learning-powered application. It highlights the importance of data cleaning, analysis, and model evaluation before the final step of putting the model into a practical application. The web app serves as a clear, tangible way to see the model in action and a simple way for others to use it.

Technologies Used
Python: The core programming language.

Pandas: For data manipulation and analysis.

Numpy: For numerical operations.

Matplotlib & Seaborn: For data visualization.

Scikit-learn: For machine learning model training and evaluation.

Streamlit: For creating the web application.

The trained model is saved using joblib or pickle for easy use in the web application.
