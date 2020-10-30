# BERT-for-Quora-Duplicates
Using the Bi-directional Encoder Representations from Transformers for Semantic Similarity on Quora duplicates dataset.


This project makes use of a BERT model to detect if two strings of text are similar. The bert-base-uncased was the model used for transfer learning. This model was trained in a self-supervised version and achieves about 89% accuracy on the test set.

For mode details on model, please see: https://huggingface.co/bert-base-uncased.

This example code from keras provided very great help for this task: https://keras.io/examples/nlp/semantic_similarity_with_bert/
