# Assignment 7 of CS 203: Software Tools and Techniques for AI

## Text Classification with Model Checkpointing

### Datasets Used
- **Dataset 1**: `train.tsv` and `test.tsv`
- **Dataset 2**: `IMDB.csv`

### Embedding Methods
The text data from the datasets is converted to embeddings using two different methods:
1. **Bag of Words**
2. **bert-base-uncased embeddings**

### Classification
These embeddings are then used to train an MLP classifier to classify the text data into two classes: positive and negative. The results from both embeddings are then compared. 