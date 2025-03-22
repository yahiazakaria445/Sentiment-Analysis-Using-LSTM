This project implements sentiment analysis on airline tweet data using an LSTM model, leveraging Natural Language Processing (NLP) techniques for text preprocessing and classification.

# Dataset
This dataset contains tweets related to major U.S. airlines, The data was scraped and labeled with sentiment categories as positive, neutral, or negative. [Dataset Link](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment?select=database.sqlite)

# libraries used
- numpy
- pandas
- matplotlib
- seaborn
- NLTK
- scikit-learn
- tensorflow
- re

# Text Preprocessing
Text data is cleaned through tokenization, lowercasing, and stop word removal, followed by padding to ensure uniform input for the LSTM model.

# Model architecture
| model  | optimizer | metrics |loss function  |accuracy score|batch size |regularization technique |
| -------- | -------- | -------- | -------- |-------- |-------- |-------- |
|  LSTM    | adam   |accuracy score    |categorical crossentropy    |0.91 |32 |Dropout|
  

