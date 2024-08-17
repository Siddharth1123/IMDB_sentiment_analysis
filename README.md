Steps to Build and Deploy the Sentiment Analysis Model

1. Environment Setup
Create a Project Directory:
    mkdir IMDB_sentiment_analysis
    cd IMDB_sentiment_analysis

Set Up a Virtual Environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install Required Packages:

pip install numpy pandas scikit-learn tensorflow keras flask

2. Data Preparation
    Download and Load the IMDB Dataset:kaggle
    Extract the dataset and place it in a directory, e.g., data/.

     
4. Data Preprocessing :
   label encoding / hotencoder
   split into train and test
   tokenization (text into values)
   
5 Model Building and Training
    LSTM Model
    Logistic Regression Model (train_logistic_regression.py):

5. Model Deployment with Flask

6. Run Flask Application:
   python deploy.py

   







