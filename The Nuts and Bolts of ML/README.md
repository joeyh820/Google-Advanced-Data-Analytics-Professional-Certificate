# TikTok Claims Classification Project

## Project Title
Classification of TikTok Videos' Claim Status Using Machine Learning Models

## Project Description
The TikTok Claims Classification Project aims to automate the process of identifying TikTok videos that contain claims or offer opinions, reducing the backlog of user reports needing review by moderators. Utilizing a dataset of nearly 20,000 videos, the project explores the development and evaluation of machine learning models, particularly XGBoost and random forests, to classify videos based on their claim status. The final model, a random forest with 75 trees, demonstrated high precision, recall, and F-1 scores, leveraging user engagement metrics (views, likes, shares, downloads, and comments) as pivotal features for prediction.

## Business and Data Understanding
TikTok's moderation challenge stems from an overwhelming volume of user reports on videos containing claims, necessitating a prioritization system for efficient review. The project leverages a synthetic dataset created for the Google Advanced Data Analytics Professional Certificate Course, encompassing user engagement data and transcription texts across 19,382 videos. Initial data cleaning included dropping rows with missing values and unnecessary columns, encoding categorical variables, and feature engineering to enhance model accuracy.

## Modelling and Evaluation
The project's approach was methodical, starting with exploratory data analysis and hypothesis testing, followed by model building and rigorous evaluation. The champion model's importance plot highlighted the significant role of user engagement features in classification. A comprehensive evaluation, including a confusion matrix analysis, confirmed the model's robustness in accurately classifying videos, with minimal false positives and negatives.

## Conclusion and Further Steps
This initiative underscores the potential of machine learning in streamlining content moderation on platforms like TikTok. The predictive model not only facilitates the prioritization of user reports but also opens avenues for further exploration, such as incorporating natural language processing techniques to enhance feature sets and model performance.

### Note
The scenario and data in this project are entirely fictitious and do not represent TikTok or any real-world entities. This project serves as a practical application within the Google Advanced
