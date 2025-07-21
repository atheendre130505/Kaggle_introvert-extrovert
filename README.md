Kaggle Introvert-Extrovert Classification
This repository contains my solutions for the Kaggle Playground Series - Season 5, Episode 7: Predict the Introverts from the Extroverts competition.

🎯 Competition Overview
The goal of this competition is to predict whether a person is an Introvert or Extrovert based on their social behavior and personality traits. This is a binary classification problem that uses synthetic data generated from real-world behavioral patterns.

Competition Details
Competition Type: Tabular Playground Series

Evaluation Metric: Accuracy Score

Dataset: Synthetically generated from real-world personality data

Duration: Few weeks (typical for Playground Series)

📊 Dataset Information
The dataset contains behavioral and psychological features that correlate with personality types:

Features
Time_spent_Alone: Average time an individual spends alone (in hours)

Stage_fear: Whether the individual experiences stage fright (Yes/No)

Social_event_attendance: Number of social events attended recently

Going_outside: Frequency of going outside for non-essential reasons

Drained_after_socializing: Whether the person feels exhausted after social interaction (Yes/No)

Friends_circle_size: Count of close friends in the individual's social circle

Post_frequency: Frequency of social media posting

Personality: Target variable (Introvert/Extrovert)

Submission Format
text
id,Personality
18524,Extrovert
18525,Introvert
18526,Introvert
🗂️ Repository Structure
This repository contains implementations of various machine learning algorithms and techniques:

Supervised Learning Models
ADA_boost.ipynb - AdaBoost classifier implementation

XG_boost.ipynb - XGBoost gradient boosting model

Decision_tree.ipynb - Decision Tree classifier

Decision_tree2.ipynb - Alternative Decision Tree approach

random_forests.ipynb - Random Forest ensemble method

svm.ipynb - Support Vector Machine classifier

ANN's.ipynb - Artificial Neural Networks implementation

Unsupervised Learning & Clustering
Kmeans.ipynb - K-Means clustering analysis

DBScan.ipynb - DBSCAN density-based clustering

Advanced Techniques
ensemble.ipynb - Ensemble methods combining multiple models

autogluon.ipynb - AutoML approach using AutoGluon

🚀 Getting Started
Prerequisites
python
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn
autogluon
Usage
Clone this repository:

bash
git clone https://github.com/atheendre130505/Kaggle_introvert-extrovert.git
cd Kaggle_introvert-extrovert
Download the competition data from Kaggle

Run any of the Jupyter notebooks to explore different approaches:

For quick results: Start with autogluon.ipynb

For ensemble approach: Try ensemble.ipynb

For specific algorithms: Choose any individual model notebook

🏆 Model Performance
The competition features a unique situation where many top submissions achieve similar high accuracy scores, suggesting the public leaderboard may be based on a small portion of test data. This creates potential for significant changes in the private leaderboard rankings.

Key Insights
High Achievable Accuracy: Multiple participants have achieved 97%+ accuracy

Class Imbalance: The dataset shows approximately 51% extroverts and 49% introverts

Leaderboard Compression: Many top teams have identical public scores
