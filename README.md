# Spam-Email-Detection-using-MultinomialNavibase


Overview
This project implements a spam email classifier using the Multinomial Naive Bayes algorithm. The classifier analyzes email subjects to differentiate between spam and ham (non-spam) messages. By leveraging the CountVectorizer for text processing and Multinomial Naive Bayes for classification, this project offers an efficient solution for email filtering.

Deployed App
I have deployed the Spam Email Detector App, and it is accessible via the following link: Spam Email Detector.



How it Works
Text Processing:

Email subjects are processed using the CountVectorizer, which converts text into a matrix of token counts. This step involves creating a vocabulary of words present in the dataset.
Training the Model:

The dataset, comprising labeled spam and ham email subjects, is split into training and testing sets. The Multinomial Naive Bayes classifier is trained on the training data to learn the patterns and characteristics of spam emails.
Classification:

When a new email subject is provided, the trained classifier uses the CountVectorizer to convert it into token counts and predicts whether it's spam or ham based on the learned patterns.
Dataset Used
The classifier is trained and tested on a Spam Mails Dataset containing labelled email subjects, with indications of whether they are spam or ham.

Dataset Description:

Details of the dataset

Model Accuracy
The classifier's accuracy is a crucial metric to evaluate its performance. After training, the model's accuracy is determined using the testing dataset. This accuracy score was 95%.

Libraries and Tools Used
Python Libraries: pandas, numpy, CountVectorizer, MultinomialNB from sklearn
Data Processing: CountVectorizer is employed to convert text documents into token counts, creating the feature matrix.
Model Training: Multinomial Naive Bayes classifier is used for training the model.
Getting Started
Clone the Repository:


cd Spam-Email-Detection-using-MultinomialNB
Install Dependencies:

pip install pandas numpy scikit-learn streamlit
Run the Streamlit App:

streamlit run app.py


Fork the repository on GitHub.
Create a new branch with a descriptive name.
Make your changes and commit them with clear comments.
Push your changes to your fork.
Open a pull request, explaining the changes made.
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
