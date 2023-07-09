# PHISHING URL DETECTION ::

ABSTRACT : Phishing is a cybersecurity attack that is used to trick victim users to provide sensitive information or deploy malicious software on their infrastructure. Depending on the target system and users, these attacks can inflict severe negative impacts on the system. Therefore, researchers have been working on developing phishing detection and prevention techniques to thwart these attacks. In this model, we present an efficient phishing websites detection system that analyzes the phishing websites URL addresses to learn data patterns that can identify authentic and phishing websites. Our system employs machine learning techniques such as Logistic Regression  to learn data patterns in websites URLs. We evaluate our system on a recent phishing websites dataset using classification accuracy as a performance indicator. Our best result shows that Logistics regression models provide 93.40% classification accuracy on the almost balanced-class dataset.
          

# Create an working environment for the Project:
Type conda create -p phishing python==3.8 -y  (on Cmd prompt)

To Activate the working Environment Type conda activate phishing/  (on cmd prompt)

# To install Required Dependency:
Type pip install -r requirnments.txt in (cmd prompt)

# Steps which are Implemented in this Model:
1.Data collection (https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls)

2.Data Description

3.Data Preprocessing:
                a) check duplicates in the data
                b) cleaning /?@ symbol form the URL

4.Data Transformation:
                a) Converting Text into Numerical using Countvectorizer

5.Resampling Method:
                a) converting Imbalanced data into Balanced data using SMOTE

6.Model Training:
                a) Logistic Regression
                b) Random Forest Classifier

7.Evaluation Metrics:
                a)ConfusionMatrix,precision score,recall score,accuracy score

8.Formatting to Pickle.

9.Prediction. 