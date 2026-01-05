📌 Project Overview

This project is a Spam Message Classification system built using Machine Learning and Natural Language Processing (NLP).
The model classifies SMS messages as Ham (Normal) or Spam based on their text content.

The project was developed as part of my internship assignment, focusing on real-world text data handling, feature extraction and model evaluation.

🎯 Objective

To build a model that can accurately classify messages as spam or ham

To understand text preprocessing and feature extraction

To apply a supervised machine learning algorithm for classification

🧠 Technologies Used

Python

Pandas – data handling

Scikit-learn – machine learning models & evaluation

TF-IDF Vectorizer – feature extraction

Multinomial Naive Bayes – classification algorithm

Google Colab – development environment

📂 Dataset

SMS Spam Collection Dataset

Contains labeled SMS messages:

ham → normal messages

spam → promotional/fraud messages

⚙️ Project Workflow

Data loading and inspection

Data cleaning and preprocessing

Label encoding (ham → 0, spam → 1)

Feature extraction using TF-IDF Vectorizer

Train-test split

Model training using Multinomial Naive Bayes

Model evaluation (accuracy, precision, recall, F1-score)

Testing on custom messages

🧪 Model Performance

Accuracy: ~96%

High precision for spam detection

Strong recall for normal (ham) messages

This ensures fewer false spam alerts while maintaining good detection capability.

🧾 Classification Report Summary

Ham (0):

High recall (model rarely misses normal messages)

Spam (1):

Very high precision (when marked spam, it is almost always correct)
📈 Results

The model successfully classifies unseen messages and demonstrates strong performance on real-world SMS data.

📌 Key Learnings

Handling real-world text data and encoding issues

Importance of correct preprocessing order in NLP

Feature extraction using TF-IDF

Building and evaluating classification models

Debugging common ML pipeline errors

🚀 Future Improvements

Improve spam recall using hyperparameter tuning

Try advanced models like Logistic Regression or SVM

Deploy as a web app using Streamlit or Flask

👩‍🎓 Author

Deepanshi Jindal

B.Tech (AI & Data Science)
