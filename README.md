# EmotionSense-NLP
Project Name: EmotionSense NLP
Start Date: 01-08-2024
Student: Usha
institute:Entry
mentor:jisma

Overview
EmotionSense NLP is an entry-level natural language processing project designed to classify emotions from text data. This project uses various machine learning models to analyze and categorize textual data into predefined emotional categories.

Project Goals
Text Preprocessing: Clean and prepare text data for analysis, including text cleaning, tokenization, and stopword removal.
Feature Extraction: Transform text data into numerical features using techniques such as CountVectorizer and TfidfVectorizer.
Model Development: Train and evaluate different machine learning models for emotion classification, including Naive Bayes and Support Vector Machine (SVM).
Model Evaluation: Compare model performance using metrics like accuracy, F1-score, and confusion matrix.
Dataset
The dataset consists of text comments labeled with different emotions. The main emotions in the dataset are:https://drive.google.com/file/d/1HWczIICsMpaL8EJyu48ZvRFcXx3_pcnb/view

Anger
Fear
Joy
Data Preprocessing
The following preprocessing steps were performed:

![image](https://github.com/user-attachments/assets/b0e7447e-ee79-42f0-b85b-b5dd96c37008)

![image](https://github.com/user-attachments/assets/c155fae8-0bed-4488-8ab2-d5591858c822)
![image](https://github.com/user-attachments/assets/9bce4ef9-14d9-4f9c-bbd0-1a8575d90f7c)

![image](https://github.com/user-attachments/assets/4c5d23f3-976b-4be2-825c-a52ae815674b)

![image](https://github.com/user-attachments/assets/52549a49-dddd-4076-84f6-f0eda3aaefbb)



Text Cleaning: Convert text to lowercase, remove short words, and remove punctuation.
Tokenization: Split text into tokens for analysis.
Stopword Removal: Remove common words that do not contribute to emotion classification.

Feature Extraction

![image](https://github.com/user-attachments/assets/d751ee64-e5b8-4b38-b0c2-67bab22b3044)

![image](https://github.com/user-attachments/assets/117173d8-4536-4d67-8dec-840a9c020745)

![image](https://github.com/user-attachments/assets/78359f9c-e57a-4577-908d-77ac89a74204)


Two feature extraction methods were used:

![image](https://github.com/user-attachments/assets/39ed3272-2311-43cb-9a75-5f868c67d16c)

![image](https://github.com/user-attachments/assets/d62c6619-7a98-4126-815e-abc6cbc82567)

![image](https://github.com/user-attachments/assets/3848f748-2b64-4b09-ae55-4011bcf36d7b)


CountVectorizer: Converts text into a matrix of token counts.
TfidfVectorizer: Converts text into a matrix of TF-IDF features, reflecting the importance of words in the dataset.
Model Development
The following models were trained and evaluated:

Naive Bayes: A probabilistic model based on Bayes' theorem.
Support Vector Machine (SVM): A model that finds the optimal hyperplane to separate different emotion classes.
Evaluation Metrics
Models were evaluated using:

Accuracy: The proportion of correctly classified instances.
F1-Score: The harmonic mean of precision and recall, providing a balance between them.
Results
Naive Bayes Model: Achieved an accuracy of 89.45% with balanced precision and recall across classes.
SVM Model: Achieved an accuracy of 89.84% with slightly better performance in precision and recall.
Visualizations
Class Distribution: Bar plot showing the distribution of emotions in the dataset.
Confusion Matrix: Visual representation of the model's classification performance.
Classification Report Heatmap: Heatmap displaying precision, recall, and F1-Score for each class.

Conclusion
The EmotionSense NLP project effectively utilized natural language processing techniques to classify emotions from text. Key achievements include:

Preprocessing: Text was cleaned, tokenized, and normalized to improve data quality.
Feature Extraction: Methods like CountVectorizer and TfidfVectorizer transformed text into useful numerical features.
Model Performance: Both Naive Bayes and Support Vector Machine (SVM) models performed well, with SVM achieving slightly higher accuracy and balanced classification results.
Overall, the SVM model provided the best performance for emotion classification, demonstrating the effectiveness of advanced NLP techniques in understanding and categorizing text-based emotions.

Contact Information:
For any questions or feedback, please contact Usha at [ushamuth18@gmail.com]

