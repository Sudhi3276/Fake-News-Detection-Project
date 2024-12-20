
# Hey, Sudhindra P is here! 

Myself Sudhindra P, and I’m thrilled to share this exciting project on **Fake News Detection using Machine Learning**. This project focuses on tackling the spread of misinformation by leveraging machine learning techniques to classify news articles as fake or real.

---

## Abstract
The advent of the World Wide Web and the rapid adoption of social media platforms (e.g., Facebook, Twitter) have enabled unprecedented information dissemination. However, this also leads to the spread of misleading or fake information. Automated classification of misinformation and disinformation is a challenging task, even for experts.

This project proposes a machine learning ensemble approach for automating the classification of news articles. By exploring various textual features, we train a combination of machine learning algorithms and evaluate their performance on four real-world datasets. Our experimental results demonstrate the superior performance of the proposed ensemble learner approach.

---

## Features
- **Dataset Handling**: Handles missing values and merges text attributes (`title`, `author`, `text`) into a single column for analysis.
- **Text Vectorization**: Utilizes TF-IDF and CountVectorizer for feature extraction.
- **Machine Learning Models**: Implements models like:
  - Naive Bayes (MultinomialNB)
  - Logistic Regression
  - Passive Aggressive Classifier
- **Evaluation Metrics**: Evaluates model performance using metrics such as accuracy, precision, recall, and F1-score.
- **Visualization**: Includes confusion matrix visualization for performance evaluation.

---

## Requirements
Install the necessary libraries using the command:

```bash
pip install -r requirements.txt
