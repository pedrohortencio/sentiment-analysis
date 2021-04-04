# Sentiment Analysis
This repository contain Artificial Intelligence models that perform Sentiment Analysis in different datasets. The first model is a LSTM neural network capable of perform sentiment analysis in movie reviews.

❕ I built an interactive notebook that uses the pretrained model to classify any sentence into "Positive" or "Negative". You can try out easily by just running the following Google Colab Notebook (it works in any browser):
[Review Analyzer.](https://colab.research.google.com/github/pedrohortencio/sentiment-analysis/blob/main/IMDB%20Reviews/Review_Analyser.ipynb)


## IMDB Dataset
It's a combination of 50,000 reviews from IMDB, highly polarized, divided in binary classes (either positive or negative). I used the data from [Kaggle](https://ai.stanford.edu/~amaas/data/sentiment/), because it's already in a CSV format. The raw, .txt, data can be downloaded from [Stanford's AI Website](https://ai.stanford.edu/~amaas/data/sentiment/).

A LSTM Neural Network was trained to perform the sentiment analysis in the reviews. 
Final accuracy was ~88% both in validation and test datasets.


# Roadmap

I plan to continue to update this repository, creating models with a couple more datasets (the next one will problably be the Amazon Reviews dataset). I'm also interested in making the models more interactive.
