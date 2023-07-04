
# Fake News Detection




## Acknowledgements

 The successful completion of this project would not have been possible without the support and contributions of many individuals and organizations. We would like to express our sincere gratitude to all those who helped us throughout this project.

First and foremost, we would like to thank our project supervisor Dr. Urvashi Prakash Shukla, for their unwavering guidance, support, and encouragement throughout the project. Their expertise and advice were critical in helping us navigate the challenges we encountered along the way.

We would like to give a special mention to the internet service provider, whose reliable internet connection enabled us to collaborate and work on this project efficiently. Without a stable internet connection, we would have faced numerous obstacles and delays, and the project's success would have been at risk.

Finally, we would like to thank our families and friends for their constant support, encouragement, and understanding throughout the project. Their unwavering support was essential in helping us stay motivated and focused on completing this project.

Thank you all for your contributions to this project, without which it would not have been possible to achieve our objectives.


## Overview
This project provides a machine learning model that can be used to detect fake news articles. The model is trained on a large dataset of news articles labeled as real or fake, and uses natural language processing techniques to analyze the content of each article and determine whether it is likely to be accurate or misleading.

Fake news has become a major problem in recent years, with the spread of misinformation and propaganda on social media and other online platforms. The goal of this project is to provide a tool that can help users identify fake news articles and avoid being misled by false information.

## Dependencies
The dependencies of a fake news detection model will depend on the specific implementation of the model are : 

Python (3.5 or later)

NumPy (1.18 or later)

Pandas (1.0 or later)

Scikit-learn (0.23 or later)

NLTK (3.5 or later)

Matplotlib (3.2 or later)

## Installation

Use the package manager pip to install library.

Follow these command to start your project.

pip install -r requirements.txt

python app.py

## Data Set
The kaggle link from where we have take our data set for fake news detection model.

https://www.kaggle.com/datasets/jruvika/fake-news-detection

It has around 4050 rows with 4 columns i.e. URLs, Headline, Body, Label

## User Interface
![image](https://user-images.githubusercontent.com/91000887/231347574-04316d78-7632-4e8c-8dfc-9824b95f1824.png)

## Prediction Page
![image](https://user-images.githubusercontent.com/91000887/231347904-a174e7fe-ca44-42fa-b0e9-e1bdde5984a8.png)

## Performance
Here we use the Logistic Regression.

Accuracy - 0.961

Precision - 0.976

Recall - 0.943

f1-score - 0.959

Limitation - 

-Only for the news which are written in English language.

-Only used for text news.

-It will not run for real time data.

-It will not give the accuracy of 100%.

## Examples

 0 indicate Real News

 1 indicate Fake News
 
![image](https://user-images.githubusercontent.com/91000887/231349792-32dd41c9-6e9d-4b3e-b386-7455b23e8962.png)


![image](https://user-images.githubusercontent.com/91000887/231349997-ad0ec8d3-82dd-4372-bd3e-d6e643f40d02.png)