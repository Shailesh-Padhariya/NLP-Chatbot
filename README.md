# NLP-Chatbot
A deep learning chatbot built with TensorFlow that processes stories and questions using NLP techniques, then predicts yes/no answers by understanding context through LSTM-based sequence modeling.


Chatbot NLP Project 
Project: Conversational Question-Answering Chatbot using Deep Learning (TensorFlow/Keras)

Description:
Developed a deep learning-based chatbot that answers yes/no questions about given stories using an encoder-decoder architecture with LSTM layers. The chatbot processes story and question pairs, tokenizes and vectorizes them, then predicts answers with a softmax classifier over vocabulary terms.

Key Features:

Data loading and preprocessing from pickled story-question-answer datasets.

Vocabulary building and tokenization with Keras Tokenizer.

Sequence padding to ensure uniform input length for RNN.

Encoder-decoder model architecture combining story and question embeddings.

Attention-like mechanism via dot-product and additive operations to link story and query.

Trained on custom yes/no answer dataset with batch size 32 over 30 epochs.

Model evaluation and prediction with accuracy tracking.

Custom input prediction demonstrating inference capabilities.

Environment: Python, TensorFlow, Keras, NumPy, Pickle

Performance: Achieved solid accuracy with binary yes/no classification on test dataset.
