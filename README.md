# Product Review Opinion Mining

- NLP task to extract product features and assign positive or negative sentiment to those features.
- Data source is Amazon reviews of various products
- Spacy's NLP pipeline was used to first pre-process the data then identify nouns and noun phrases (potential features) along with adjectives (likely sentiment bearing)
- Features pruned using Pointwise Mutual Information (PMI)
- Sentiment analysed using Naive Bayes classification
- The final output are product summaries, consisting of the extracted features and aggregate sentiment towards those features
- The approach taken here was inspired by Hu and Liu, 2004 (https://www.cs.uic.edu/~liub/publications/kdd04-revSummary.pdf)
