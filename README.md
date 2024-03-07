# RedditGoesGreen
Understand how public opinion about climate change has changed over time and how people feel about different emerging technologies (topic modelling)

## Abstract

We conduct an exploration of advanced Natural Language Processing (NLP) techniques to analyze the evolution of sentiment and discourse on climate change using the Reddit Climate Change Dataset. The aim of this project is to understand which NLP techniques are useful for deriving insights about public perceptions on climate change and how the different techniques compare with each other. The report outlines the methodology, models used, and the evaluation metrics employed. Sentiment analysis results reveal the effectiveness of Transformer-based models over Word2Vec, with notable nuances captured by ClimateBERT. Topic modeling, utilizing LDA and BERTopic, showcases the ability of BERTopic to extract more specific and nuanced topics. The findings provide valuable insights for policymakers, activists, and researchers hoping to utilize NLP techniques to understand public perceptions about climate, despite limitations. 

## File structure
1. `data` folder contains filtered data. Note: the majority of datasets are present in Google Drive due to their size.

2. `eda` folder contains all exploratory data analysis done on the raw dataset. Each file in this folder states the number of lines of code in it.

3. `models` folder contains all models that were investigated as part of this project. Each file in this folder states the number of lines of code in it.
