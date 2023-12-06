# Twitter-Sentiment-Analysis-of-US-Airlines-using-LSTM-BERT
Explore sentiment in U.S. airline tweets using Single Bidirectional LSTM, Stacked LSTM, and Unidirectional LSTM models. Evaluate model performance on a dataset of 14,485 tweets, examining accuracy, precision, recall, and F1 score. Dive into GloVe-based embeddings and attention mechanisms for enhanced sentiment analysis.
## Table of Contents
1. Data Preprocessing: Cleaning and preparing the dataset for analysis.
2. LSTM Models: Implementing and evaluating LSTM models for sentiment analysis.
   -Single-layer Unidirectional LSTM: : Implementation and results.
   - Single-layer Bidirectional LSTM:: Implementation and results.
   - Stacked Unidirectional LSTM:: Implementation and results.
   - Stacked Bidirectional LSTM: Implementation and results.
3. Evaluation: Metrics and performance analysis.
4. Attention Mechanism : Introduction and implementation of attention mechanism in LSTM.
4. BERT Models: Utilizing BERT for sentiment analysis.
   -  Training BERT models.
   -  Optimizing BERT model performance.
5.  RoBERTa tokenizer for analysis.
6. ANOVA: Conducting ANOVA to analyze model performance differences.
## Conclusion
This project focuses on sentiment analysis of Twitter data related to US airlines using various deep learning models. The analysis involves the implementation and comparison of different LSTM (Long Short-Term Memory) architectures, including single-layer bidirectional and unidirectional LSTMs, as well as stacked bidirectional and unidirectional LSTMs. Additionally, the project explores the integration of attention mechanisms into the LSTM models to enhance their performance. Furthermore, the sentiment analysis is extended to incorporate BERT (Bidirectional Encoder Representations from Transformers), a state-of-the-art pre-trained language model, to evaluate its effectiveness in capturing contextual information for sentiment 
# Model Comparison:
The project compares the performance of single-layer bidirectional and unidirectional LSTMs and their stacked counterparts. Evaluation metrics such as accuracy, precision, recall, and F1 score are employed for a comprehensive assessment.
# Attention Mechanism:
An attention mechanism is introduced to the LSTM model to improve its ability to focus on relevant parts of the input sequence, enhancing its performance in capturing context for sentiment analysis.
# BERT Integration:
The project incorporates BERT, a powerful transformer-based model, for sentiment analysis. The BERT model is fine-tuned on the airline Twitter dataset, and its performance is evaluated and compared with LSTM-based models.
# ANOVA Analysis:
An analysis of variance (ANOVA) is conducted to determine if there are significant differences in the performance of the LSTM models. The results provide insights into the relative effectiveness of different architectures.
# Hyperparameter Tuning:
Hyperparameter tuning is performed to optimize the performance of the BERT model. The project explores various combinations of learning rates, epochs, and batch sizes to identify the best hyperparameters.

