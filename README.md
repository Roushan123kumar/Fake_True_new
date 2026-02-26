📰 Fake News Detection System

A Machine Learning based web application that classifies news articles as Fake or Real using Natural Language Processing (NLP) techniques.

📌 Project Description

This project aims to detect fake news automatically by training a machine learning model on a dataset of real and fake news articles.

The system:

Preprocesses text data

Converts text into numerical features

Trains a classification model

Predicts whether given news content is Fake or Real

📁 Project Structure
Fake_True_new/
│
├── Fake.csv              # Fake news dataset
├── True.csv              # Real news dataset
├── prepare.py            # Data preprocessing & model training
├── predict.py            # Prediction logic
├── newapp.py             # Main web application
├── index.html            # Frontend UI
├── requirements.txt      # Required Python libraries
├── config.yml            # Configuration file
├── setup.sh              # Setup script
├── Procfile              # Deployment file
└── .ebignore             # Ignore file for deployment
🛠️ Technologies Used

Python

Machine Learning

Natural Language Processing (NLP)

HTML

Git & GitHub

⚙️ Installation Steps

1️⃣ Clone the repository:

git clone https://github.com/Roushan123kumar/Fake_True_new.git

2️⃣ Navigate to the project folder:

cd Fake_True_new

3️⃣ Install required libraries:

pip install -r requirements.txt
▶️ How to Run the Project
Step 1: Train the Model
python prepare.py
Step 2: Run the Web Application
python newapp.py

Open the browser and access the local server to test predictions.

📊 Dataset Information

Fake.csv – Contains fake news articles

True.csv – Contains real news articles

Large dataset files are handled using Git LFS.

🎯 Features

✔ Text preprocessing
✔ Machine learning classification
✔ Web-based user interface
✔ Fake/Real prediction system

📌 Author

Roushan Kumar
