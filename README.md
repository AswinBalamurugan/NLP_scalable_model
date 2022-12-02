Please refer: [My Project Collection](https://github.com/AswinBalamurugan/Machine_Learning_Projects/blob/main/README.md)

# Objective
To get a deeper understanding of the NLP techniques leveraging a scalable model (XGBoost model) for classification.

# Dataset
The dataset is available on kaggle - "Deep-NLP".
Link to the website - https://www.kaggle.com/datasets/samdeeplearning/deepnlp

## Description of the dataset
The dataset contains 80 user responses to a therapy chatbot. 
Bot said: 'Describe a time when you have acted as a resource for someone else'.  
User responded. 
If a response is 'not flagged', the user can continue talking to the bot. 
If it is 'flagged', the user is referred to help.

The 2 columns used for classification are:
* Class
* Response_text

# Approach
To process the given responses and build an XGBoost Classifier model to classify the a given response as flagged or not flagged.

# About XGBoost
XGBoost, which stands for Extreme Gradient Boosting, is a scalable, distributed gradient-boosted decision tree (GBDT) machine learning library. A Gradient Boosting Decision Trees (GBDT) is a decision tree ensemble learning algorithm similar to random forest, for classification and regression. Ensemble learning algorithms combine multiple machine learning algorithms to obtain a better model.

# Accuracy scores of the XGBoost Model
* Train Accuracy : 0.89 
* Test Accuracy : 0.75

# Conclusion
NLP techniques like tokenizer, bag of words, lemmatization are used to process the sentences and prepare them for modelling. The trained XGBoost Classifier model will be able to classify a new response as flagged or not flagged with considerable accuracy. 
