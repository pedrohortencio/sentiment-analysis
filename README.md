# Sentiment Analysis
This repository contain Artificial Intelligence models that perform Sentiment Analysis in different datasets. The first model is a LSTM neural network capable of perform sentiment analysis in movie reviews.


## IMDB Dataset
It's a combination of 50,000 reviews from IMDB, highly polarized, divided in binary classes (either positive or negative). I used the data from [Kaggle](https://ai.stanford.edu/~amaas/data/sentiment/), because it's already in a CSV format. The raw, .txt, data can be downloaded from [Stanford's AI Website](https://ai.stanford.edu/~amaas/data/sentiment/).

A LSTM Neural Network was trained to perform the sentiment analysis in the reviews. I built an iteractive notebook that uses the pretrained model and it can be easily run using the Google Colab:
[Review Analyzer.](https://colab.research.google.com/github/pedrohortencio/sentiment-analysis/blob/main/IMDB%20Reviews/Review_Analyser.ipynb)

Final accuracy was ~88% both in validation and test datasets.
