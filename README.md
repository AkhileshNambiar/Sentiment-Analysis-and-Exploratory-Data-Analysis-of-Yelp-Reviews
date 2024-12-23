# Sentiment-Analysis-and-Exploratory-Data-Analysis-of-Yelp-Reviews
This project leverages Exploratory Data Analysis (EDA) and Natural Language Processing (NLP) techniques to analyze Yelp reviews and uncover valuable insights. The main objectives of the project include:

Dataset Overview and Cleaning:

Loading and preprocessing a Yelp reviews dataset.
Handling missing values and converting date formats for temporal analysis.
Exploratory Data Analysis (EDA):

Performing descriptive analysis to summarize the dataset.
Visualizing review trends over time, including yearly review counts.
Analyzing the distribution of star ratings using bar plots and count plots.
Identifying patterns and trends in user feedback.
Text and Sentiment Analysis:

Using NLP techniques to tokenize review text and create word frequency distributions.
Generating word clouds to visualize commonly used words in reviews.
Mapping star ratings to sentiment categories (positive, neutral, negative) and analyzing their distribution.
Insights and Recommendations:

This project employs both traditional machine learning models and advanced deep learning approaches for sentiment analysis of Yelp reviews:

Logistic Regression:

Utilized with TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to classify review sentiments.
A robust baseline model for text classification tasks due to its simplicity and effectiveness for linearly separable data.
Transformer-based Models:

DistilBERT: A lightweight version of BERT, optimized for faster training and inference while retaining performance. Used for fine-tuning on the Yelp reviews dataset to perform sentiment classification.
BERT: Implemented for sequence classification tasks, leveraging pre-trained language representations to enhance the understanding of contextual word usage in reviews.
Training Setup for Transformers:

Tokenization using pre-trained tokenizers such as DistilBertTokenizer.
PyTorch datasets created for encoding input text and sentiment labels.
Model fine-tuned using the Trainer API from the Hugging Face library with performance metrics such as accuracy, precision, recall, and F1 score to evaluate the model's effectiveness.
