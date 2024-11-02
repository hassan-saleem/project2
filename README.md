Flight Delay Prediction Model
**Overview**
This repository contains the code to predict flight delays. Using features such as departure time, airline, and distance, this model aims to classify if a flight will be delayed by more than 15 minutes.

Requirements
To run this project, you'll need Python 3.8+ and the packages listed in requirements.txt. Install them by running:

bash
Copy code
pip install -r requirements.txt
Files and Directories
main.py: The main file for data processing, model training, and evaluation.
requirements.txt: Lists all the Python dependencies.
README.md: This file explains the purpose, requirements, and usage.
src/: Contains modules for data loading, cleaning, feature engineering, and model building.
Running the Code
To run the prediction pipeline:

Clone this repository:
bash
Copy code
git clone <YOUR_GITLAB_REPOSITORY_URL>
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Execute main.py:
bash
Copy code
python main.py
Expected Output
Running main.py will:

Preprocess the data (if provided).
Split the data into training and test sets.
Train a logistic regression model.
Evaluate the model and display:
Accuracy, Precision, Recall, Sensitivity, and Specificity
Confusion Matrix and ROC Curve plot
