# Observing the Impact of Training Data Size on the Performance of Deep Learning Models

This Repo contains the code used for the design and implementation of a classifier to detect offensive speech using the OLID dataset. Two classifiers were adopted: a Long-Short-Term Memory (LSTM) classifier and a BERT-sequence classifier. 

The LSTM classifier was chosen due to its ability to work with sequential data and its robustness to noisy data. The BERT-sequence classifier was selected for its state-of-the-art performance on a wide range of NLP tasks. The training of models involved data preprocessing, including data cleaning and data visualization, to understand the data and extract meaningful insights. The models were trained on different sizes of training data, and their performances were evaluated on test data.

The results showed that the performance of both classifiers was affected by the size of the training data. The BERT-sequence classifier outperformed the LSTM classifier in most cases, but both classifiers had lower performance on offensive tweets due to class imbalance. Overall, this study demonstrates the effectiveness of LSTM and BERT-sequence classifiers in detecting offensive speech and provides insights into the impact of training data size on classifier performance.

The Inspiration was taken from :
1. https://www.kaggle.com/code/derrelldsouza/imdb-sentiment-analysis-eda-ml-lstm-bert/notebook
2. https://huggingface.co/docs/transformers/model_doc/bert#transformers.BertForSequenceClassification
