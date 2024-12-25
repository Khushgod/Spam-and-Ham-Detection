So I have used the Spam and Ham Detection using Python libraries and Machine Learning Logistic Regression Model Logic : 
In another Project of video claasification is also a Project made by the logic of Machine Learning Model and Python In built library of YOLOV8

The model details and structure of the following project is mentioned below :

Model Details :

The spam detection system uses the following components:

Text Preprocessing:

Lowercase conversion
Punctuation removal
Stop words removal
Tokenization


Feature Engineering:

Text vectorization using TF-IDF
Feature scaling


Classification:

Logistic Regression with optimized parameters
Binary output (SPAM/HAM)



Structure : 

spam-detection/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│   └── trained_model.pkl
│
├── src/
│   ├── __init__.py
│   ├── preprocessing.py
│   ├── training.py
│   └── prediction.py
│
├── notebooks/
│   └── model_development.ipynb
│
├── tests/
│   └── test_spam_detector.py
│
├── requirements.txt
└── README.md
