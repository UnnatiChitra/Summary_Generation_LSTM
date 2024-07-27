# Summary_Generation_LSTM

**Objective:**
Develop an LSTM-based model to generate extractive summaries for news articles.

**Data:**
Utilized a dataset from Kaggle, containing a collection of news articles.

**Approach:**

1. **Data Preprocessing:**

- Tokenization: Converted text into sequences of tokens.
- Padding: Ensured uniform input length by padding sequences.
- Splitting: Divided data into training, validation, and test sets.
     
2. **Training:**

- Trained the LSTM model on the preprocessed dataset.
- Implemented techniques like dropout to prevent overfitting.
- Monitored training with validation loss and accuracy metrics.
  
3. **Evaluation:**

- Used the ROUGE (Recall-Oriented Understudy for Gisting Evaluation) score to evaluate the performance.
- ROUGE scores provide a measure of the overlap between the generated summaries and the reference summaries.
- Focused on ROUGE-N (unigram, bigram) and ROUGE-L (longest common subsequence) scores.
  
**Results:**

- The model successfully generated extractive summaries that captured the essence of the news articles.
- Achieved competitive ROUGE scores, indicating the effectiveness of the model in summarization tasks.


