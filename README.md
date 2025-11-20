# Question-pair-similarity-classification
Question pair similarity classification Using Machine learning .

 Exploratory Data Analysis-EDA
-imports Necessary Librarry 
-cvs file detect encoding
- Load Dataset
- Visualize Distribution of Target Variable
- Text Length Analysis
analyze sentence length by number of words and number of characters.
- Text Length Distribution
- Compare Duplicate vs Non-Duplicate
- Word Cloud Analysis
- Correlation Analysis (Feature Engineering Preview)

 Text Processing
- Lowercasing
- Removing special characters & numbers
- Removing stopwords
- Lemmatization
Apply Preprocessing to Both Questions
Combine Both Questions into a Single Feature
 - ML models expect one representation per sample.

TF-IDF Feature Extrection
Using TensorFlow/Keras

model building 
- Baseline — Logistic Regression on TF-IDF
- Siamese LSTM
- Using pretrained embeddings (GloVe) — quick instructions
- Transfer learning with BERT / DistilBERT (outline)

  AUC-ROC Curve
Measures how well model distinguishes duplicate vs non-duplicate pairs.

Using Keras Tuner for LSTM
Manual Hyperparameter Tuning
