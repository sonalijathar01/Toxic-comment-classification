# Jigsaw Unintended Bias in Toxicity Classification

Detect toxicity across a diverse range of conversations

# Problem statement

Classify the given comments based on toxicity level. If target > .5 label as 1 (Toxic) else 0 (Intoxic)
Source : https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification

# Introduction
The Conversation AI team, a research initiative founded by Jigsaw and Google (both part of Alphabet), builds technology to protect voices in conversation. A main area of focus is machine learning models that can identify toxicity in online conversations, where toxicity is defined as anything rude, disrespectful or otherwise likely to make someone leave a discussion.

# 1. Business/Real World Problem
We need to classify the given comments based on toxicity level. If target > .5 mark the label as 1 (Toxic) else 0 ( In-toxic ).

# 2. Business constraints
A] Latency : 
Given a comment we need prediction of label (0 or 1) irrespective of the time taken by the model as long as it is not taking day to predict. So, no low latency is required.
B] Interpretability : 
Our goal is not only to predict what is a toxicity of comment, but also to know why the model has predicted it either of the cases.

# 3. Data Information
We have two data files: In the data supplied for problem, the text of the individual comment is found in the comment_text column. Each comment in Train has a toxicity label (target), and models should predict the target toxicity for the Test data.

# Flow of Project
We have done EDA on the dataset. As a part of feature engineering we have introduced topic modeling and these topics we are going to feed as input to our classification model. We have also done the sentiment analysis and at the end applied the logistic regression model to classify the comment.

# How to execute the project
In order to run the project just download the data from above mentioned source then run ipynb file in jupyter notebook.

# Prerequisites
 * Python 3
 * Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy,    scipy.

# Author
Sonali Jathar
