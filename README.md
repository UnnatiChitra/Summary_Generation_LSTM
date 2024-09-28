# Test Summarization using LSTM Encoder-Decoder

Text summarization is the problem of creating a short, accurate, and fluent summary of a longer text document. It is a Natural Language Processing application which produces short and meaningful summary of a lengthy paragraph thereby helping us to understand the essence of the topic in an efficient way.

Automatic text summarization methods are greatly needed to address the ever-growing amount of text data available online to both better help discover relevant information and to consume relevant information faster.

Text Summarization
1. **Abstrative Based**: In Abstractive based, we generate new sentences from the original text. The sentences generated through abstractive summarization might not be present in the original text.

## Problem Statement
Customer reviews can be lengthy and detailed. Manually analysing these reviews, as you might guess, takes a long time. This is where Natural Language Processing's application can be put to use to develop a short summary for lengthy reviews.

Our objective here is to generate a summary for the "Amazon Fine Food reviews" using the abstraction-based text summarization approaches.

Data Scource: [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews?select=Reviews.csv)

## Project pipeline
1. Understanding Text Summarization,
2. Text pre-processing,
3. Abstractive Text Summarization using LSTM, ENCODER-DECODER architecture,
4. Web scrape an article using BS4.

## Results
### Abstractive Text Summarization 

Original text: ``gluten free want crackers one also delicious second order``<br>
Predicted summary:  ``great gluten free baking``


Original text: ``coffee tastes like regular coffee good weak used little less water regular strength coffee taste great smell better whether works stomach needed sure ``<br>
Predicted summary:  ``good coffee``


Original text: ``first time italy wife actually give gifts well good sucks seasonal definitely makes look forward holidays``<br>
Predicted summary:  ``the best``
