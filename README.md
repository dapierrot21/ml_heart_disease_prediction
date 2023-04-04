# Heart Disease Prediction Project
This repository contains the code for my ongoing machine learning project to predict heart disease using a dataset of patient information. As a newcomer to the field of machine learning, I undertook this project to gain hands-on experience and learn about the end-to-end machine learning project workflow.

# Data
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The data has been preprocessed and is available in the "heart.csv" file.

# Approach
My approach to this project involves several key stages:

# Data cleaning and preprocessing: 
I am currently cleaning the dataset by handling missing values, removing duplicates, and standardizing the data. I am also performing feature engineering by creating new features and transforming existing ones.

# Model selection: 
I am exploring several classification algorithms, including logistic regression, k-nearest neighbors, decision trees, and random forests. I am using cross-validation and hyperparameter tuning to optimize the models.

# Evaluation: 
I plan to evaluate the models based on their accuracy, precision, recall, and F1 score. I will also create ROC curves and calculate the area under the curve (AUC) to assess the models' performance.

# Results (To be updated):
I will update this section with the results of my best-performing model once I have completed the evaluation stage.

# Future work:
In the future, I plan to explore additional feature engineering techniques and model architectures to improve the performance of my heart disease prediction model. I also plan to deploy the model to a web application or mobile app to make it more accessible to healthcare providers and patients.

# Conclusion
This project is an exciting opportunity for me to gain valuable experience in the end-to-end machine learning project workflow, from data cleaning and preprocessing to model selection and evaluation. I look forward to updating this repository with my progress and sharing my findings with the community.


# How to view the notebook locally
1. Install Python on your computer (if not already installed).
2. Install pip (if not already installed) using the command: python -m ensurepip --default-pip
3. Install virtual environment using the command: pip install virtualenv
4. Clone the repository using the command: git clone <repository_url>
5. Navigate to the cloned repository on your local machine using the terminal or command prompt.
6. Create a virtual environment using the command: virtualenv venv (this will create a new directory called venv).
7. Activate the virtual environment using the command: source venv/bin/activate (for Linux/MacOS) or venv\Scripts\activate (for Windows).
8. Install the required packages from the requirements.txt file using the command: pip install -r requirements.txt
9. Launch Jupyter Notebook using the command: jupyter notebook
10. Your browser should automatically open a new tab at the Jupyter Notebook dashboard. If not, open your browser and go to http://localhost:8888/tree.
11. Navigate to the folder where the notebook file is located and open it.
